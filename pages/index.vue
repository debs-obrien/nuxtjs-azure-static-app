<template>
  <div>
    <div>
      <h1 class="title">
        Nuxt.js & Azure
      </h1>
      <h2 class="subtitle">
        Deploying your static site to Azure Static Web Apps
      </h2>
      <div class="links">
          <div>
            <ul>
            <li>
              <NuxtLink to="/about" >About page</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/spa-fallback" >Spa Fallback page</NuxtLink>
            </li>
            <li>
              <NuxtLink to="/404" >Custom error page</NuxtLink>
            </li>
          </ul>
          </div>
          <div>
            <a
          href="https://github.com/debs-obrien/nuxtjs-azure-static-app"
          target="_blank"
          class="button--grey"
        >
          GitHub
        </a>
        <a href="https://nuxtjs.org/faq/deployment-azure-static-web-apps" target="_blank" class="button--green">
          Documentation
        </a>
          </div>
        
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>

<style scoped>
.links {
  display: flex;
  flex-direction: column;
  padding-top: 15px;
}
ul{
  list-style: none;
  display: flex;
  flex-direction: row;
  margin-bottom: 40px;
  text-align: center;
  justify-content: center;
}
li{
  padding: 0 20px;
}
</style>
