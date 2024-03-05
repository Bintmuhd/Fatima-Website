<script>
import { RouterLink, RouterView } from "vue-router";
// import { CIcon } from "@coreui/icons-vue";
// import { cilList, cilShieldAlt } from "@coreui/icons";
// export default {
//   components: {
//     CIcon,
//   },
//   setup() {
//     return {
//       cilList,
//       cilShieldAlt,
//     };
//   },
// };
</script>

<template>
  <div>
    <!-- <CIcon :icon="cilList" width="36" customClassName="icon" />
    <CIcon :icon="cilShieldAlt" width="36" customClassName="icon" /> -->
  </div>
  <section class="section">
    <main>
      <div class="hero">
        <p>Fatima Muhammad</p>
        <h1>Frontend Developer</h1>
        <hr />
        <h1>Technical Writer</h1>
      </div>

      <!-- <div class="social">
        <p>F</p>
        <p>T</p>
        <p>M</p>
        <p>L</p>
        
      </div> -->

      <div class="social"></div>
    </main>

    <main>
      <nav class="pages">
        <!-- <RouterLink to="/">Home</RouterLink> -->
        <RouterLink to="/about" class="router-link">ABOUT</RouterLink>
        <RouterLink to="/about" class="router-link">PROJECTS</RouterLink>
        <RouterLink to="/about" class="router-link">TALKS</RouterLink>
        <RouterLink to="/about" class="router-link">ARTICLES</RouterLink>
      </nav>
    </main>
  </section>
</template>

<style scoped>
section {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 90vh;
}
.hero h1 {
  font-size: 60px;
  font-weight: 500;
}
.hero p {
  font-size: 20px;
}

.social {
  margin-top: 2rem;
  width: 50%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.router-link {
  font-weight: 500;
  padding: 10px;
}

.pages {
  display: flex;
  flex-direction: column;
}
</style>
