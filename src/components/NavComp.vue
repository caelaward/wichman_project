<template>
  <div class="sticky-top" id="navDiv">
    <nav class="navbar navbar-expand-lg p-3">
      <div class="container-fluid ">
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse justify-content-center" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <router-link :to="{ name: 'home' }" class="nav-link " :class="{ 'active': currentRoute === 'home' }" @click="collapseNavbar" exact>Home</router-link>
            <router-link :to="{ name: 'about' }" class="nav-link " :class="{ 'active': currentRoute === 'about' }" @click="collapseNavbar">About</router-link>
            <router-link :to="{ name: 'service' }" class="nav-link " :class="{ 'active': currentRoute === 'service' }" @click="collapseNavbar">Services</router-link>
            <div class="dropdown">
              <button class="dropbtn nav-link">Catalogue</button>
              <div class="dropdown-content">
                <a @click="downloadPDF('/path/to/your/pdf.pdf')">PDF File</a>
                <a @click="downloadPDF('/path/to/your/pdf.pdf')">PDF File 2</a>
              </div>
            </div>
            <router-link :to="{ name: 'projects' }" class="nav-link " :class="{ 'active': currentRoute === 'projects' }" @click="collapseNavbar">Our Work</router-link>
            <router-link :to="{ name: 'contact' }" class="nav-link " :class="{ 'active': currentRoute === 'contact' }" @click="collapseNavbar">Contact</router-link>

         
         
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentRoute: ''
    };
  },
  created() {
    this.currentRoute = this.$route.name;
  },
  watch: {
    $route(to) {
      this.currentRoute = to.name;
    }
  },
  methods: {
    collapseNavbar() {
      if (window.innerWidth < 992) {
        const navbarToggler = document.querySelector('.navbar-toggler');
        const navbarCollapse = document.querySelector('.navbar-collapse');
        if (navbarCollapse.classList.contains('show')) {
          navbarToggler.click();
        }
      }
    },
    downloadPDF(pdfUrl) {
      // Create a link element
      const link = document.createElement('a');
      link.href = pdfUrl;
      // Set the download attribute to force download
      link.setAttribute('download', 'filename.pdf');
      // Append to the document body
      document.body.appendChild(link);
      // Trigger the click event to start download
      link.click();
      // Cleanup
      document.body.removeChild(link);
    }
  }
};
</script>

<style>
#logo {
  width: 25px;
  height: 30px;
  padding: 2px;
  mix-blend-mode: multiply;
  transition: transform 0.3s;
}

#logo:hover {
  transform: scale(1.2);
}

.nav-link.active {
  font-weight: bold;
  text-decoration: underline;
}

#navDiv {
  background-color: rgb(219, 193, 132);
}

.dropbtn {
  color: white;
  padding: 8px;
  font-size: 16px;
  border: none;
  cursor: pointer;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
  z-index: 1;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown-content a:hover {
  background-color: #f1f1f1;
}
</style>
