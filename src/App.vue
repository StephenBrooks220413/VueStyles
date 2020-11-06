<template>
    <div id="app">
        
        <Nav/>
        <Home/>
        <Price/>
        <Contact/>
        <br><br>
        <Footer/>


    </div>
</template>

<script>
    import Home from './components/Home.vue';
    import Nav from './components/Nav.vue';
    import Price from './components/Price.vue';
    import Contact from './components/Contact.vue';
    import Footer from './components/Footer.vue';

    export default {
        name: 'app',
        components: {
            Home,
            Nav,
            Price,
            Contact,
            Footer
        }
    };
</script>

<style>
@import 'assets/bootstrap.min.css';
</style>

