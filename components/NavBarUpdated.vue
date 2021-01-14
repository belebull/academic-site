<template>
  <div class="menu">
    <div class="w-full inline-flex justify-between items-center bg-teal-200 p-4 font-header text-teal-100">
      <div class="site-title">
        <span class="text-4xl">Beleicia Bullock</span>
      </div>
      <div class="mobile-menu-btn">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
          class="feather feather-menu stroke-current"
        ><line x1="3" y1="12" x2="21" y2="12" /><line x1="3" y1="6" x2="21" y2="6" /><line x1="3" y1="18" x2="21" y2="18" /></svg>
      </div>
    </div>
    <div class="mobile-menu absolute w-screen bg-teal-200 text-teal-100 shadow-lg px-12 py-16">
      <div class="mobile-menu-content">
        <div class="close-icon h-4 relative">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="32"
            height="32"
            viewBox="0 0 32 32"
            fill="#CCD7D8"
            stroke="#CCD7D8"
            stroke-width="2"
            stroke-linecap="round"
            stroke-linejoin="round"
            class="feather feather-x absolute right-0"
          ><line x1="18" y1="6" x2="6" y2="18" /><line x1="6" y1="6" x2="18" y2="18" /></svg>
        </div>
        <div class="mobile-header flex flex-row flex-nowrap items-center mx-8">
          <div class="mobile-profile mx-3">
            <img
              src="~/static/profile.jpg"
              alt="Beleicia in front of La Cathedral in Spain"
              class="h-20 w-20 rounded-2xl"
            >
          </div>
          <div class="mobile-header-text">
            <div class="font-header font-bold text-xl">
              Beleicia Bullock
            </div>
            <div class="font-header text-base">
              CS Graduate Student
            </div>
          </div>
        </div>
        <div class="mobile-menu-items">
          <ul class="mobile-menu-items-list font-header font-bold font-3xl">
            <li class="text-center mb-8 focus:bg-teal-100 focus:text-teal-200">
              <nuxt-link to="">
                Home
              </nuxt-link>
            </li>
            <li class="text-center mb-8">
              <nuxt-link to="">
                About
              </nuxt-link>
            </li>
            <li class="text-center mb-8">
              <nuxt-link to="">
                Research
              </nuxt-link>
            </li>
            <li class="text-center">
              <nuxt-link to="">
                Experience
              </nuxt-link>
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.mobile-menu {
  border-radius: 0px 0px 65px 65px;
  height: 70%;
  top: 0;
  z-index: 0;
}
</style>
