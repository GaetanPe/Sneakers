<template>
    <div class="container-fluid navbar navbar-expand-lg navbar-light" id="nav">
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
                <!-- Section Panier -->
                <div class="dropdown">
                    <a
                        class="btn dropdown-toggle"
                        href="#"
                        role="button"
                        id="dropdownMenuLink"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        aria-expanded="false"
                    >
                        <i class="fas fa-shopping-cart"></i>
                    </a>

                    <div
                        class="dropdown-menu"
                        aria-labelledby="dropdownMenuLink"
                    >
                        <div id="section-product-details">
                            <!-- Section Panier -->
                            <div class="cart">
                            <table>
                                <thead>
                                <tr>
                                    <th colspan="2">Votre commande</th>
                                </tr>
                                </thead>
                                <tbody>
                                <tr>
                                    <td>Nombre de Pizza</td>
                                    <td>x {{ nbrProduct }}</td>
                                </tr>
                                <tr>
                                    <td>Code Promo</td>
                                    <td class="code-promo">
                                    <input v-model="promo" placeholder="Ajouter un code promo" />
                                    </td>
                                </tr>
                                <tr>
                                    <td>Total à payer</td>

                                    <td>
                                    <transition name="bounce">
                                        <div v-if="promo === 'royale'">
                                        (-5€)
                                        <span class="sale">{{ totalPrice }} €</span>
                                        {{ totalPrice - 5 }} €
                                        </div>
                                        <div v-else>{{ totalPrice }} €</div>
                                    </transition>
                                    </td>
                                </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    </div>
</template>

<script></script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="css">
#rownav {
    width: 100%;
    display: flex;
    justify-content: space-between;
}
</style>
