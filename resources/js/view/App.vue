<template>
    <div>

        <nav>
            <div class="nav-wrapper">
                <a href="#" class="brand-logo">SPA - laravel com Vue JS</a>
                <ul id="nav-mobile" class="right hide-on-med-and-down">
                    <li><router-link :to="{ name: 'home' }">Home</router-link></li>
                    <li><router-link :to="{ name: 'hello' }">Hello</router-link></li>
                    <li><router-link :to="{ name: 'example' }">Example</router-link></li>
                </ul>
            </div>
        </nav>

        <div class="container">
            <div class="card"></div>
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
export default {



}
</script>
