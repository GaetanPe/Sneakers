<template>
    <body id="page-top">
        <!-- Navigation-->
        <nav class="navbar navbar-expand-lg navbar-info fixed-top bg-light" id="mainNav">
            <div class="container">
                <a class="navbar-brand" href="#page-top"
                    ><img src="../assets/img/nav-barLogo.png" alt="..." style="height:100px"
                /></a>
                <button
                    class="navbar-toggler"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#navbarResponsive"
                    aria-controls="navbarResponsive"
                    aria-expanded="false"
                    aria-label="Toggle navigation"
                >
                    Menu
                    <i class="fas fa-bars ms-1"></i>
                </button>
                <div class="collapse navbar-collapse" id="navbarResponsive">
                    <ul class="navbar-nav text-uppercase ms-auto py-4 py-lg-0">
                        <li class="nav-item">
                            <a class="nav-link" href="#services">Services</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#portfolio">Portfolio</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#about">About</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#team">Team</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#contact">Contact</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
        <!-- Masthead-->
        <header class="masthead">
            <div class="container">
                <div class="masthead-subheading">Welcome To Our Studio!</div>
                <div class="masthead-heading text-uppercase">
                    It's Nice To Meet You
                </div>
                <a
                    class="btn btn-primary btn-xl text-uppercase"
                    href="#services"
                    >Tell Me More</a
                >
            </div>
        </header>
        <!-- Services-->
        <section class="page-section" id="services">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">Services</h2>
                    <h3 class="section-subheading text-muted">
                        Lorem ipsum dolor sit amet consectetur.
                    </h3>
                </div>
                <div class="row text-center">
                    <div class="col-md-4">
                        <span class="fa-stack fa-4x">
                            <i
                                class="fas fa-circle fa-stack-2x text-primary"
                            ></i>
                            <i
                                class="fas fa-shopping-cart fa-stack-1x fa-inverse"
                            ></i>
                        </span>
                        <h4 class="my-3">E-Commerce</h4>
                        <p class="text-muted">
                            Lorem ipsum dolor sit amet, consectetur adipisicing
                            elit. Minima maxime quam architecto quo inventore
                            harum ex magni, dicta impedit.
                        </p>
                    </div>
                    <div class="col-md-4">
                        <span class="fa-stack fa-4x">
                            <i
                                class="fas fa-circle fa-stack-2x text-primary"
                            ></i>
                            <i class="fas fa-laptop fa-stack-1x fa-inverse"></i>
                        </span>
                        <h4 class="my-3">Responsive Design</h4>
                        <p class="text-muted">
                            Lorem ipsum dolor sit amet, consectetur adipisicing
                            elit. Minima maxime quam architecto quo inventore
                            harum ex magni, dicta impedit.
                        </p>
                    </div>
                    <div class="col-md-4">
                        <span class="fa-stack fa-4x">
                            <i
                                class="fas fa-circle fa-stack-2x text-primary"
                            ></i>
                            <i class="fas fa-lock fa-stack-1x fa-inverse"></i>
                        </span>
                        <h4 class="my-3">Web Security</h4>
                        <p class="text-muted">
                            Lorem ipsum dolor sit amet, consectetur adipisicing
                            elit. Minima maxime quam architecto quo inventore
                            harum ex magni, dicta impedit.
                        </p>
                    </div>
                </div>
            </div>
        </section>
        <!-- Portfolio Grid-->
        <section class="page-section bg-light" id="portfolio">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">Portfolio</h2>
                    <h3 class="section-subheading text-muted">
                        Lorem ipsum dolor sit amet consectetur.
                    </h3>
                </div>
                <div class="row">
                    <div class="col-lg-4 col-sm-6 mb-4">
                        <!-- Portfolio item 1-->
                        <div class="portfolio-item">
                            <a
                                class="portfolio-link"
                                data-bs-toggle="modal"
                                href="#portfolioModal1"
                            >
                                <div class="portfolio-hover">
                                    <div class="portfolio-hover-content">
                                        <i class="fas fa-plus fa-3x"></i>
                                    </div>
                                </div>
                                <img
                                    class="img-fluid"
                                    src="../assets/img/portfolio/1.jpg"
                                    alt="..."
                                />
                            </a>
                            <div class="portfolio-caption">
                                <div class="portfolio-caption-heading">
                                    Threads
                                </div>
                                <div
                                    class="portfolio-caption-subheading text-muted"
                                >
                                    Illustration
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-sm-6 mb-4">
                        <!-- Portfolio item 2-->
                        <div class="portfolio-item">
                            <a
                                class="portfolio-link"
                                data-bs-toggle="modal"
                                href="#portfolioModal2"
                            >
                                <div class="portfolio-hover">
                                    <div class="portfolio-hover-content">
                                        <i class="fas fa-plus fa-3x"></i>
                                    </div>
                                </div>
                                <img
                                    class="img-fluid"
                                    src="../assets/img/portfolio/2.jpg"
                                    alt="..."
                                />
                            </a>
                            <div class="portfolio-caption">
                                <div class="portfolio-caption-heading">
                                    Explore
                                </div>
                                <div
                                    class="portfolio-caption-subheading text-muted"
                                >
                                    Graphic Design
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-sm-6 mb-4">
                        <!-- Portfolio item 3-->
                        <div class="portfolio-item">
                            <a
                                class="portfolio-link"
                                data-bs-toggle="modal"
                                href="#portfolioModal3"
                            >
                                <div class="portfolio-hover">
                                    <div class="portfolio-hover-content">
                                        <i class="fas fa-plus fa-3x"></i>
                                    </div>
                                </div>
                                <img
                                    class="img-fluid"
                                    src="../assets/img/portfolio/3.jpg"
                                    alt="..."
                                />
                            </a>
                            <div class="portfolio-caption">
                                <div class="portfolio-caption-heading">
                                    Finish
                                </div>
                                <div
                                    class="portfolio-caption-subheading text-muted"
                                >
                                    Identity
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-sm-6 mb-4 mb-lg-0">
                        <!-- Portfolio item 4-->
                        <div class="portfolio-item">
                            <a
                                class="portfolio-link"
                                data-bs-toggle="modal"
                                href="#portfolioModal4"
                            >
                                <div class="portfolio-hover">
                                    <div class="portfolio-hover-content">
                                        <i class="fas fa-plus fa-3x"></i>
                                    </div>
                                </div>
                                <img
                                    class="img-fluid"
                                    src="../assets/img/portfolio/4.jpg"
                                    alt="..."
                                />
                            </a>
                            <div class="portfolio-caption">
                                <div class="portfolio-caption-heading">
                                    Lines
                                </div>
                                <div
                                    class="portfolio-caption-subheading text-muted"
                                >
                                    Branding
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-sm-6 mb-4 mb-sm-0">
                        <!-- Portfolio item 5-->
                        <div class="portfolio-item">
                            <a
                                class="portfolio-link"
                                data-bs-toggle="modal"
                                href="#portfolioModal5"
                            >
                                <div class="portfolio-hover">
                                    <div class="portfolio-hover-content">
                                        <i class="fas fa-plus fa-3x"></i>
                                    </div>
                                </div>
                                <img
                                    class="img-fluid"
                                    src="../assets/img/portfolio/5.jpg"
                                    alt="..."
                                />
                            </a>
                            <div class="portfolio-caption">
                                <div class="portfolio-caption-heading">
                                    Southwest
                                </div>
                                <div
                                    class="portfolio-caption-subheading text-muted"
                                >
                                    Website Design
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-lg-4 col-sm-6">
                        <!-- Portfolio item 6-->
                        <div class="portfolio-item">
                            <a
                                class="portfolio-link"
                                data-bs-toggle="modal"
                                href="#portfolioModal6"
                            >
                                <div class="portfolio-hover">
                                    <div class="portfolio-hover-content">
                                        <i class="fas fa-plus fa-3x"></i>
                                    </div>
                                </div>
                                <img
                                    class="img-fluid"
                                    src="../assets/img/portfolio/6.jpg"
                                    alt="..."
                                />
                            </a>
                            <div class="portfolio-caption">
                                <div class="portfolio-caption-heading">
                                    Window
                                </div>
                                <div
                                    class="portfolio-caption-subheading text-muted"
                                >
                                    Photography
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- About-->
        <section class="page-section" id="about">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">About</h2>
                    <h3 class="section-subheading text-muted">
                        Mise en place de la plateforme SneakersAddict
                    </h3>
                </div>
                <ul class="timeline">
                    <li>
                        <div class="timeline-image">
                            <img
                                class="rounded-circle img-fluid"
                                src="../assets/img/about/1.jpg"
                                alt="..."
                            />
                        </div>
                        <div class="timeline-panel">
                            <div class="timeline-heading">
                                <h4>2019-2020</h4>
                                <h4 class="subheading">
                                   Nos débuts laborieux
                                </h4>
                            </div>
                            <div class="timeline-body">
                                <p class="text-muted">
                                    Après plusieurs mois, acharnée de travail pour concrétiser notre projet nous avons essuyé de nombreuses échecs.
                                    Mais comme on le dit souvent le plus important c'est pas la chute c'est l'attérissage, ainsi nous sommes revus plus déterminés que
                                    jamais après chaque obstable sur notre route afin de vous offrir le meilleur en terme de sneakers.
                                </p>
                            </div>
                        </div>
                    </li>
                    <li class="timeline-inverted">
                        <div class="timeline-image">
                            <img
                                class="rounded-circle img-fluid"
                                src="../assets/img/about/2.jpg"
                                alt="..."
                            />
                        </div>
                        <div class="timeline-panel">
                            <div class="timeline-heading">
                                <h4>Janvier 2021</h4>
                                <h4 class="subheading">Création de la première boutique</h4>
                            </div>
                            <div class="timeline-body">
                                <p class="text-muted">
                                    Suite un succès exponnetielle de notre plateforme se classsant dans les plus sites et applications les plus visités sur
                                    l'année de 2021. Nous avons voulu voir grand très grand en revoyant nos objectifs avec plus d'ambition.
                                    Malgrès les difficultés sanitaires actuels qui aurait pu nous contraindre à le faire. <br>
                                    Nous avons ouvert <span class="text-uppercase text-dark">notre première boutique sur Paris</span>
                                </p>
                            </div>
                        </div>
                    </li>
                    <li>
                        <div class="timeline-image">
                            <img
                                class="rounded-circle img-fluid"
                                src="../assets/img/about/3.jpg"
                                alt="..."
                            />
                        </div>
                        <div class="timeline-panel">
                            <div class="timeline-heading">
                                <h4>Juillet 2021</h4>
                                <h4 class="subheading">
                                    Transition vers une enseigne
                                </h4>
                            </div>
                            <div class="timeline-body">
                                <p class="text-muted">
                                    Encore une fois, notre succès a été rétinticent notre présence devenaient presque vitale.
                                    Pour commecencer, nous avons conquis le coeur des fans franciliens en ouvrant une dizaine de boutique.
                                    Puis dans toutes la France métropolitaine.
                                </p>
                            </div>
                        </div>
                    </li>
                    <li class="timeline-inverted">
                        <div class="timeline-image">
                            <img
                                class="rounded-circle img-fluid"
                                src="../assets/img/about/4.jpg"
                                alt="..."
                            />
                        </div>
                        <div class="timeline-panel">
                            <div class="timeline-heading">
                                <h4>Janvier 2022</h4>
                                <h4 class="subheading">Transition vers une enseigne mondiale</h4>
                            </div>
                            <div class="timeline-body">
                                <p class="text-muted">
                                    SneakersAddict va au courant de l'année s'ouvrir au marché mondiale en touchant un public toujours aussi passionné avec une bonne
                                    paire au pied 😁.
                                    SneakersAddict sera bientot une réference aux quatres coins du monde pour les personnes qui desire 
                                    apprendre et comprendre cette univers si merveilleux.
                                </p>
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </section>
        <!-- Team-->
        <section class="page-section bg-light" id="team">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">
                        Notre equipe fondatrice
                    </h2>
                    <h3 class="section-subheading text-muted">
                        Voici les trois premières personnes à avoir travailler sur SneakersAddict.
                    </h3>
                </div>
                <div class="row">
                    <div class="col-lg-4">
                        <div class="team-member">
                            <img
                                class="mx-auto rounded-circle"
                                src="../assets/img/team/1.jpg"
                                alt="..."
                            />
                            <h4>Parveen Anand</h4>
                            <p class="text-muted">Lead Designer</p>
                            <a class="btn btn-dark btn-social mx-2" href="https://twitter.com/RebeuDeter" target="_blank"
                                ><i class="fab fa-twitter"></i
                            ></a>
                            <a class="btn btn-dark btn-social mx-2" href="#!"
                                ><i class="fab fa-facebook-f"></i
                            ></a>
                            <a class="btn btn-dark btn-social mx-2" href="#!"
                                ><i class="fab fa-linkedin-in"></i
                            ></a>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="team-member">
                            <img
                                class="mx-auto rounded-circle"
                                src="../assets/img/team/2.jpg"
                                alt="..."
                            />
                            <h4>Diana Petersen</h4>
                            <p class="text-muted">Lead Marketer</p>
                            <a class="btn btn-dark btn-social mx-2" href="#!"
                                ><i class="fab fa-twitter"></i
                            ></a>
                            <a class="btn btn-dark btn-social mx-2" href="#!"
                                ><i class="fab fa-facebook-f"></i
                            ></a>
                            <a class="btn btn-dark btn-social mx-2" href="#!"
                                ><i class="fab fa-linkedin-in"></i
                            ></a>
                        </div>
                    </div>
                    <div class="col-lg-4">
                        <div class="team-member">
                            <img
                                class="mx-auto rounded-circle"
                                src="../assets/img/team/3.jpg"
                                alt="..."
                            />
                            <h4>Larry Parker</h4>
                            <p class="text-muted">Lead Developer</p>
                            <a class="btn btn-dark btn-social mx-2" href="#!"
                                ><i class="fab fa-twitter"></i
                            ></a>
                            <a class="btn btn-dark btn-social mx-2" href="#!"
                                ><i class="fab fa-facebook-f"></i
                            ></a>
                            <a class="btn btn-dark btn-social mx-2" href="#!"
                                ><i class="fab fa-linkedin-in"></i
                            ></a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <!-- Clients-->
        <div class="py-5">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-md-3 col-sm-6 my-3">
                        <a href="#!"
                            ><img
                                class="img-fluid img-brand d-block mx-auto"
                                src="../assets/img/logos/microsoft.svg"
                                alt="..."
                        /></a>
                    </div>
                    <div class="col-md-3 col-sm-6 my-3">
                        <a href="#!"
                            ><img
                                class="img-fluid img-brand d-block mx-auto"
                                src="../assets/img/logos/google.svg"
                                alt="..."
                        /></a>
                    </div>
                    <div class="col-md-3 col-sm-6 my-3">
                        <a href="#!"
                            ><img
                                class="img-fluid img-brand d-block mx-auto"
                                src="../assets/img/logos/facebook.svg"
                                alt="..."
                        /></a>
                    </div>
                    <div class="col-md-3 col-sm-6 my-3">
                        <a href="#!"
                            ><img
                                class="img-fluid img-brand d-block mx-auto"
                                src="../assets/img/logos/ibm.svg"
                                alt="..."
                        /></a>
                    </div>
                </div>
            </div>
        </div>
        <!-- Contact-->
        <section class="page-section" id="contact">
            <div class="container">
                <div class="text-center">
                    <h2 class="section-heading text-uppercase">Contactez Nous</h2>
                    <h3 class="section-subheading text-muted">
                        Lorem ipsum dolor sit amet consectetur.
                    </h3>
                </div>
                <!-- * * * * * * * * * * * * * * *-->
                <!-- * * SB Forms Contact Form * *-->
                <!-- * * * * * * * * * * * * * * *-->
                <!-- This form is pre-integrated with SB Forms.-->
                <!-- To make this form functional, sign up at-->
                <!-- https://startbootstrap.com/solution/contact-forms-->
                <!-- to get an API token!-->
                <form id="contactForm" data-sb-form-api-token="API_TOKEN">
                    <div class="row align-items-stretch mb-5">
                        <div class="col-md-6">
                            <div class="form-group">
                                <!-- Name input-->
                                <input
                                    class="form-control"
                                    id="name"
                                    type="text"
                                    placeholder="Votre nom *"
                                    data-sb-validations="required"
                                />
                                <div
                                    class="invalid-feedback"
                                    data-sb-feedback="name:required"
                                >
                                    A name is required.
                                </div>
                            </div>
                            <div class="form-group">
                                <!-- Email address input-->
                                <input
                                    class="form-control"
                                    id="email"
                                    type="email"
                                    placeholder="Votre Email *"
                                    data-sb-validations="required,email"
                                />
                                <div
                                    class="invalid-feedback"
                                    data-sb-feedback="email:required"
                                >
                                    An email is required.
                                </div>
                                <div
                                    class="invalid-feedback"
                                    data-sb-feedback="email:email"
                                >
                                    Email is not valid.
                                </div>
                            </div>
                            <div class="form-group mb-md-0">
                                <!-- Phone number input-->
                                <input
                                    class="form-control"
                                    id="phone"
                                    type="tel"
                                    placeholder="Votre telephone *"
                                    data-sb-validations="required"
                                />
                                <div
                                    class="invalid-feedback"
                                    data-sb-feedback="phone:required"
                                >
                                    A phone number is required.
                                </div>
                            </div>
                        </div>
                        <div class="col-md-6">
                            <div class="form-group form-group-textarea mb-md-0">
                                <!-- Message input-->
                                <textarea
                                    class="form-control"
                                    id="message"
                                    placeholder="Votre Message *"
                                    data-sb-validations="required"
                                ></textarea>
                                <div
                                    class="invalid-feedback"
                                    data-sb-feedback="message:required"
                                >
                                    A message is required.
                                </div>
                            </div>
                        </div>
                    </div>
                    <!-- Submit success message-->
                    <!---->
                    <!-- This is what your users will see when the form-->
                    <!-- has successfully submitted-->
                    <div class="d-none" id="submitSuccessMessage">
                        <div class="text-center text-white mb-3">
                            <div class="fw-bolder">
                                Form submission successful!
                            </div>
                            To activate this form, sign up at
                            <br />
                            <a
                                href="https://startbootstrap.com/solution/contact-forms"
                                >https://startbootstrap.com/solution/contact-forms</a
                            >
                        </div>
                    </div>
                    <!-- Submit error message-->
                    <!---->
                    <!-- This is what your users will see when there is-->
                    <!-- an error submitting the form-->
                    <div class="d-none" id="submitErrorMessage">
                        <div class="text-center text-danger mb-3">
                            Error sending message!
                        </div>
                    </div>
                    <!-- Submit Button-->
                    <div class="text-center">
                        <button
                            class="btn btn-primary btn-xl text-uppercase disabled"
                            id="submitButton"
                            type="submit"
                        >
                            Envoyer
                        </button>
                    </div>
                </form>
            </div>
        </section>
        <!-- Footer-->
        <footer class="footer py-4">
            <div class="container">
                <div class="row align-items-center">
                    <div class="col-lg-4 text-lg-start">
                        Copyright &copy; SneakersAddict.com 2022
                    </div>
                    <div class="col-lg-4 my-3 my-lg-0">
                        <a class="btn btn-dark btn-social mx-2" href="#!"
                            ><i class="fab fa-twitter"></i
                        ></a>
                        <a class="btn btn-dark btn-social mx-2" href="#!"
                            ><i class="fab fa-facebook-f"></i
                        ></a>
                        <a class="btn btn-dark btn-social mx-2" href="#!"
                            ><i class="fab fa-linkedin-in"></i
                        ></a>
                    </div>
                    <div class="col-lg-4 text-lg-end">
                        <a class="link-dark text-decoration-none me-3" href="#!"
                            >Privacy Policy</a
                        >
                        <a class="link-dark text-decoration-none" href="#!"
                            >Terms of Use</a
                        >
                    </div>
                </div>
            </div>
        </footer>
        <!-- Portfolio Modals-->
        <!-- Portfolio item 1 modal popup-->
        <div
            class="portfolio-modal modal fade"
            id="portfolioModal1"
            tabindex="-1"
            role="dialog"
            aria-hidden="true"
        >
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="close-modal" data-bs-dismiss="modal">
                        <img
                            src="../assets/img/close-icon.svg"
                            alt="Close modal"
                        />
                    </div>
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <div class="modal-body">
                                    <!-- Project details-->
                                    <h2 class="text-uppercase">Project Name</h2>
                                    <p class="item-intro text-muted">
                                        Lorem ipsum dolor sit amet consectetur.
                                    </p>
                                    <img
                                        class="img-fluid d-block mx-auto"
                                        src="../assets/img/portfolio/1.jpg"
                                        alt="..."
                                    />
                                    <p>
                                        Use this area to describe your project.
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipisicing elit. Est blanditiis dolorem
                                        culpa incidunt minus dignissimos
                                        deserunt repellat aperiam quasi sunt
                                        officia expedita beatae cupiditate,
                                        maiores repudiandae, nostrum, reiciendis
                                        facere nemo!
                                    </p>
                                    <ul class="list-inline">
                                        <li>
                                            <strong>Client:</strong>
                                            Threads
                                        </li>
                                        <li>
                                            <strong>Category:</strong>
                                            Illustration
                                        </li>
                                    </ul>
                                    <button
                                        class="btn btn-primary btn-xl text-uppercase"
                                        data-bs-dismiss="modal"
                                        type="button"
                                    >
                                        <i class="fas fa-times me-1"></i>
                                        Close Project
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Portfolio item 2 modal popup-->
        <div
            class="portfolio-modal modal fade"
            id="portfolioModal2"
            tabindex="-1"
            role="dialog"
            aria-hidden="true"
        >
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="close-modal" data-bs-dismiss="modal">
                        <img
                            src="../assets/img/close-icon.svg"
                            alt="Close modal"
                        />
                    </div>
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <div class="modal-body">
                                    <!-- Project details-->
                                    <h2 class="text-uppercase">Project Name</h2>
                                    <p class="item-intro text-muted">
                                        Lorem ipsum dolor sit amet consectetur.
                                    </p>
                                    <img
                                        class="img-fluid d-block mx-auto"
                                        src="../assets/img/portfolio/2.jpg"
                                        alt="..."
                                    />
                                    <p>
                                        Use this area to describe your project.
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipisicing elit. Est blanditiis dolorem
                                        culpa incidunt minus dignissimos
                                        deserunt repellat aperiam quasi sunt
                                        officia expedita beatae cupiditate,
                                        maiores repudiandae, nostrum, reiciendis
                                        facere nemo!
                                    </p>
                                    <ul class="list-inline">
                                        <li>
                                            <strong>Client:</strong>
                                            Explore
                                        </li>
                                        <li>
                                            <strong>Category:</strong>
                                            Graphic Design
                                        </li>
                                    </ul>
                                    <button
                                        class="btn btn-primary btn-xl text-uppercase"
                                        data-bs-dismiss="modal"
                                        type="button"
                                    >
                                        <i class="fas fa-times me-1"></i>
                                        Close Project
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Portfolio item 3 modal popup-->
        <div
            class="portfolio-modal modal fade"
            id="portfolioModal3"
            tabindex="-1"
            role="dialog"
            aria-hidden="true"
        >
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="close-modal" data-bs-dismiss="modal">
                        <img
                            src="../assets/img/close-icon.svg"
                            alt="Close modal"
                        />
                    </div>
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <div class="modal-body">
                                    <!-- Project details-->
                                    <h2 class="text-uppercase">Project Name</h2>
                                    <p class="item-intro text-muted">
                                        Lorem ipsum dolor sit amet consectetur.
                                    </p>
                                    <img
                                        class="img-fluid d-block mx-auto"
                                        src="../assets/img/portfolio/3.jpg"
                                        alt="..."
                                    />
                                    <p>
                                        Use this area to describe your project.
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipisicing elit. Est blanditiis dolorem
                                        culpa incidunt minus dignissimos
                                        deserunt repellat aperiam quasi sunt
                                        officia expedita beatae cupiditate,
                                        maiores repudiandae, nostrum, reiciendis
                                        facere nemo!
                                    </p>
                                    <ul class="list-inline">
                                        <li>
                                            <strong>Client:</strong>
                                            Finish
                                        </li>
                                        <li>
                                            <strong>Category:</strong>
                                            Identity
                                        </li>
                                    </ul>
                                    <button
                                        class="btn btn-primary btn-xl text-uppercase"
                                        data-bs-dismiss="modal"
                                        type="button"
                                    >
                                        <i class="fas fa-times me-1"></i>
                                        Close Project
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Portfolio item 4 modal popup-->
        <div
            class="portfolio-modal modal fade"
            id="portfolioModal4"
            tabindex="-1"
            role="dialog"
            aria-hidden="true"
        >
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="close-modal" data-bs-dismiss="modal">
                        <img
                            src="../assets/img/close-icon.svg"
                            alt="Close modal"
                        />
                    </div>
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <div class="modal-body">
                                    <!-- Project details-->
                                    <h2 class="text-uppercase">Project Name</h2>
                                    <p class="item-intro text-muted">
                                        Lorem ipsum dolor sit amet consectetur.
                                    </p>
                                    <img
                                        class="img-fluid d-block mx-auto"
                                        src="../assets/img/portfolio/4.jpg"
                                        alt="..."
                                    />
                                    <p>
                                        Use this area to describe your project.
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipisicing elit. Est blanditiis dolorem
                                        culpa incidunt minus dignissimos
                                        deserunt repellat aperiam quasi sunt
                                        officia expedita beatae cupiditate,
                                        maiores repudiandae, nostrum, reiciendis
                                        facere nemo!
                                    </p>
                                    <ul class="list-inline">
                                        <li>
                                            <strong>Client:</strong>
                                            Lines
                                        </li>
                                        <li>
                                            <strong>Category:</strong>
                                            Branding
                                        </li>
                                    </ul>
                                    <button
                                        class="btn btn-primary btn-xl text-uppercase"
                                        data-bs-dismiss="modal"
                                        type="button"
                                    >
                                        <i class="fas fa-times me-1"></i>
                                        Close Project
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Portfolio item 5 modal popup-->
        <div
            class="portfolio-modal modal fade"
            id="portfolioModal5"
            tabindex="-1"
            role="dialog"
            aria-hidden="true"
        >
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="close-modal" data-bs-dismiss="modal">
                        <img
                            src="../assets/img/close-icon.svg"
                            alt="Close modal"
                        />
                    </div>
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <div class="modal-body">
                                    <!-- Project details-->
                                    <h2 class="text-uppercase">Project Name</h2>
                                    <p class="item-intro text-muted">
                                        Lorem ipsum dolor sit amet consectetur.
                                    </p>
                                    <img
                                        class="img-fluid d-block mx-auto"
                                        src="../assets/img/portfolio/5.jpg"
                                        alt="..."
                                    />
                                    <p>
                                        Use this area to describe your project.
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipisicing elit. Est blanditiis dolorem
                                        culpa incidunt minus dignissimos
                                        deserunt repellat aperiam quasi sunt
                                        officia expedita beatae cupiditate,
                                        maiores repudiandae, nostrum, reiciendis
                                        facere nemo!
                                    </p>
                                    <ul class="list-inline">
                                        <li>
                                            <strong>Client:</strong>
                                            Southwest
                                        </li>
                                        <li>
                                            <strong>Category:</strong>
                                            Website Design
                                        </li>
                                    </ul>
                                    <button
                                        class="btn btn-primary btn-xl text-uppercase"
                                        data-bs-dismiss="modal"
                                        type="button"
                                    >
                                        <i class="fas fa-times me-1"></i>
                                        Close Project
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Portfolio item 6 modal popup-->
        <div
            class="portfolio-modal modal fade"
            id="portfolioModal6"
            tabindex="-1"
            role="dialog"
            aria-hidden="true"
        >
            <div class="modal-dialog">
                <div class="modal-content">
                    <div class="close-modal" data-bs-dismiss="modal">
                        <img
                            src="../assets/img/close-icon.svg"
                            alt="Close modal"
                        />
                    </div>
                    <div class="container">
                        <div class="row justify-content-center">
                            <div class="col-lg-8">
                                <div class="modal-body">
                                    <!-- Project details-->
                                    <h2 class="text-uppercase">Project Name</h2>
                                    <p class="item-intro text-muted">
                                        Lorem ipsum dolor sit amet consectetur.
                                    </p>
                                    <img
                                        class="img-fluid d-block mx-auto"
                                        src="../assets/img/portfolio/6.jpg"
                                        alt="..."
                                    />
                                    <p>
                                        Use this area to describe your project.
                                        Lorem ipsum dolor sit amet, consectetur
                                        adipisicing elit. Est blanditiis dolorem
                                        culpa incidunt minus dignissimos
                                        deserunt repellat aperiam quasi sunt
                                        officia expedita beatae cupiditate,
                                        maiores repudiandae, nostrum, reiciendis
                                        facere nemo!
                                    </p>
                                    <ul class="list-inline">
                                        <li>
                                            <strong>Client:</strong>
                                            Window
                                        </li>
                                        <li>
                                            <strong>Category:</strong>
                                            Photography
                                        </li>
                                    </ul>
                                    <button
                                        class="btn btn-primary btn-xl text-uppercase"
                                        data-bs-dismiss="modal"
                                        type="button"
                                    >
                                        <i class="fas fa-times me-1"></i>
                                        Close Project
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
       
    </body>
</template>

<script>
export default {
    name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
