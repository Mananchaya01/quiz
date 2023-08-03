<template>
    <div>
        <header class="shadow-sm bg-white">
            <nav class="container mx-auto p-4 flex justify-between">
                <NuxtLink to="/" class="font-bold">PowerPuff Girl</NuxtLink>
                <ul class="flex gap-4">
                    <li><NuxtLink to="/">Home</NuxtLink></li>
                    <li><NuxtLink to="/blossom" class="btn">Blossom</NuxtLink></li>
                    <li><NuxtLink to="/bubbles" class="btn">Bubbles</NuxtLink></li>
                    <li><NuxtLink to="/buttercup" class="btn">Buttercup</NuxtLink></li>
                    <li><NuxtLink to="/doctor" class="btn">Doctor</NuxtLink></li>
                </ul>
            </nav>
        </header>
  
        <!-- page content go here -->
        <div class="container mx-auto p-4">
            <slot />
        </div>
    </div>
</template>
  
<style scoped>
    .router-link-exact-active {
        color: #12b488;
    }
</style>