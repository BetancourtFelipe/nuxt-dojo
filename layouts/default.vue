<template>
  <div>
    <header>
      <div>
        <NuxtLink to="/">Nuxt Dojo</NuxtLink>
        <ul>
          <li><NuxtLink to="/">Home</NuxtLink></li>
          <li><NuxtLink to="/about">About</NuxtLink></li>
          <li><NuxtLink to="/products">Products</NuxtLink></li>
        </ul>
      </div>
    </header>

    <!-- output the page content -->
    <div>
      <slot />
    </div>
  </div>
</template>

<style>
.router-link-exact-active {
  color: #12b488;
}
</style>
