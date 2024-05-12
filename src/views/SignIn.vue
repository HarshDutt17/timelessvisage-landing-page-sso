<template>
  <div>
    <navbar-component></navbar-component>
    <main>
      <div class="relative pt-16 pb-32 flex content-center items-center justify-center" style="min-height: 75vh;">
        <div class="absolute top-0 w-full h-full bg-center bg-cover"
          style='background-image: url("https://images.unsplash.com/photo-1557804506-669a67965ba0?ixlib=rb-1.2.1&amp;ixid=eyJhcHBfaWQiOjEyMDd9&amp;auto=format&amp;fit=crop&amp;w=1267&amp;q=80");'>
          <span id="blackOverlay" class="w-full h-full absolute opacity-75 bg-black"></span>
        </div>
        <div class="container relative mx-auto">
          <div class="items-center flex flex-wrap">
            <div class="w-full lg:w-6/12 px-4 ml-auto mr-auto text-center">
              <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-8 shadow-lg rounded-lg">
                <div class="px-4 py-5 flex-auto">
                  <div
                    class="text-white p-3 text-center inline-flex items-center justify-center w-12 h-12 mb-5 shadow-lg rounded-full bg-blue-400">
                    <i class="fas fa-user"></i>
                  </div>
                  <h6 class="text-xl font-semibold">Sign In with SSO services</h6>
                  <div class="flex flex-col items-center gap-2 my-8">
                    <button
                      class="w-fit flex bg-blue-500 text-gray-200 active:bg-gray-100 text-sm   px-4 py-2 rounded shadow hover:shadow-md outline-none focus:outline-none lg:mr-1 lg:mb-0 ml-3 mb-3 w-1/2 my-2 "
                      type="button" style="transition: all 0.15s ease 0s;">
                      <img alt="..." src="../assets/img/Timelessviasge.png" class="max-w-1/2 w-1/2 ml-8 mr-2"
                        style="max-width: 20px;" />
                      <a href="http://localhost:8080">Sign in with &nbsp;<b> TimelessVisage </b> </a>
                    </button>
                    <button
                      class="w-fit bg-blue-500 text-gray-200 active:bg-gray-100 text-sm   px-4 py-2 rounded shadow hover:shadow-md outline-none focus:outline-none lg:mr-1 lg:mb-0 ml-3 mb-3 w-1/2 my-2"
                      type="button" style="transition: all 0.15s ease 0s;">
                      <i class="fab fa-facebook pr-2"></i> Sign in with Facebook
                    </button>
                    <button
                      class="w-fit bg-blue-500 text-gray-200 active:bg-gray-100 text-sm  px-4 py-2 rounded shadow hover:shadow-md outline-none focus:outline-none lg:mr-1 lg:mb-0 ml-3 mb-3 w-1/2 my-2"
                      type="button" style="transition: all 0.15s ease 0s;">
                      <i class="fab fa-google pr-2"></i> Sign in with Google
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="top-auto bottom-0 left-0 right-0 w-full absolute pointer-events-none overflow-hidden"
          style="height: 70px;">
          <svg class="absolute bottom-0 overflow-hidden" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none"
            version="1.1" viewBox="0 0 2560 100" x="0" y="0">
            <polygon class="text-gray-300 fill-current" points="2560 0 2560 100 0 100"></polygon>
          </svg>
        </div>
      </div>
    </main>
    <footer-component></footer-component>
  </div>
</template>
<script>
import NavbarComponent from "../components/Navbar.vue";
import FooterComponent from "../components/Footer.vue";
export default {
  name: "Signin",
  components: {
    NavbarComponent,
    FooterComponent
  }
}
</script>
