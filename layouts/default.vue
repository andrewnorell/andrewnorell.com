<template>
  <div>
    <Nuxt />
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
  background-color: $white;
}

body {
  display: flex;
  flex-direction: column;
  min-height: 100vh;
  font-size: 1.8rem;
  line-height: 1.5;
  font-weight: 400;
  padding: 0;
  background-color: $white;

  #__nuxt,
  #__layout,
  #__layout > * {
    flex: 1 0 auto;
    display: flex;
    flex-direction: column;
  }

  #main {
    flex-grow: 1;
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
