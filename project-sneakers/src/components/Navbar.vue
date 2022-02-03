<template>
     <div
        class="container-fluid navbar navbar-expand-lg navbar-light "
        id="nav"
    >
        <div class="row " style="width:100%">
            <div class="col-2">
                <img
                    src="../assets/img/nav-barLogo.png"
                    alt=""
                    style="height: 100px"
                />
            </div>
            <div class="col-5 my-auto" style="margin-left: 300px">
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav mr-auto">
                        <li class="nav-item active">
                            <router-link to="/">Home</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/about">A Propos</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/store">Store</router-link>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="col-2 my-auto  " >
                <button class="btn  "><a href="#"><i class="fas fa-shopping-cart" style="height:90px"></i></a></button>
            </div>
        </div>
    </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="css">

</style>