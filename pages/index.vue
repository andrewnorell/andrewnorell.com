<template>
  <div class="u-container">
    <h1>👋 <br>I’m Andrew Norell, a Tech Lead, Product Owner, and Frontend Dev living in Minneapolis, MN.</h1>
    <a href="https://www.linkedin.com/in/andrewnorell/" title="Andrew Norell on LinkedIn">
      <svg width="24" height="24" fill="none" xmlns="http://www.w3.org/2000/svg">
        <g clip-path="url(#clip0)" fill="#46025D">
          <path d="M4.011 7.644h-.814a2.188 2.188 0 00-1.668.375 1.618 1.618 0 00-.403 1.221v13.217a1.556 1.556 0 00.395 1.2A1.585 1.585 0 002.69 24c.38 0 .711-.036 1.412-.01a2.058 2.058 0 001.586-.343 1.56 1.56 0 00.393-1.2V9.24a1.618 1.618 0 00-.402-1.22 2.174 2.174 0 00-1.668-.376zM3.6 0A2.775 2.775 0 00.873 2.674 2.832 2.832 0 003.6 5.462a2.763 2.763 0 002.743-2.788A2.774 2.774 0 003.6 0zM17.098 7.48a5.33 5.33 0 00-3.588 1.08 1.243 1.243 0 00-.31-.616 1.043 1.043 0 00-.775-.305 20.412 20.412 0 00-2.571.051c-.713.144-1.06.65-1.06 1.543v13.224a1.567 1.567 0 00.391 1.2 2.068 2.068 0 001.588.343c.766-.03.984.01 1.409.01a1.586 1.586 0 001.17-.343 1.565 1.565 0 00.395-1.2v-7.059a2.14 2.14 0 012.184-2.38 2.132 2.132 0 012.24 2.38v7.05a1.56 1.56 0 00.393 1.2 2.055 2.055 0 001.584.342c.314-.012.686-.012.994 0a2.072 2.072 0 001.588-.343 1.566 1.566 0 00.39-1.2v-9.03a5.67 5.67 0 00-6.022-5.948z" />
        </g>
        <defs>
          <clipPath id="clip0">
            <path fill="#fff" d="M0 0h24v24H0z" />
          </clipPath>
        </defs>
      </svg>
    </a>
  </div>
</template>

<style lang="scss">
  .u-container {
    max-width: 72rem;
    margin: 0 auto;
  }
</style>

<style lang="scss" scoped>
  h1 {
    color: $purple;
    font-size: 2.4rem;
    line-height: 1.5;
    font-weight: 600;
    text-align: center;
    margin-bottom: 1.5em;
    font-family: $font-family-sans-serif;
  }

  @media (min-width: $screen-sm-min) {
    h1 {
      font-size: 4rem;
    }
  }

  a {
    display: block;
    margin: 0 auto;
    width: 2.4rem;
    height: 2.4rem;
    transition: opacity 0.1s ease-out;

    svg {
      display: block;
      width: 2.4rem;
      height: 2.4rem;
    }

    &:hover,
    &:focus {
      opacity: 0.75;
    }
  }
</style>
