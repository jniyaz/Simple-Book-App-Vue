<template>
  <div id="app" class="font-sans antialiased text-black">
    <div id="nav" class="bg-purple-dark">
      <div class="container flex items-center justify-between px-10 py-4">
        <div>
          <h3><a class="text-white" href="/">Books GraphQL</a></h3>
        </div>
        <div>
          <router-link to="/" class="text-white hover:text-grey-light">Home</router-link>
          <router-link to="/about" class="text-white hover:text-grey-light pl-6">About</router-link>
        </div>
      </div>
    </div>
    <router-view/>
  </div>
</template>

<style style="@/assets/main.css">
