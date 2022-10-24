<template>
  <section class="header">
    <div class="container-fluid navbar-menu ">
      <nav id="navbar" class="navbar navbar-expand-lg bg-light px-0 ">
        <div id="navbar" class="container-fluid center">
          <a href="#home" class="logo-img"><img id="logo" src="../public/img/Banner/logo.png" alt=""></a>
          <a class="navbar-brand px-1" href="#home">HOME</a>
          <div id="navbar-menu" class="navbar-menu" v-bind:class="{ 'is-active': showMobileMenu }">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0  ">
              <li class="nav-item">
                <a class="nav-link" href="#prizes">PRIZESSSSSS !!!! </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#gallery">Gallery </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#roadmap">ROADMAP</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#faq">FAQ</a>
              </li>
              <li class="nav-item ">
                <a href="https://twitter.com/LuckyApt" target="_blank" class="btn " id="twitter">
                  <i class="bi bi-twitter"></i>
                </a>
              </li>
              <li class="nav-item">
                <a href="https://discord.gg/H9QNPJy6wy" target="_blank" class="btn" id="twitter">
                  <i class="bi bi-discord"></i>
                </a>
              </li>
              <li class="nav-item">
                <a href="https://t.me/+BByUPXvBKeNiZDQx" target="_blank" class="btn" id="twitter">
                  <i class="bi bi-telegram"></i>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
    </div>
  </section>
  <div class="contenido">
    <section class="section">
      <div class="home">
        <hr id="home">
        <section class="cuerpo">
          <div class="container text-sm-start">
            <div class="row">
              <div class="col-lg-6">
                <div class="title">
                  <h1 class="title text-lg-start text-center">THE BIGGEST RAFFLE IN APTOS</h1>
                </div>
                <div class="text">
                  <h5 class="text-c text-lg-start text-center">Win 10k APT with 2 APT is possible</h5>
                  <p class="t-parraf text-lg-start text-center">10000 APT LUCKYS and incredible prizes for all
                    of them</p>
                  <p class="t-parraf text-lg-start text-center">Our project and, from now on, also your
                    project,
                    will be the biggest raffle in the network of aptos. Initially, we will do an incredible
                    raffle with a bunch of winners. Afterward, there will be weekly raffles in the apt token,
                    the blockchain network of the
                    future, as well as raffles of merchandising
                    .</p>
                </div>
                <div class="div-button">
                  <a id="btn-see" class="btn btn-success" href="https://campus.open-bootcamp.com/">See
                    more</a>
                </div>
              </div>
              <div class="col-lg-6 div-carousel">
                <div class="carousel-wrapper">
                  <div class="carousel-container">
                    <div class="carousel">
                      <div class="image-one"></div>
                      <div class="image-two"></div>
                      <div class="image-three"></div>
                      <div class="image-four"></div>
                      <div class="image-five"></div>
                      <div class="image-six"></div>
                      <div class="image-seven"></div>
                      <div class="image-eight"></div>
                      <div class="image-nine"></div>
                      <div class="image-ten"></div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section class="prizes" id="prizes">
          <div class="containerr">
            <h1 class="title text-center">PRIZESSSS !!!</h1>
          </div>
          <div class="containerr">
            <div class="row">
              <div class="col-12 col-md-6 col-lg-4">
                <div class="card">
                  <div class="face face1 ">
                    <div class="content">
                      <span class="stars"></span>
                      <h2 class="java">50% OF POOL PRIZES</h2>
                      <p class="java">A lucky holder of an APT LUCKY TOAST CLUB NFT WILL EARN 40% OF THE
                        OBTAINED ON MINT DAY (10000 APT)</p>
                    </div>
                  </div>
                  <div class="face face2">
                    <h2 id="k">10K APTOS</h2>
                  </div>
                </div>
              </div>
              <div class="col-12 col-md-6 col-lg-4">
                <div class="card">
                  <div class="face face1">
                    <div class="content">
                      <span class="stars"></span>
                      <h2 class="java">20% OF POOL PRIZES</h2>
                      <p class="java">A lucky holder of an APT LUCKY TOAST CLUB NFT WILL EARN 40% OF THE
                        OBTAINED ON MINT DAY (4000 APT)</p>
                    </div>
                  </div>
                  <div class="face face2">
                    <h2>4K APTOS</h2>
                  </div>
                </div>
              </div>
              <div class="col-12  col-lg-4">
                <div class="card">
                  <div class="face face1">
                    <div class="content">
                      <span class="stars"></span>
                      <h2 class="java">15% OF POOL PRIZES</h2>
                      <p class="java">A lucky holder of an APT LUCKY TOAST CLUB NFT WILL EARN 40% OF THE
                        OBTAINED ON MINT DAY  (3000 APT)</p>
                    </div>
                  </div>
                  <div class="face face2">
                    <h2>3K APTOS</h2>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="containerr">
            <div class="row">
              <div class="col-12 col-md-6 ">
                <div class="card">
                  <div class="face face1">
                    <div class="content">
                      <span class="stars"></span>
                      <h2 class="java">5% OF POOL PRIZES</h2>
                      <p class="java">A lucky holder of an APT LUCKY TOAST CLUB NFT WILL EARN 40% OF THE
                        OBTAINED ON MINT DAY  (1000 APT)</p>
                    </div>
                  </div>
                  <div class="face face2">
                    <h2>1K APTOS</h2>
                  </div>
                </div>
              </div>
              <div class="col-12 col-md-6 ">
                <div class="card">
                  <div class="face face1">
                    <div class="content">
                      <span class="stars"></span>
                      <h2 class="java">10% OF POOL PRIZES</h2>
                      <p class="java">As a team we have decided to reward the community, this 10% will be distributed
                        among the 10 most active users of our social networks and who interact the most with the
                        community (200 APT for each winner)</p>
                    </div>
                  </div>
                  <div class="face face2">
                    <h2>2K APTOS</h2>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
        <section class="gal" id="gallery">
          <h1 class="title text-center">Gallery</h1>
          <div class="back">
            <div class="slider">
              <div class="slide-track">
                <div class="slide">
                  <img src="../public/img/Infinite/APTOS.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/BOB.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/GUITA.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/HALLOWEN.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/ONEPIECE.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/APTOS.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/BOB.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/GUITA.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/HALLOWEN.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/ONEPIECE.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/APTOS.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/BOB.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/GUITA.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/HALLOWEN.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/ONEPIECE.png" height="256" width="256" alt="" />
                </div>
              </div>
            </div>
          </div>
          <div class="slider">
            <div class="slide-track">
              <div class="slide">
                <img src="../public/img/Infinite/860.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/861.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/862.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/863.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/864.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/865.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/866.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/867.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/868.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/869.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/870.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/871.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/872.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/873.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/874.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/875.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/876.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/877.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/878.png" height="256" width="256" alt="" />
              </div>
              <div class="slide">
                <img src="../public/img/Infinite/879.png" height="256" width="256" alt="" />
              </div>
            </div>
          </div>
          <div class="fast">
            <div class="slider">
              <div class="slide-track">
                <div class="slide">
                  <img src="../public/img/Infinite/1125.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1126.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1127.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1128.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1129.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1130.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1131.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1132.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1133.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1134.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1135.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1136.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1137.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1138.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1139.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1140.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1141.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1142.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1143.png" height="256" width="256" alt="" />
                </div>
                <div class="slide">
                  <img src="../public/img/Infinite/1144.png" height="256" width="256" alt="" />
                </div>
              </div>
            </div>
          </div>
        </section>
        <hr id="roadmap">
        <section class="roadmap">
          <div class="container">
            <h1 class="title text-center m-0">ROADMAP</h1>
            <div class="container-fluid">
              <div class="row">
                <div class="col-12 col-lg-4 col-md-6">
                  <div class="card">
                    <div class="card-body">
                      <h5 class="card-title">First Moment</h5>
                      <p class="card-text">Aptos mainnet launch</p>
                      <hr>
                      <p class="card-text">Progress</p>
                      <progress class="progress is-success" value="100" max="100">15%</progress>
                      <p>100%</p>
                    </div>
                  </div>
                  <div class="line">
                    <hr class="linea">
                  </div>
                </div>
                <div class="col-12 col-lg-4 col-md-6">
                  <div class="card">
                    <div class="card-body">
                      <h5 class="card-title">Second Moment</h5>
                      <p class="card-text text-center">Launch Web page and Social Networks</p>
                      <hr>
                      <p class="card-text">Progress</p>
                      <progress class="progress is-primary" value="100" max="100">15%</progress>
                      <p>100%</p>
                    </div>
                  </div>
                  <div class="line">
                    <hr class="linea">
                  </div>
                </div>
                <div class="col-12 col-lg-4 col-md-6">
                  <div class="card">
                    <div class="card-body">
                      <h5 class="card-title">Third Moment</h5>
                      <p class="card-text text-center">Apply to blue move launchpad</p>
                      <hr>
                      <p class="card-text">Progress</p>
                      <progress class="progress is-small is-warning" max="100"></progress>
                      <p>In progess</p>
                    </div>
                  </div>
                  <div class="line">
                    <hr class="linea">
                  </div>
                </div>
                <div class="col-12 col-lg-4 col-md-6">
                  <div class="card">
                    <div class="card-body">
                      <h5 class="card-title">Fourth Moment</h5>
                      <p class="card-text text-center">MINT DAY</p>
                      <p class="card-text text-center">MINT date will be revealed soon</p>
                      <p class="card-text text-center">The announcement will be in our social networks</p>
                      <hr>
                      <p class="card-text">Progress</p>
                      <progress class="progress is-small is-danger" max="100"></progress>
                      <p>...</p>
                    </div>
                  </div>
                  <div class="line">
                    <hr class="linea">
                  </div>
                </div>
                <div class="col-12 col-lg-4 col-md-6">
                  <div class="card">
                    <div class="card-body">
                      <h5 class="card-title">Fifth Moment </h5>
                      <p class="card-text">DAY OF PRIZESSSS</p>
                      <p class="card-text text-center">ONE WEEK AFTER MINT DAY, THE MOST INCREDIBLE RAFFLE
                        OF THE APTOS NETWORK WILL TAKE PLACE</p>
                      <a href="#" class="btn btn-primary">MORE INFO ABOUT PRIZES</a>
                      <p class="card-text">Progress</p>

                      <progress class="progress is-small is-black" max="100"></progress>
                      <p>...</p>
                    </div>
                  </div>
                  <div class="line">
                    <hr class="linea">
                  </div>
                </div>
                <div class="col-12 col-lg-4 col-md-6">
                  <div class="card">
                    <div class="card-body">
                      <h5 class="card-title">INFINITE </h5>
                      <p class="card-text text-center">Every week NFT Market royalties will be raffled
                        among the APT LUCKY CLUB community and merchandising
                      </p>
                      <hr>
                      <p class="card-text">Progress</p>
                      <progress class="progress is-small is-info" max="100"></progress>
                      <p>INFINITE</p>
                    </div>
                  </div>
                  <div class="line">
                    <hr class="linea">
                  </div>
                </div>

              </div>
            </div>
          </div>
        </section>
        <div class="container">
          <section class="faq z-100" id="faq">
            <h1 class="title text-center">FAQ</h1>
            <div class="row">
              <div class="col-12 col-lg-4 center col-md-6">
                <div class="accordion" id="accordionExample">
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingOne">
                      <button class="accordion-button" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                        q: What is a NFT?
                      </button>
                    </h2>
                    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne"
                      data-bs-parent="#accordionExample">
                      <div class="accordion-body">
                        The NFT is a digital asset, this asset has different functions, in this case it
                        is a
                        ticket for the MOST INCREDIBLE RAFFLE ON THE APTOS NETWORK
                      </div>
                    </div>
                  </div>
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingFive">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseFive" aria-expanded="false" aria-controls="collapseFive">
                        q: Why those NFTs are for you?
                      </button>
                    </h2>
                    <div id="collapseFive" class="accordion-collapse collapse" aria-labelledby="headingFive"
                      data-bs-parent="#accordionExample">
                      <div class="accordion-body">
                        Our proposal is simple
                        !!! Raffles !!! We want to make the biggest raffle within the aptos network and
                        give
                        profits to our community, in addition to that there will be weekly raffles for
                        the
                        royalties of the purchase and sale of nft and
                        merchandising giveaways
                      </div>
                    </div>
                  </div>
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingSix">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseSix" aria-expanded="false" aria-controls="collapseSix">
                        q: How much?
                      </button>
                    </h2>
                    <div id="collapseSix" class="accordion-collapse collapse" aria-labelledby="headingSix"
                      data-bs-parent="#accordionExample">
                      <div class="accordion-body">
                        The mint price will be 2 APT
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-12 col-lg-4 col-md-6">
                <div class="accordion" id="accordionE">
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingFour">
                      <button class="accordion-button" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseFour" aria-expanded="true" aria-controls="collapseFour">
                        q: How many can we mint?
                      </button>
                    </h2>
                    <div id="collapseFour" class="accordion-collapse collapse show" aria-labelledby="headingFour"
                      data-bs-parent="#accordionE">
                      <div class="accordion-body">
                        You can mint as many as you want
                      </div>
                    </div>
                  </div>
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingTwo">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                        q: Where can i buy the APT LUCKYS?
                      </button>
                    </h2>
                    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo"
                      data-bs-parent="#accordionE">
                      <div class="accordion-body">
                        We have applied to the bluemove launchpad, we are waiting for a response, and we
                        would
                        love to launch on this platform
                      </div>
                    </div>
                  </div>
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingThree">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                        q: Prizes?
                      </button>
                    </h2>
                    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree"
                      data-bs-parent="#accordionE">
                      <div class="accordion-body">
                        The info about prizes is <a href="#prizes" class="btn btn-primary">here</a>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="col-12 col-lg-4 col-md-6">
                <div class="accordion" id="accordionT">
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingSeven">
                      <button class="accordion-button" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseSeven" aria-expanded="true" aria-controls="collapseSeven">
                        q: When to mint?
                      </button>
                    </h2>
                    <div id="collapseSeven" class="accordion-collapse collapse show" aria-labelledby="headingSeven"
                      data-bs-parent="#accordionT">
                      <div class="accordion-body">
                        The minting date of the APT LUCKY'S will be announced soon
                        <p>be tuned to our social networks</p>
                      </div>
                    </div>
                  </div>
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingEL">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseEL" aria-expanded="false" aria-controls="collapseEL">
                        q: When is the biggest Raffle?
                      </button>
                    </h2>
                    <div id="collapseEL" class="accordion-collapse collapse" aria-labelledby="headingEL"
                      data-bs-parent="#accordionT">
                      <div class="accordion-body">
                        One week after mint day
                        <p>Info about prizes <a href="#prizes" class="btn btn-primary">here</a></p>
                      </div>
                    </div>
                  </div>
                  <div class="accordion-item">
                    <h2 class="accordion-header" id="headingNine">
                      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse"
                        data-bs-target="#collapseNine" aria-expanded="false" aria-controls="collapseNine">
                        q: What will happen with the Royalties?
                      </button>
                    </h2>
                    <div id="collapseNine" class="accordion-collapse collapse" aria-labelledby="headingNine"
                      data-bs-parent="#accordionT">
                      <div class="accordion-body">
                        Every royalty generated by a purchase or a sell, will be used for more raffles,
                        ( 30%
                        of
                        the
                        royalties will be for the development team of this project )
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </section>
        </div>




      </div>
    </section>
  </div>
  <section class="footer">
    <div class="row">
      <div class="col-12 col-lg-6" id="networks">
        <h1>APTLUCKY CLUB</h1>
        <a href="https://twitter.com/LuckyApt" target="_blank" class="btn btn-primary" id="twitter">
          <i class="bi bi-twitter"></i> Twitter
        </a>
        <a href="https://discord.gg/H9QNPJy6wy" class="btn btn-primary" target="_blank" id="twitter">
          <i class="bi bi-discord"></i> Discord
        </a>
        <a href="https://t.me/+BByUPXvBKeNiZDQx" target="_blank" class="btn btn-primary" id="twitter">
          <i class="bi bi-telegram"></i> Telegram
        </a>
      </div>
      <div class="col-12 col-lg-6" id="touch">

      </div>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      showMobileMenu: false,
    }
  }
}
</script>

<style lang="scss">
@import '../public/css/main.css'
</style>
