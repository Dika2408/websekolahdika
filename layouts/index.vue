<template>
  <div id="app">
    <!-- Header -->
    <header-component></header-component>

    <!-- Navigation Bar -->
    <navbar-component></navbar-component>

    <!-- Profile Section -->
    <profile-section></profile-section>

    <!-- Footer -->
    <footer-component></footer-component>
  </div>
</template>

<script>
export default {
  components: {
    'header-component': {
      template: `
        <div class="header" style="background-color: #0056b3; color: white; padding: 15px 0; text-align: center;">
          <h1>SMK NEGERI 4 TASIKMALAYA</h1>
        </div>
      `
    },
    'navbar-component': {
      template: `
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
          <div class="container-fluid">
            <a class="navbar-brand" href="#">SMKN 4</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
              <ul class="navbar-nav">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="#">Beranda</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Profil</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Kurikulum</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Gallery</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">Informasi</a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#">PPDB</a>
                </li>
              </ul>
            </div>
          </div>
        </nav>
      `
    },
    'profile-section': {
      template: `
        <div class="profile-section" style="text-align: center; margin-top: 20px;">
          <img src="logo-placeholder.png" alt="Logo SMKN 4" class="img-fluid" style="max-width: 100px;">
          <h2>Profil SMK Negeri 4 Tasikmalaya</h2>
          <p>Jl. Depok, Sukamenak, Kec. Purbaratu, Kota Tasikmalaya, Jawa Barat 46196</p>
        </div>
      `
    },
    'footer-component': {
      template: `
        <div class="footer" style="background-color: #0056b3; color: white; text-align: center; padding: 10px 0; margin-top: 20px;">
          <p>&copy;copyright SMKNA TASIKMALAYA</p>
        </div>
      `
    }
  }
};
</script>

<style>
body {
  font-family: Arial, sans-serif;
}
</style>
