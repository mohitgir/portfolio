<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">Mohit Gir <br /><i>Web Developer</i></h1>
      <div class="links">
        <a
          href="mailto:mohitgir98@outlook.com"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Email Me
        </a>
       <a
          href="/resume-v1.pdf"
          target="_blank"
          rel="noopener noreferrer"
          class="button--green"
        >
          Resume
        </a>
        <!-- <a
          href="https://github.com/mohitgir"
          target="_blank"
          rel="noopener noreferrer"
          class="button--grey"
        >
          GitHub
        </a> -->
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style lang="scss">
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 5rem;
  @media only screen and (max-width: 600px) {
    font-size: 3rem;
  }
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
