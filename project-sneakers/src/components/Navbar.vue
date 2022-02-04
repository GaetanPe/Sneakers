<template>
    <div class="container-fluid navbar navbar-expand-lg navbar-light bg-dark" id="nav">
        <div class="row" id="rownav">
            <div class="col-2">
                <img

                    src="../assets/img/nav-barLogo.png"
                    alt=""
                    style="height: 100px"
                />
            </div>
            <div class="col-4 my-auto">
                <div
                    class="collapse navbar-collapse"
                    id="navbarSupportedContent"
                >
                    <ul class="navbar-nav mr-auto">
                        <li class="nav-item active">
                            <router-link to="/">Home</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/apropos">A Propos</router-link>
                        </li>
                        <li class="nav-item">
                            <router-link to="/store">Store</router-link>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="col-4 my-auto">
                <div class="container">                                          
            <div class="dropdown">
                <button type="button" class="btn btn-primary dropdown-toggle" data-toggle="dropdown">
                 Cart
                </button>
                <div class="dropdown-menu">
                <div class="card rounded-3 mb-2">
                        <div class="card-body">
                        </div>
                    </div>
                    <div class="card">
                    <div class="card-body">
                        <button type="button" class="btn btn-warning btn-block btn-lg">Payer</button>
                    </div>
                    </div>
                </div>
            </div>
        </div>
        </div>
    </div>
    </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="css">
#rownav {
    width: 100%;
    display: flex;
    justify-content: space-between;
}
</style>

