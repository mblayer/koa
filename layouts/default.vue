<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>
html {
  font-family: Roboto, -apple-system, BlinkMacSystemFont, 'Segoe UI',
    'Helvetica Neue', Arial, sans-serif;
  font-size: 18px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background-color: #000e15;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  color: #e5cf3e;
  text-decoration: none;
  padding: 10px 30px;
  font-size: 25px;
}

.button--green:hover {
  color: #fff;
}
.subtitle {
  font-weight: 700;
  font-size: 50px;
  color: #e5cf3e;
  word-spacing: 5px;
  padding-bottom: 15px;
  text-align: center;
}
</style>
