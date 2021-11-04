<template>
  <div>
    <Nuxt />
  </div>
</template>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700;900&display=swap');

html {
  font-family:
    'Poppins',
    -apple-system,
    BlinkMacSystemFont,
    'Segoe UI',
    Roboto,
    'Helvetica Neue',
    Arial,
    sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
  background: #0F1011;
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}

.logo {
  margin-top: 30px;
  width: 100px;
}

a {
  text-decoration: none;
  color: white
}

.container {
  text-align: center;
  min-height: 100vh;
  width: 90vw;
  max-width: 800px;
}

.row {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}

.center {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.left {
  display: flex;
  justify-content: flex-start;
  align-items: left;
}

.border {
    border-radius: 6px;
}

.maxWidth {
  max-width: 800px;
}

</style>
