<template>
    <div
        class="container-fluid navbar navbar-expand-lg navbar-light bg-light"
        id="nav"
    >
        <div class="row">
            <div class="col-5 ">
                <img
                    src="./assets/img/nav-barLogo.png"
                    alt=""
                    style="height: 100px"
                />
            </div>
            <div class="col-4 my-auto p-2" style="margin-left:100px">
                <button
                    class="navbar-toggler"
                    type="button"
                    data-toggle="collapse"
                    data-target="#navbarSupportedContent"
                    aria-controls="navbarSupportedContent"
                    aria-expanded="false"
                    aria-label="Toggle navigation"
                >
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div
                    class="collapse navbar-collapse"
                    id="navbarSupportedContent"
                >
                    <ul class="navbar-nav mr-auto">
                        <li class="nav-item active">
                            <router-link to="/">Home</router-link>  
                        </li>
                        <li class="nav-item">
                            <router-link to="/about">About</router-link>  
                        </li>
                        <li class="nav-item">
                            <router-link to="/store">Store</router-link>  
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <router-view />
</template>
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
    padding: 30px;
    z-index: 3;
    margin-bottom: 300px;
}

#nav a {
    font-weight: bold;
    color: #2c3e50;
}

#nav a.router-link-exact-active {
    color:yellow;
}
li{
  text-decoration: none;
}
</style>
