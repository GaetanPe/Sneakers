<template>
    <body id="page-top">        
        <!-- Masthead-->
        <header class="masthead">
            <div class="jumbotron jumbotron-fluid">
                <div class="container">
                    <div class="row">
                        <div class="col-12">
                            <h1 class="display-1 text-uppercase ">Sneakers Addict </h1>
                        </div>
                        <div class="col-12 ">
                            <p class="lead font-italic" style="font-size:35px">La sneaker qu'il vous faut...</p>
                        </div>
                    </div>
                </div>
            </div>
        </header>
        <!-- Search form -->
            <div class="container">
                <div class="row">
                    <div class="col">
                        <form class="form-inline">
                            <div class="container-fluid">
                                <div class="row">
                                    <div class="col-11 ">
                                        <input class="form-control w-100" type="text" placeholder="Recherche">
                                    </div>
                                    <div class="col-1">
                                        <button class="btn btn-primary btn-rounded w-100" type="submit">Envoyer</button>
                                    </div>
                                </div>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        <!-- Services-->
        <section class="page-section" id="services">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">Services</h2>
                    <h3 class="section-subheading text-muted">
                        Votre confort ? Notre priorité !
                    </h3>
                </div>
                <div class="row text-center">
                    <div class="col-md-4">
                        <span class="fa-stack fa-4x">
                            <i
                                class="fas fa-circle fa-stack-2x text-primary"
                            ></i>
                            <i
                                class="
                                    fas
                                    fa-shopping-cart fa-stack-1x fa-inverse
                                "
                            ></i>
                        </span>
                        <h4 class="my-3">Livraison Rapide</h4>
                        <p class="text-muted">
                            Notre transporteur vous assure une livre rapide et sécurisé, 
                            dans les plus brefs délais.
                        </p>
                    </div>
                    <div class="col-md-4">
                        <span class="fa-stack fa-4x">
                            <i
                                class="fas fa-circle fa-stack-2x text-primary"
                            ></i>
                            <i class="fas fa-laptop fa-stack-1x fa-inverse"></i>
                        </span>
                        <h4 class="my-3">Achat en Ligne</h4>
                        <p class="text-muted">
                            La totalité des modèles sont disponibles sur notre site
                            dans les différentes tailles.
                        </p>
                    </div>
                    <div class="col-md-4">
                        <span class="fa-stack fa-4x">
                            <i
                                class="fas fa-circle fa-stack-2x text-primary"
                            ></i>
                            <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
                        </span>
                        <h4 class="my-3">Paiement Sécurisé</h4>
                        <p class="text-muted">
                            Notre plateforme de paiement est totalement sécurisée.
                        </p>
                    </div>
                </div>
            </div>
        </section>
    </body>
</template>
<script>
export default {
    name: "Mainpage",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
#page-top {
    margin-top: 160px;
}
</style>
