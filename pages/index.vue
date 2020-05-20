<template>
  <div>
    <div>
      <div class="logos">
        <svg width="159" height="121" viewBox="0 0 159 121" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M157.761 105.868L111.987 24.1688C108.222 17.5147 98.4678 17.5147 94.6956 24.161L89.7988 32.8924L95.4844 42.9907L103.396 29.1359L149.045 110.281H132.785C133.628 115.451 129.161 120.504 122.796 120.504H149.107C156.628 120.512 161.384 112.335 157.761 105.868Z" fill="#158876"/>
<path d="M47.2504 110.281H10.0049L66.2285 10.2203L84.4959 42.4284L89.8066 32.9003L73.8197 4.50341C70.4146 -1.51803 61.9252 -1.4946 58.5514 4.53466L1.14849 107.141C-2.21758 113.155 2.21845 120.512 9.21614 120.512H57.2393C50.8742 120.512 46.4069 115.459 47.2504 110.281Z" fill="#41B38A"/>
<path d="M132.785 110.281C132.636 109.359 132.316 108.438 131.816 107.532L95.4922 42.9907L89.8066 32.8924L84.4958 42.4205L48.211 107.54C47.7111 108.438 47.3987 109.359 47.2425 110.273C46.3991 115.443 50.8742 120.496 57.2314 120.496H59.0277H122.78H122.788C129.153 120.504 133.62 115.459 132.785 110.281ZM57.7 110.281L90.1112 52.8858L122.327 110.281H57.7Z" fill="#243746"/>
</svg>
<img src="azure.png" alt="azure">
      </div>
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
svg{
  padding-right: 20px;
}
img{
  height: 120px;
}
</style>
