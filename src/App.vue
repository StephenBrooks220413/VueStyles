<template>
    <div id="app">
        
        <Nav/>
        <Home/>
        <Price/>
        <footer/>


    </div>
</template>

<script>
    import Home from './components/Home.vue';
    import Nav from './components/Nav.vue';
    import Price from './components/Price.vue';
    import Footer from './components/Footer.vue';

    export default {
        name: 'app',
        components: {
            Home,
            Nav,
            Price,
            Footer
        }
    };
</script>

<style>
@import 'assets/bootstrap.min.css';
</style>

