<template>
  <div>
    <main>
      <Nuxt />
    </main>
  </div>
</template>

<style lang="scss">
*,
*::before,
*::after {
  box-sizing: inherit;
}

html {
  font-size: 10px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  box-sizing: border-box;
  background: linear-gradient(135deg, rgba(255, 172, 198, 0.7) 2.88%, rgba(182, 224, 245, 0.7) 100%);
  animation: BackgroundGradient 6s ease infinite;
  background-size: 400% 400%;
}

@keyframes BackgroundGradient {
  0% {
    background-position: 50% 0%;
  }

  50% {
    background-position: 51% 100%;
  }

  100% {
    background-position: 50% 0%;
  }
}

body {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  font-size: 1.8rem;
  line-height: 1.5;
  font-weight: 400;
  padding: 0;
  background-color: transparent;

  #__nuxt,
  #__layout,
  #__layout > * {
    flex: 1 0 auto;
    display: flex;
    flex-direction: column;
  }

  #__nuxt {
    background-image: url('~assets/images/border.svg');
    background-repeat: repeat-x;
    background-position: center top;
  }

  main {
    flex-grow: 1;
    display: flex;
    flex-direction: column;
    justify-content: center;
    background-image: url('~assets/images/border.svg');
    background-repeat: repeat-x;
    background-position: center bottom;
    padding: 6.4rem 2rem;

    @media (min-width: $screen-sm-min) {
      padding: 12.8rem 2rem;
    }
  }
}

img,
svg,
video {
  max-width: 100%;
  height: auto;
}

button,
input,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}

.a11y-only,
.u-hidden {
  border: 0;
  clip: rect(0 0 0 0);
  height: 1px;
  margin: -1px;
  overflow: hidden;
  padding: 0;
  position: absolute;
  width: 1px;
}

.u-container {
  margin: 0 auto;
  max-width: 144rem;
}
</style>
