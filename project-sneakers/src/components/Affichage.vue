<template>
    <section class="page-section" id="portfolio">
        <div class="container">
            <div class="text-center">
                <h2 class="section-heading text-uppercase">BestSeller</h2>
                <h3 class="section-subheading text-muted">
                    Nos meilleurs ventes ce mois-ci.
                </h3>
            </div>
            <div class="row">
                 <div class="col-lg-4 col-sm-6 " style="margin-bottom:100px" v-for="elements in sneakers" v-bind:key="elements.id" >
                    <!-- Portfolio item 1-->
                    <div class="flip-card">
                        <div class="flip-card-inner">
                            <div class="flip-card-front">
                                <img
                                    v-bind:src="elements.grid_picture_url" 
                                    v-bind:alt="elements.id"
                                    style="width: 100%; height: 100%"
                                />
                                <div class="superelement">
                                    {{elements.name}}
                                    <p>{{elements.retail_price_cents/100}}$</p>
                                   
                                </div>
                            </div>  
                            <div class="flip-card-back">
                                <h1 class="display-5 text-uppercase " >{{elements.silhouette}}</h1>
                                <div style="font-size:12px; font-style:italic; color:black">
                                <span class="correct">PRICE</span> : {{elements.retail_price_cents/100}}$ <br>
                                <span class="correct">Brand</span> : {{elements.brand_name}} <br>
                                <span class="correct">Color</span> : {{elements.color}} <br>
                                <span class="correct">Etat</span> : {{elements.shoe_condition}} <br>
                                <a v-if="elements.story_html"> <span class="correct">Story :</span> {{elements.story_html}}</a> <br>
                                <span class="correct">Designer</span> : {{elements.designer}} <br>
                                <a v-if="elements.has_stock"> in stock <img style="width: 7%" src="../assets/img/validation.png"></a>
                                <a v-else> not in stock <img style="width: 5%" src="../assets/img/Cross_red_circle.png"></a> 
                                <br>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="container" style="margin-top:80px;">
                        <div class="row">
                            <div class="col">
                                <button class="Mysuperbutton">Ajouter Au Panier</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            </div>
    </section>
</template>
 <script>
// /* eslint-disable no-use-before-define */
import sneakers from '../data/API.json'

export default{ 
data (){
    return sneakers
    }
}
</script>
<style>
body {
  font-family: Arial, Helvetica, sans-serif;
}

.flip-card {
  background-color: transparent;
  width: 300px;
  height: 300px;
  perspective: 1000px;
}

.flip-card-inner {
  position: relative;
  width: 100%;
  height: 100%;
  text-align: center;
  transition: transform 0.6s;
  transform-style: preserve-3d;
  box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
}

.flip-card:hover .flip-card-inner {
  transform: rotateY(180deg);
}

.flip-card-front, .flip-card-back {
  position: absolute;
  width: 100%;
  height: 100%;
  -webkit-backface-visibility: hidden;
  backface-visibility: hidden;
}

.flip-card-front {
  color: black;
}

.flip-card-back {
  background-color: #2980b9;
  color: white;
  transform: rotateY(180deg);
}
</style>
