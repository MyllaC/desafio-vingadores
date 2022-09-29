<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <body>
    <header>
      <div>
        <nav
            class="h-14 rounded flex items-center justify-between bg-pink-100 shadow-pink-900 shadow-md drop-shadow-md hover:shadow-pink-800 hover:shadow-lg hover:drop-shadow-lg">
          <span
              class="text-3xl font-black italic tracking-wider mx-10 text-pink-900 brightness-150">Scarlet
            Witch</span>

          <div class="flex items-center mx-10 space-x-18">
            <RouterLink
                class="text-2xl mx-4 text-[#810D27] opacity-75 hover:opacity-100 hover:text-3xl duration-300 ease-in-out"
                        to="/">Home
            </RouterLink>
            <RouterLink class="text-2xl mx-4 text-[#810D27] opacity-75 hover:opacity-100 hover:text-3xl duration-300 ease-in-out"
                        to="/profile">Profile
            </RouterLink>
            <RouterLink class="text-2xl mx-4 text-[#810D27] opacity-75 hover:opacity-100 hover:text-3xl duration-300 ease-in-out" to="/powers">Powers
            </RouterLink>
          </div>

        </nav>
      </div>
    </header>
    <RouterView />
  </body>

</template>

<script>
import './assets/tailwind.css'
import './styles/global.css'

</script>

