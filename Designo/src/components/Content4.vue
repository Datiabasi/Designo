<template>
  <div class="footer pt-md-5">
    <div class="pt-md-3">
      <div class="container px-md-5">
        <div class="desktop">
          <div class="nav-section py-4">
            <nav class="navbar navbar-expand-lg navbar-light">
              <a class="navbar-brand" href="#"
                ><img src="../assets/logo-light.png" alt="logo" width="37%"
              /></a>
              <button
                class="navbar-toggler"
                type="button"
                data-toggle="collapse"
                data-target="#navbarNavDropdown"
                aria-controls="navbarNavDropdown"
                aria-expanded="false"
                aria-label="Toggle navigation"
              >
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav ml-auto">
                  <li class="nav-item">
                    <a class="nav-link" href="#">Our Company</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link ml-4" href="#">Locations</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link ml-4" href="#">Contact</a>
                  </li>
                </ul>
              </div>
            </nav>
          </div>
          <hr />
        </div>
        <div class="mobile my-5 py-5">
          <a class="navbar-brand pb-3 pt-3 text-center" href="#"
            ><img src="../assets/logo-light.png" alt="logo" width="65%"
          /></a>
          <hr />
          <div class="text-center">
            <ul class="">
              <li class="nav-item">
                <a class="nav-link" href="#">Our Company</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Locations</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Contact</a>
              </li>
            </ul>
          </div>
        </div>
        <div class="footer-main d-flex justify-content-between pt-3 pb-5">
          <div class="items">
            <p class="b">Designo CentralOffice</p>
            <p>3886 Wellington Street</p>
            <p>Toronto, Ontario M9C 3J5</p>
          </div>
          <div class="items">
            <p class="b">Contact Us (Central office)</p>
            <p class="b">P : +1 253-863-8967</p>
            <p class="b">M : contact@designo.co</p>
          </div>
          <div class="d-flex align-items-end">
            <div class="d-flex">
              <div class="icon pr-3">
                <img src="../assets/desktop/icon-facebook.svg" alt="" />
              </div>
              <div class="icon pr-3">
                <img src="../assets/desktop/icon-youtube.svg" alt="" />
              </div>
              <div class="icon pr-3">
                <img src="../assets/desktop/icon-twitter.svg" alt="" />
              </div>
              <div class="icon pr-3">
                <img src="../assets/desktop/icon-pinterest.svg" alt="" />
              </div>
              <div class="icon pr-3">
                <img src="../assets/desktop/icon-instagram.svg" alt="" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
.mobile {
  display: none;
}
.footer {
  background-color: #1d1d1f;
}
.nav-link {
  text-transform: uppercase;
  color: #fff !important;
  letter-spacing: 2px;
  font-size: 13px;
  font-weight: 400;
}
.navbar {
  padding: 0 !important;
  margin: 0 !important;
}
hr {
  background-color: #8a8a8c77 !important;
}
p {
  color: #8a8a8c;
  font-size: 14px;
  margin: 0;
}
.b {
  font-weight: 600;
}
@media (min-width: 0px) and (max-width: 767.98px) {
  .container {
    padding-top: 10rem;
  }
  .mobile {
    display: contents;
  }
  .desktop {
    display: none;
  }
  .footer-main {
    flex-direction: column;
    align-items: center;
  }
  .items {
    margin-bottom: 2rem;
  }
  .nav-link {
    font-size: 16px;
  }
}
@media (min-width: 375px) and (max-width: 424.98px) {
}
@media (min-width: 0px) and (max-width: 374.98px) {
}
</style>