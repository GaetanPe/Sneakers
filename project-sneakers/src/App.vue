<template>
    <div>
        <Navbar/>
        <router-view/>
    </div>
</template>
<script>
import Navbar from "./components/Navbar.vue"

export default {
    /* eslint-disable no-use-before-define */
    components:{
        Navbar,
    }
};
</script>

<style>
#app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
}

#nav {
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 2;
    background-color: #ffff;
}

#nav a {
    font-weight: bold;
    color: #ffff;
    text-decoration: none;
    font-size: 30px;
    margin-right: 30px;
}

#nav a.router-link-exact-active {
    color: rgb(233, 20, 20);
    text-decoration: none;
    margin-right: 40px;
    font-size: 30px;
}

</style>
