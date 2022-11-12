<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
</script>

<template>
    <div class=" w-3/4 mx-auto mt-10  shadow-lg h-screen">
        <header class="p-4 flex justify-betweem orange-pink h-40 rounded">
            <div class="flex space-y-4 items-center">
                <img src="/logocdg.png" alt="" class="w-24 mr-4">
                <h1 class="text-white text-2xl md:text-4xl">Welcome to the gentlemen's club</h1>
            </div>
        </header>

        <div class="md:flex mt-10 md:space-x-10 text-white rounded p-4 white-opac orange-yellow">
            <div class="">
                <p class="max-sm:mb-10">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

            </div>
            <div class="">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

            </div>

        </div>
        <div class="md:flex mt-10 md:space-x-10 text-white rounded p-4 white-opac yellow-red">
            <div class="">
                <p class="max-sm:mb-10">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

            </div>
            <div class="">
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>

            </div>

        </div>
    </div>
</template>
<style media="screen">
body {
    background-color: rgba(0, 0,0, 0.90);
}
.white-opac {
        background-color: rgba(255, 255, 255, 0.45);
}
.orange-pink {
    background: linear-gradient(115deg, #d4145a, #e26c1d);
}
.orange-yellow {
    background: linear-gradient(115deg, #e26c1d, rgba(234, 168, 60, 0.99));
}
.yellow-red {
    background: linear-gradient(115deg, rgba(234, 168, 60, 0.99), #d4145a);
}

</style>
