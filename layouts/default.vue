<template>
  <div id='top'>
    <header id='header-five' class="s-header">
        <div class="row">
            <div class="header-logo">
                <a class="site-logo" href="index.html"><img src="logo-menu.png" alt="Homepage"></a>
            </div>
            <nav id='nav-main' class="header-nav-wrap">
                <ul class="header-nav">
                    <li class="current"><a class="smoothscroll"  href="#home" title="home" v-on:click="navClicked">HOME</a></li>
                    <li><a class="smoothscroll"  href="#oferta" title="services" v-on:click="navClicked">PONUDA</a></li>
                    <li><a class="smoothscroll"  href="#range" title="about" v-on:click="navClicked">SURAĐUJTE S NAMA</a></li>
                    <li><a class="smoothscroll"  href="#about" title="works" v-on:click="navClicked">INFO</a></li>
                    <li><a class="smoothscroll"  href="#contact" title="contact" v-on:click="navClicked">KONTAKT</a></li>
                </ul>
            </nav>
            <a id='header-icon' class="header-menu-toggle" href="#0">
                <span class="header-menu-icon" v-on:click="openMobile"></span>
            </a>
        </div>
    </header>

    <section id="home" class="s-home page-hero target-section">
        <div class="video-container-home">
          <video autoplay muted loop id="myVideo">
            <source src="copy-1.mp4" type="video/mp4">
            <source src="copy-1.webm" type="video/webm">
          </video>
        </div>
        <div class="shadow-overlay"></div>
        <div class="home-content">
            <div class="row home-content__main">
                <h1>Oglašavanje smještajnih objekata</h1>
                <div class="home-content__button">
                  <a href="#oferta" class="smoothscroll btn btn-animatedbg">Pogledajte ponudu</a>
                </div>
            </div>
        </div>
    </section>
    <section id="oferta" class="s-oferta target-section">
        <div class="row section-header">
            <div class="col-full">
                <h3 data-num="01" class="subhead">Ponuda</h3>
                <h1 class="display-1 display-1--light">Naša ponuda uključuje:</h1>
            </div>
            <div class="bottom">
                <div class="row">
                  <div class="col-six tab-full list">
                      <div class="head"><span>01.</span> Oglašavanje na vodećim svjetskim portalima</div>
                      <p>Oglašavamo vaš smještaj na preko 100 vodećih svjetskih portala. Posredstvom partnerskih portala, vaš objekt je zastupljen na svim relevantnim kanalima za rezervaciju smještaja, čime se maksimiziraju mogućnosti za optimalnu popunjenost.</p>
                  </div>

                  <div class="col-six tab-full list">
                      <div class="head"><span>02.</span> Komunikacija s gostima</div>
                      <p>Od upita, preko potvrde rezervacije do dolaska gosta u smještajni objekt. Na 10 + svjetskih jezika, na raspolaganju smo gostima 24h dnevno, 7 dana u tjednu. Odgovor slijedi unutar 1h  od slanja upita.</p>
                  </div>
                </div>

                <div class="row">
                  <div class="col-six tab-full list">
                      <div class="head"><span>03.</span> Profesionalno fotografiranje</div>
                      <p>U suradnji sa vodećim fotografima specijaliziranjima za nekretnine, nudimo uslugu profesionalnog fotografiranja objekta (interijer, eksterijer i zračne fotografije) o trošku agencije.</p>
                  </div>

                  <div class="col-six tab-full list">
                      <div class="head"><span>04.</span>  Korisnička podrška za iznajmljivače</div>
                      <p>Tu smo za vas: preko telefona, tekstualnih poruka, elektroničke pošte i osobno. 7 dana u tjednu tijekom cijele godine.</p>
                  </div>
                </div>
                <div class='row'>
                  <div class="col-six tab-full list">
                      <div class="head"><span>05.</span> Savjetovanje</div>
                      <p>Savjetujemo Vas  o svim aspektima organizacije i uređenja smještajnog objekta te načinu rada s gostima, kako bi zajedno povećali konkurentnost ponude i zadovoljstvo gosta.</p>
                  </div>
                </div>
            </div>
        </div>
    </section>
    <section id="management" class="s-oferta target-section s-oferta-2">
        <div class="row section-header">
            <div class="col-full">
                <h1 class="display-1">Prepustite nam brigu o popunjenosti Vašeg smještajnog objekta i spremni dočekajte goste.</h1>
            </div>
        </div>
        <div class="row management-process block-1-4 block-tab-full">
            <div class="col-block item-process">
                <div class="item-process__header icon">
                    <img src="people.png">
                </div>
                <p>Savjetujemo Vas  o svim aspektima organizacije i uređenja smještajnog objekta te načinu rada s gostima.</p>
            </div>
            <div class="col-block item-process">
                <div class="item-process__header icon">
                    <img src="photo-camera.png">
                </div>
                <p>U suradnji sa vodećim fotografima specijaliziranjima za nekretnine, nudimo uslugu profesionalnog fotografiranja objekta  o trošku agencije.</p>
            </div>
            <div class="col-block item-process">
                <div class="item-process__header icon">
                    <img src="desktop-monitor.png">
                </div>
                <p>Naši su oglasi prisutni na svim vodećim svjetskim portalima za oglašavanje smještaja u turizmu. </p>
            </div>
            <div class="col-block item-process">
                <div class="item-process__header icon">
                    <img src="kalendar2.png">
                </div>
                <p>Naši se oglasi ažuriraju na dnevnoj bazi. Konstantno pratimo tržište i prilagođavamo aktivnosti.</p>
            </div>
            <div class="col-block item-process">
                <div class="item-process__header icon">
                    <img src="telefon.png">
                </div>
                <p>Svi klijenti imaju na raspolaganju korisničku podršku u svako doba dana tijekom cijele godine.</p>
            </div>
            <div class="col-block item-process">
                <div class="item-process__header icon">
                    <img src="24h.png">
                </div>
                <p>Naši su agenti na raspolaganju gostima i klijentima 16h dnevno, 7 dana u tjednu. Odgovor slijedi unutar 1h .</p>
            </div>
            <div class="col-block item-process">
                <div class="item-process__header icon">
                    <img src="globus.png">
                </div>
                <p>Naši agenti raspolažu s 10+ svjetskih jezika što omogućava
neposrednu komunikaciju s gostom.</p>
            </div>
            <div class="col-block item-process">
                <div class="item-process__header icon">
                    <img src="comments.png">
                </div>
                <p>Vodimo gosta kroz cijeli proces - od upita, preko potvrde do dolaska
u smještajni objekt.</p>
            </div>
        </div>  <!-- end management-process -->
    </section>
    <section id="management" class="s-management target-section">
        <div class="row section-header">
            <div class="col-full">
                <h1 class="display-1">Neki od naših partnera</h1>
            </div>
        </div>
        <div class="row logo-process block-1-4-cla block-tab-full">
            <carousel :per-page-custom="[[768, 2], [1024, 4]]" :easing="linear" :autoplay="true" :loop="true" :scrollPerPage="false">
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="vrbo-3.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="booking-3.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="Ferienhausmiete.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="Trivago.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="casamundo.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="Hotels.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="priceline.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="tripadvisor.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="hometogo.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="homeaway.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="orbitz.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="kayak.png">
                        </div>
                    </div>
                </slide>
                <slide>
                    <div class="col-block item-process">
                        <div class="item-process__header icon">
                            <img src="tui.png">
                        </div>
                    </div>
                </slide>
            </carousel>
        </div>
    </section>
    <section id="range" class="s-range target-section">
        <div class="row section-header">
            <div class="col-full">
                <h3 data-num="03" class="subhead">Surađujte s nama</h3>
                    <form id="mc-form-1" class="group mc-form" novalidate="true">
                        <div class="input-group name">
                          <input type="text" name="name" v-model="user.name" placeholder="Ime i prezime">
                        </div>

                        <div class="input-group mail">
                          <input type="email" name="mail" v-model="user.email" placeholder="E-mail adresa">
                        </div>
                        <div class="input-group topic">
                          <input type="text" name="topic" v-model="user.telefon" placeholder="Telefon">
                        </div>
                        <div class="input-group content">
                          <input type="text" name="topic" v-model="user.adresa" placeholder="Adresa">
                        </div>
                        <div class="input-group name">
                          <input type="text" name="name" v-model="user.tip" placeholder="Tip Smještaja">
                        </div>
                        <div class="input-group mail">
                          <input type="email" name="jedinice" v-model="user.jedinice" placeholder="Vaš Upit">
                        </div>
                        <input type="submit" name="send" value="Pošalji upit" @click="on_submit">
                    </form>
                </div>
        </div>
        <div class="row map aos-init aos-animate">
            <div class="col-full map-markers">
                <img src="slijepa-karta-hrvatske.png">
                <div id="rijeka" class="circle"></div>
                <div class="circle" style="top: 57.0%; left: 32.5%;"></div>
                <div class="circle" style="top: 64.0%; left: 39.5%;"></div>
                <div class="circle" style="top: 62.0%; left: 48.5%;"></div>
                <div class="circle" style="top: 74.0%; left: 58.5%;"></div>
                <div class="circle" style="top: 87.0%; left: 73.5%;"></div>
                <div class="circle active" style="top: 71.0%; left: 51.5%;"></div>

            </div>
        </div>
    </section>
    <section id="about" class="s-about target-section">
        <div class="row section-header">
            <div class="col-full">
                <h3 data-num="04" class="subhead">O Nama</h3>
                <p class="lead">Five Star International d.o.o. okuplja tim mladih ljudi sa
sveučilišnim obrazovanjem iz područja turizma i marketinga. Višegodišnje iskustvo i zadovoljstvo naših klijenata garancija su uspješne suradnje u budućnosti. Obratite nam se s povjerenjem i bez obaveza!<br></p>
            </div>
            <div class="bottom">
                <div class="col-six tab-full list">
                    <div class="head">Naša ponuda uključuje:</div>
                    <ul>
                        <li><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13 13" id="circle"><g class="a"><circle class="b" cx="6.5" cy="6.5" r="6.5"/><circle class="c" cx="6.5" cy="6.5" r="5"/></g></svg>  preuzimamo kompletnu komunikaciju s gostima i partnerima</li>
                        <li><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13 13" id="circle"><g class="a"><circle class="b" cx="6.5" cy="6.5" r="6.5"/><circle class="c" cx="6.5" cy="6.5" r="5"/></g></svg>  liste popunjenosti s terminima boravka šaljemo nekoliko tjedana prije dolaska gostiju</li>
                        <li><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13 13" id="circle"><g class="a"><circle class="b" cx="6.5" cy="6.5" r="6.5"/><circle class="c" cx="6.5" cy="6.5" r="5"/></g></svg>  minimiziramo broj otkazanih rezervacija</li>
                        <li><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13 13" id="circle"><g class="a"><circle class="b" cx="6.5" cy="6.5" r="6.5"/><circle class="c" cx="6.5" cy="6.5" r="5"/></g></svg> individualna posvećenost i osobni pristup svakom objektu osigurava maksimalnu popunjenost uz optimalne cijene</li>
                        <li><svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 13 13" id="circle"><g class="a"><circle class="b" cx="6.5" cy="6.5" r="6.5"/><circle class="c" cx="6.5" cy="6.5" r="5"/></g></svg> imamo jednu od najpovoljnijih tarifa agencijske provizije na tržištu koja  se obračunava na temelju ukupnog prihoda objekta</li>
                    </ul>
                    <div class="summary">Obratite nam se s povjerenjem i zatražite besplatnu procjenu prihoda za svoj objekt!</div>

                </div>
                <div class="col-six tab-full boxes">
                    <div class="line">
                        <div class="box box1">
                            <div class="head">6 godina</div>
                            <div class="dsc">Iskustva</div>
                        </div>
                        <div class="box box2">
                            <div class="head">24/7</div>
                            <div class="dsc">Dostupnost</div>
                        </div>
                    </div>
                    <div class="line">
                        <div class="box box3">
                            <div class="head">Elastičnost</div>
                            <div class="dsc">i profesonalnost</div>
                        </div>
                    </div>
                    <div class="line">
                        <div class="box box4">
                            <div class="head">Brzi odgovori</div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="col-full ured-wrapper">
              <img src='ured-2.jpg' class="lead lead--bottom">
            </div>
        </div>
    </section>
    <section id="contact" class="s-contact target-section">
        <div class="row section-header">
            <div class="col-full">
                <h3 data-num="05" class="subhead">Kontakt</h3>
            </div>
        </div>
        <div class="row contact-infos">
            <div class="col-eight tab-full form">
                <h4 class="">Kontakt</h4>
                <div class="">
                    <form id="mc-form" class="group mc-form" novalidate="true">
                        <div class="input-group name">
                          <input type="text" v-model="user.ime2" name="name" placeholder="Ime i prezime">
                        </div>

                        <div class="input-group mail">
                          <input type="email" v-model="user.email2" name="mail" placeholder="E-mail adresa">
                        </div>
                        <div class="input-group topic">
                          <input type="text" v-model="user.telefon2" name="topic" placeholder="Telefon">
                        </div>
                        <div class="input-group topic">
                          <input type="text" v-model="user.naslov2" name="topic" placeholder="Naslov">
                        </div>
                        <div class="input-group content">
                          <textarea rows="12" v-model="user.poruka2" name="content" placeholder="Poruka"></textarea>
                        </div>
                        <input type="submit" name="send" value="Pošalji" @click="on_submit" >
                    </form>
                </div>
            </div>
            <div class="col-four tab-full info">
                <h4>INFORMACIJE</h4>
                <div class="box">
                    <p>Five Star International d.o.o.</p>
                    <p>Četvrt Žarka Dražojevića 1, Omiš</p>
                </div>
                <div class="box">
                    <div class="in"><a class="phone" href="tel:+38595555555">Tel: +385 95 555 5555</a></div>
                    <div class="in"><a class="email" href= "mailto:info@5star.hr" >E-mail: info@5star.hr</a></div>
                </div>
                <div class="box">
                    <div class="social">
                        <img src="facebook.png">
                        <a href="https://www.facebook.com/5star.adria/" target="_blank" class="link"></a>
                    </div>
                    <div class="social">
                        <img src="instagram.png">
                        <a href="https://www.instagram.com/5star.hr/" target="_blank" class="link"></a>
                    </div>
                    <div class="social">
                        <img src="linkedin.png">
                        <a href="https://www.instagram.com/5star.hr/" target="_blank" class="link"></a>
                    </div>
                </div>
                <div class='box'>
                  <img src='ured.jpg' >
                </div>
            </div>
        </div> <!-- end contact-infos -->
    </section>
    <footer>
        <div class="row">
            <div class="col-full cl-copyright block-1-2 block-tab-full">
                <div class="col-block copy-text">
                    &copy; Copyright {{currentYear}}, 5star
                </div>
            </div>
        </div>
        <div class="cl-go-top">
            <a class="smoothscroll" href="#top"></a>
        </div>
    </footer>
  </div>
</template>
<script>
import axios from 'axios'
import { Carousel, Slide } from 'vue-carousel';


export default {
  data () {
    return {
      isActive: false,
      currentYear: 2021,
      user: {
        name: '',
        email: '',
        telefon: '',
        adresa: '',
        jedinice: '',
        tip: '',
        ime2: '',
        telefon2: '',
        email2: '',
        naslov2: '',
        poruka2: ''
      }
    }
  },
    components: {
        Carousel,
        Slide
    },
    methods: {
        handleScroll () {

        },
        openMobile() {
            this.isActive = !this.isActive;
            let navEle = document.getElementById('nav-main');
            let headIcon = document.getElementById('header-icon');
            if(this.isActive) {
                headIcon.classList.add("is-clicked");
                navEle.style.display = 'block';
            } else {
                headIcon.classList.remove("is-clicked");
                navEle.style.display = 'none';
            }
        },
        navClicked() {
            let navEle = document.getElementById('nav-main');
            let headIcon = document.getElementById('header-icon');
            this.isActive = false;
            headIcon.classList.remove("is-clicked");
            navEle.style.display = 'none';
        },
        async on_submit() {
            let response = await axios.post('/api/contact/send-mail', this.user);
            this.user = {
                name: '',
                email: '',
                telefon: '',
                adresa: '',
                jedinice: '',
                tip: '',
                ime2: '',
                telefon2: '',
                email2: '',
                naslov2: '',
                poruka2: ''
            }
        }
    },
    created () {

    },
    destroyed () {

    },
    head() {
        return {
            meta: [
                {
                    name: "viewport",
                    content: "user-scalable=no, width=device-width, initial-scale=1.0"
                },
                {
                    name: 'apple-mobile-web-app-capable',
                    content: 'yes'
                }
            ]
        }
    }
}
</script>

<style>
.a,.c {
    fill:none;
}
.a {
    color: #dfbf5f;
    stroke: #dfbf5f;
    stroke-width:3px;
}

#home, #management, #range, #about, #contact {
    overflow: hidden;
}

body {
    overflow-x: hidden;
    width: 100%;
}
.b {
    color: #dfbf5f;
    stroke:none;
}
body {
    position: relative;
}
#circle {
    width: 10px;

}

body {
  background: #151515;
  font-family: Roboto,sans-serif;
  font-size: 1.7rem;
  font-style: normal;
  font-weight: 400;
  line-height: 1.941;
  color: #595959;
  margin: 0;
  padding: 0;
}

 #rijeka {
    top: 39.0%;
    left: 9.0%;
 }

 .ured-wrapper {
     margin-top: 3rem;
 }

 .s-header {
    width: 100%;
    height: 72px;
    background-color: transparent;
    position: absolute;
    top: 4.2rem;
    z-index: 500
}

.s-header>.row {
    position: relative;
    height: 72px;
    max-width: 1400px
}

.s-header.offset {
    -webkit-transform: translate3d(0,-100%,0);
    -ms-transform: translate3d(0,-100%,0);
    transform: translate3d(0,-100%,0);
    -webkit-transition: all .25s ease-in-out;
    transition: all .25s ease-in-out
}

.ured-wrapper {
   text-align: center;
}
.ured-wrapper > img {
    width: 70%;
}
.s-header.scrolling {
    -webkit-transform: translate3d(0,0,0);
    -ms-transform: translate3d(0,0,0);
    transform: translate3d(0,0,0)
}

.s-header.sticky {
    position: fixed;
    top: 0;
    background-color: #000!important;
    opacity: 0;
    visibility: hidden;
    z-index: 600
}

.s-header.sticky>.row {
    max-width: 1200px
}

.s-header.sticky .header-logo {
    padding-left: 20px
}

.s-header.sticky .header-nav-wrap {
    top: 0;
    right: 20px;
    left: auto
}

.s-header.sticky.scrolling {
    opacity: 1;
    visibility: visible
}

.s-header.sticky .header-menu-toggle {
    top: 12px
}

.header-logo {
    display: inline-block;
    position: absolute;
    margin: 0;
    padding: 0;
    left: 0;
    top: 50%;
    -webkit-transform: translateY(-50%);
    -ms-transform: translateY(-50%);
    transform: translateY(-50%);
    z-index: 501
}

.copy-text {
    color: white;
    font-size: 16px;
}

.header-logo a {
    display: flex;
    align-items: center;
    padding: 0;
    outline: 0;
    border: none
}

.header-logo img {
    width: 40%;
    height: auto;
    -webkit-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out
}

.header-nav-wrap {
    font-family: Roboto,sans-serif;
    font-size: 1.5rem;
    text-transform: uppercase;
    letter-spacing: .2rem;
    position: absolute;
    top: 0;
    right: 0
}

.header-nav {
    display: inline-block;
    list-style: none;
    margin: 0;
    height: 72px
}

.header-nav li {
    display: inline-block;
    padding-left: 0;
    margin-right: 3rem
}

.header-nav li a {
    display: block;
    line-height: 72px;
    color: #fff
}

.header-nav li a:hover,.header-nav li.current a {
    color: #dfbf5f;
    border-bottom: 1px solid #dfbf5f
}

.header-menu-toggle {
    display: none;
    position: absolute;
    right: 29px;
    top: 18px;
    height: 42px;
    width: 42px;
    line-height: 42px;
    font-family: proxima_nova,sans-serif;
    font-size: 1.3rem;
    text-transform: uppercase;
    letter-spacing: .2rem;
    color: rgba(255,255,255,.5);
    -webkit-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out
}

.header-menu-toggle:focus,.header-menu-toggle:hover {
    color: #fff
}

.header-menu-toggle span {
    display: block;
    width: 24px;
    height: 2px;
    margin-top: -1px;
    position: absolute;
    left: 9px;
    top: 50%;
    right: auto;
    bottom: auto;
    background-color: #fff;
    -webkit-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out;
    font: 0/0 a;
    text-shadow: none;
    color: transparent
}

.header-menu-toggle span::after,.header-menu-toggle span::before {
    content: '';
    width: 100%;
    height: 100%;
    background-color: inherit;
    position: absolute;
    left: 0;
    -webkit-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out
}

.header-menu-toggle span::before {
    top: -9px
}

.header-menu-toggle span::after {
    bottom: -9px
}

.header-menu-toggle.is-clicked span {
    background-color: rgba(255,255,255,0);
    -webkit-transition: all .1s ease-in-out;
    transition: all .1s ease-in-out
}

.header-menu-toggle.is-clicked span::after,.header-menu-toggle.is-clicked span::before {
    background-color: #fff
}

.header-menu-toggle.is-clicked span::before {
    top: 0;
    -webkit-transform: rotate(135deg);
    -ms-transform: rotate(135deg);
    transform: rotate(135deg)
}

.header-menu-toggle.is-clicked span::after {
    bottom: 0;
    -webkit-transform: rotate(225deg);
    -ms-transform: rotate(225deg);
    transform: rotate(225deg)
}

.row {
    width: 89%;
    max-width: 1200px;
    margin: 0 auto
}

.row:after {
    content: "";
    display: table;
    clear: both
}

.row .row {
    width: auto;
    max-width: none;
    margin-left: -20px;
    margin-right: -20px
}

[class*=col-] {
    float: left;
    padding: 0 20px
}

[class*=col-]+[class*=col-].end {
    float: right
}

.collapse>[class*=col-],[class*=col-].collapse {
    padding: 0
}

.col-one {
    width: 8.33333%
}

.col-1-6,.col-two {
    width: 16.66667%
}

.col-1-4,.col-three {
    width: 25%
}

.col-1-3,.col-four {
    width: 33.33333%
}

.col-five {
    width: 41.66667%
}

.col-1-2,.col-six {
    width: 50%
}

.col-seven {
    width: 58.33333%
}

.col-2-3,.col-eight {
    width: 66.66667%
}

.col-3-4,.col-nine {
    width: 75%
}

.col-5-6,.col-ten {
    width: 83.33333%
}

.col-eleven {
    width: 91.66667%
}

.col-full,.col-twelve {
    width: 100%
}

@media only screen and (max-width: 1200px) {
    .row .row {
        margin-left:-15px;
        margin-right: -15px
    }

    [class*=col-] {
        padding: 0 15px
    }

    .md-1-6,.md-two {
        width: 16.66667%
    }

    .md-one {
        width: 8.33333%
    }

    .md-1-4,.md-three {
        width: 25%
    }

    .md-1-3,.md-four {
        width: 33.33333%
    }

    .md-five {
        width: 41.66667%
    }

    .md-1-2,.md-six {
        width: 50%
    }

    .md-seven {
        width: 58.33333%
    }

    .md-2-3,.md-eight {
        width: 66.66667%
    }

    .md-3-4,.md-nine {
        width: 75%
    }

    .md-5-6,.md-ten {
        width: 83.33333%
    }

    .md-eleven {
        width: 91.66667%
    }

    .md-full,.md-twelve {
        width: 100%
    }
}

@media only screen and (max-width: 800px) {
    .row {
        width:90%
    }

    .tab-1-4 {
        width: 25%
    }

    .tab-1-3 {
        width: 33.33333%
    }

    .tab-1-2 {
        width: 50%
    }

    .tab-2-3 {
        width: 66.66667%
    }

    .tab-3-4 {
        width: 75%
    }

    .tab-full {
        width: 100%
    }

    .hide-on-tablet {
        display: none
    }
}

@media only screen and (max-width: 600px) {
    .row {
        width:auto;
        padding-left: 25px;
        padding-right: 25px
    }

    .row .row {
        margin-left: -10px;
        margin-right: -10px;
        padding-left: 0;
        padding-right: 0
    }

    [class*=col-] {
        padding: 0 10px
    }

    .mob-1-4 {
        width: 25%
    }

    .mob-1-3 {
        width: 33.33333%
    }

    .mob-1-2 {
        width: 50%
    }

    .mob-2-3 {
        width: 66.66667%
    }

    .mob-3-4 {
        width: 75%
    }

    .mob-full {
        width: 100%
    }

    .hide-on-mobile {
        display: none
    }
}

@media only screen and (max-width: 400px) {
    .row .row {
        margin-left:0;
        margin-right: 0
    }

    [class*=col-]:not(.col-block) {
        width: 100%!important;
        float: none!important;
        clear: both!important;
        margin-left: 0;
        margin-right: 0;
        padding: 0!important
    }

    [class*=col-]+[class*=col-].end {
        float: none
    }

    .stack .col-block {
        width: 100%!important;
        float: none!important;
        clear: both!important;
        margin-left: 0;
        margin-right: 0
    }
}

[class*=block-]:after {
    content: "";
    display: table;
    clear: both
}

.block-1-6 .col-block {
    width: 16.66667%
}

.block-1-5 .col-block {
    width: 20%
}

.block-1-4 .col-block {
    width: 25%
}

.block-1-4-cla .col-block {
    width: 75%
}

.block-1-3 .col-block {
    width: 33.33333%
}

.block-1-2 .col-block {
    width: 50%
}

.block-1-2 .col-block:nth-child(2n+1),.block-1-3 .col-block:nth-child(3n+1),.block-1-4 .col-block:nth-child(4n+1),.block-1-5 .col-block:nth-child(5n+1),.block-1-6 .col-block:nth-child(6n+1) {
    clear: both
}

@media only screen and (max-width: 1200px) {
    .block-m-1-6 .col-block {
        width:16.66667%
    }

    .block-m-1-5 .col-block {
        width: 20%
    }

    .block-m-1-4 .col-block {
        width: 25%
    }

    .block-m-1-3 .col-block {
        width: 33.33333%
    }

    .block-m-1-2 .col-block {
        width: 50%
    }

    .block-m-full .col-block {
        width: 100%;
        clear: both
    }

    [class*=block-m-] .col-block:nth-child(n) {
        clear: none
    }

    .block-m-1-2 .col-block:nth-child(2n+1),.block-m-1-3 .col-block:nth-child(3n+1),.block-m-1-4 .col-block:nth-child(4n+1),.block-m-1-5 .col-block:nth-child(5n+1),.block-m-1-6 .col-block:nth-child(6n+1) {
        clear: both
    }
}

@media only screen and (max-width: 800px) {
    .block-tab-1-6 .col-block {
        width:16.66667%
    }

    .block-tab-1-5 .col-block {
        width: 20%
    }

    .block-tab-1-4 .col-block {
        width: 25%
    }

    .block-tab-1-3 .col-block {
        width: 33.33333%
    }

    .block-tab-1-2 .col-block {
        width: 50%
    }

    .block-tab-full .col-block {
        width: 100%;
        clear: both
    }

    [class*=block-tab-] .col-block:nth-child(n) {
        clear: none
    }

    .block-tab-1-2 .col-block:nth-child(2n+1),.block-tab-1-3 .col-block:nth-child(3n+1),.block-tab-1-4 .col-block:nth-child(4n+1),.block-tab-1-5 .col-block:nth-child(5n+1),.block-tab-1-6 .col-block:nth-child(6n+1) {
        clear: both
    }
}

@media only screen and (max-width: 600px) {
    .block-mob-1-6 .col-block {
        width:16.66667%
    }

    .block-mob-1-5 .col-block {
        width: 20%
    }

    .block-mob-1-4 .col-block {
        width: 25%
    }

    .block-mob-1-3 .col-block {
        width: 33.33333%
    }

    .block-mob-1-2 .col-block {
        width: 50%
    }

    .block-mob-full .col-block {
        width: 100%;
        clear: both
    }

    [class*=block-mob-] .col-block:nth-child(n) {
        clear: none
    }

    .block-mob-1-2 .col-block:nth-child(2n+1),.block-mob-1-3 .col-block:nth-child(3n+1),.block-mob-1-4 .col-block:nth-child(4n+1),.block-mob-1-5 .col-block:nth-child(5n+1),.block-mob-1-6 .col-block:nth-child(6n+1) {
        clear: both
    }
}

.group:after {
    content: "";
    display: table;
    clear: both
}

.is-hidden {
    display: none
}

.is-invisible {
    visibility: hidden
}

.antialiased {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.overflow-hidden {
    overflow: hidden
}

.remove-bottom {
    margin-bottom: 0
}

.half-bottom {
    margin-bottom: 1.5rem!important
}

.add-bottom {
    margin-bottom: 3rem!important
}

.no-border {
    border: none
}

.full-width {
    width: 100%
}

.text-center {
    text-align: center
}

.text-left {
    text-align: left
}

.text-right {
    text-align: right
}

.pull-left {
    float: left
}

.pull-right {
    float: right
}

.align-center {
    margin-left: auto;
    margin-right: auto;
    text-align: center
}


@media only screen and (min-width: 993px) {
    .header-nav-wrap {
        display:block!important
    }
}

@media only screen and (max-width: 992px) {
      .s-header {
        top:0
    }

    .s-header>.row {
        max-width: none;
        width: auto
    }

    .header-logo {
        left: 10px;
        top: 3rem;
        -webkit-transform: translateY(0);
        -ms-transform: translateY(0);
        transform: translateY(0)
    }

    .header-logo img {
        width: 180px;
        height: 63px
    }

    .s-header.sticky .header-logo {
        top: 50%;
        left: 20px;
        -webkit-transform: translateY(-50%);
        -ms-transform: translateY(-50%);
        transform: translateY(-50%)
    }

    .header-menu-toggle {
        top: 3rem;
        right: 40px
    }

    .header-nav-wrap {
        display: none;
        height: auto;
        width: 100%;
        height: 100vh;
        right: auto;
        top: 0;
        left: 0;
        background-color: #000;
        padding: 120px 40px 21px
    }

    .header-nav-wrap .header-nav {
        display: block;
        height: auto;
        margin: 0 0 4.2rem 0;
        border-top: 1px solid rgba(255,255,255,.07)
    }

    .header-nav-wrap .header-nav li {
        display: block;
        margin: 0;
        padding: 0;
        border-bottom: 1px dotted rgba(255,255,255,.07)
    }

    .header-nav-wrap .header-nav li a {
        padding: 18px 0;
        line-height: 18px
    }

    .s-header.sticky .header-nav-wrap {
        right: 0
    }

    .header-menu-toggle {
        display: block
    }
}

@media only screen and (max-width: 400px) {
    .header-logo {
        left:30px
    }

    .s-header.sticky .header-logo {
        left: 10px
    }

    .header-menu-toggle {
        right: 30px
    }

    .header-menu-toggle::before {
        display: none
    }
}

[data-aos][data-aos][data-aos-duration='50'],body[data-aos-duration='50'] [data-aos] {
    transition-duration: 50ms
}

[data-aos][data-aos][data-aos-delay='50'],body[data-aos-delay='50'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='50'].aos-animate,body[data-aos-delay='50'] [data-aos].aos-animate {
    transition-delay: 50ms
}

[data-aos][data-aos][data-aos-duration='100'],body[data-aos-duration='100'] [data-aos] {
    transition-duration: .1s
}

[data-aos][data-aos][data-aos-delay='100'],body[data-aos-delay='100'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='100'].aos-animate,body[data-aos-delay='100'] [data-aos].aos-animate {
    transition-delay: .1s
}

[data-aos][data-aos][data-aos-duration='150'],body[data-aos-duration='150'] [data-aos] {
    transition-duration: .15s
}

[data-aos][data-aos][data-aos-delay='150'],body[data-aos-delay='150'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='150'].aos-animate,body[data-aos-delay='150'] [data-aos].aos-animate {
    transition-delay: .15s
}

[data-aos][data-aos][data-aos-duration='200'],body[data-aos-duration='200'] [data-aos] {
    transition-duration: .2s
}

[data-aos][data-aos][data-aos-delay='200'],body[data-aos-delay='200'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='200'].aos-animate,body[data-aos-delay='200'] [data-aos].aos-animate {
    transition-delay: .2s
}

[data-aos][data-aos][data-aos-duration='250'],body[data-aos-duration='250'] [data-aos] {
    transition-duration: .25s
}

[data-aos][data-aos][data-aos-delay='250'],body[data-aos-delay='250'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='250'].aos-animate,body[data-aos-delay='250'] [data-aos].aos-animate {
    transition-delay: .25s
}

[data-aos][data-aos][data-aos-duration='300'],body[data-aos-duration='300'] [data-aos] {
    transition-duration: .3s
}

[data-aos][data-aos][data-aos-delay='300'],body[data-aos-delay='300'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='300'].aos-animate,body[data-aos-delay='300'] [data-aos].aos-animate {
    transition-delay: .3s
}

[data-aos][data-aos][data-aos-duration='350'],body[data-aos-duration='350'] [data-aos] {
    transition-duration: .35s
}

[data-aos][data-aos][data-aos-delay='350'],body[data-aos-delay='350'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='350'].aos-animate,body[data-aos-delay='350'] [data-aos].aos-animate {
    transition-delay: .35s
}

[data-aos][data-aos][data-aos-duration='400'],body[data-aos-duration='400'] [data-aos] {
    transition-duration: .4s
}

[data-aos][data-aos][data-aos-delay='400'],body[data-aos-delay='400'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='400'].aos-animate,body[data-aos-delay='400'] [data-aos].aos-animate {
    transition-delay: .4s
}

[data-aos][data-aos][data-aos-duration='450'],body[data-aos-duration='450'] [data-aos] {
    transition-duration: .45s
}

[data-aos][data-aos][data-aos-delay='450'],body[data-aos-delay='450'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='450'].aos-animate,body[data-aos-delay='450'] [data-aos].aos-animate {
    transition-delay: .45s
}

[data-aos][data-aos][data-aos-duration='500'],body[data-aos-duration='500'] [data-aos] {
    transition-duration: .5s
}

[data-aos][data-aos][data-aos-delay='500'],body[data-aos-delay='500'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='500'].aos-animate,body[data-aos-delay='500'] [data-aos].aos-animate {
    transition-delay: .5s
}

[data-aos][data-aos][data-aos-duration='550'],body[data-aos-duration='550'] [data-aos] {
    transition-duration: .55s
}

[data-aos][data-aos][data-aos-delay='550'],body[data-aos-delay='550'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='550'].aos-animate,body[data-aos-delay='550'] [data-aos].aos-animate {
    transition-delay: .55s
}

[data-aos][data-aos][data-aos-duration='600'],body[data-aos-duration='600'] [data-aos] {
    transition-duration: .6s
}

[data-aos][data-aos][data-aos-delay='600'],body[data-aos-delay='600'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='600'].aos-animate,body[data-aos-delay='600'] [data-aos].aos-animate {
    transition-delay: .6s
}

[data-aos][data-aos][data-aos-duration='650'],body[data-aos-duration='650'] [data-aos] {
    transition-duration: .65s
}

[data-aos][data-aos][data-aos-delay='650'],body[data-aos-delay='650'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='650'].aos-animate,body[data-aos-delay='650'] [data-aos].aos-animate {
    transition-delay: .65s
}

[data-aos][data-aos][data-aos-duration='700'],body[data-aos-duration='700'] [data-aos] {
    transition-duration: .7s
}

[data-aos][data-aos][data-aos-delay='700'],body[data-aos-delay='700'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='700'].aos-animate,body[data-aos-delay='700'] [data-aos].aos-animate {
    transition-delay: .7s
}

[data-aos][data-aos][data-aos-duration='750'],body[data-aos-duration='750'] [data-aos] {
    transition-duration: .75s
}

[data-aos][data-aos][data-aos-delay='750'],body[data-aos-delay='750'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='750'].aos-animate,body[data-aos-delay='750'] [data-aos].aos-animate {
    transition-delay: .75s
}

[data-aos][data-aos][data-aos-duration='800'],body[data-aos-duration='800'] [data-aos] {
    transition-duration: .8s
}

[data-aos][data-aos][data-aos-delay='800'],body[data-aos-delay='800'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='800'].aos-animate,body[data-aos-delay='800'] [data-aos].aos-animate {
    transition-delay: .8s
}

[data-aos][data-aos][data-aos-duration='850'],body[data-aos-duration='850'] [data-aos] {
    transition-duration: .85s
}

[data-aos][data-aos][data-aos-delay='850'],body[data-aos-delay='850'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='850'].aos-animate,body[data-aos-delay='850'] [data-aos].aos-animate {
    transition-delay: .85s
}

[data-aos][data-aos][data-aos-duration='900'],body[data-aos-duration='900'] [data-aos] {
    transition-duration: .9s
}

[data-aos][data-aos][data-aos-delay='900'],body[data-aos-delay='900'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='900'].aos-animate,body[data-aos-delay='900'] [data-aos].aos-animate {
    transition-delay: .9s
}

[data-aos][data-aos][data-aos-duration='950'],body[data-aos-duration='950'] [data-aos] {
    transition-duration: .95s
}

[data-aos][data-aos][data-aos-delay='950'],body[data-aos-delay='950'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='950'].aos-animate,body[data-aos-delay='950'] [data-aos].aos-animate {
    transition-delay: .95s
}

[data-aos][data-aos][data-aos-duration='1000'],body[data-aos-duration='1000'] [data-aos] {
    transition-duration: 1s
}

[data-aos][data-aos][data-aos-delay='1000'],body[data-aos-delay='1000'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1000'].aos-animate,body[data-aos-delay='1000'] [data-aos].aos-animate {
    transition-delay: 1s
}

[data-aos][data-aos][data-aos-duration='1050'],body[data-aos-duration='1050'] [data-aos] {
    transition-duration: 1.05s
}

[data-aos][data-aos][data-aos-delay='1050'],body[data-aos-delay='1050'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1050'].aos-animate,body[data-aos-delay='1050'] [data-aos].aos-animate {
    transition-delay: 1.05s
}

[data-aos][data-aos][data-aos-duration='1100'],body[data-aos-duration='1100'] [data-aos] {
    transition-duration: 1.1s
}

[data-aos][data-aos][data-aos-delay='1100'],body[data-aos-delay='1100'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1100'].aos-animate,body[data-aos-delay='1100'] [data-aos].aos-animate {
    transition-delay: 1.1s
}

[data-aos][data-aos][data-aos-duration='1150'],body[data-aos-duration='1150'] [data-aos] {
    transition-duration: 1.15s
}

[data-aos][data-aos][data-aos-delay='1150'],body[data-aos-delay='1150'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1150'].aos-animate,body[data-aos-delay='1150'] [data-aos].aos-animate {
    transition-delay: 1.15s
}

[data-aos][data-aos][data-aos-duration='1200'],body[data-aos-duration='1200'] [data-aos] {
    transition-duration: 1.2s
}

[data-aos][data-aos][data-aos-delay='1200'],body[data-aos-delay='1200'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1200'].aos-animate,body[data-aos-delay='1200'] [data-aos].aos-animate {
    transition-delay: 1.2s
}

[data-aos][data-aos][data-aos-duration='1250'],body[data-aos-duration='1250'] [data-aos] {
    transition-duration: 1.25s
}

[data-aos][data-aos][data-aos-delay='1250'],body[data-aos-delay='1250'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1250'].aos-animate,body[data-aos-delay='1250'] [data-aos].aos-animate {
    transition-delay: 1.25s
}

[data-aos][data-aos][data-aos-duration='1300'],body[data-aos-duration='1300'] [data-aos] {
    transition-duration: 1.3s
}

[data-aos][data-aos][data-aos-delay='1300'],body[data-aos-delay='1300'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1300'].aos-animate,body[data-aos-delay='1300'] [data-aos].aos-animate {
    transition-delay: 1.3s
}

[data-aos][data-aos][data-aos-duration='1350'],body[data-aos-duration='1350'] [data-aos] {
    transition-duration: 1.35s
}

[data-aos][data-aos][data-aos-delay='1350'],body[data-aos-delay='1350'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1350'].aos-animate,body[data-aos-delay='1350'] [data-aos].aos-animate {
    transition-delay: 1.35s
}

[data-aos][data-aos][data-aos-duration='1400'],body[data-aos-duration='1400'] [data-aos] {
    transition-duration: 1.4s
}

[data-aos][data-aos][data-aos-delay='1400'],body[data-aos-delay='1400'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1400'].aos-animate,body[data-aos-delay='1400'] [data-aos].aos-animate {
    transition-delay: 1.4s
}

[data-aos][data-aos][data-aos-duration='1450'],body[data-aos-duration='1450'] [data-aos] {
    transition-duration: 1.45s
}

[data-aos][data-aos][data-aos-delay='1450'],body[data-aos-delay='1450'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1450'].aos-animate,body[data-aos-delay='1450'] [data-aos].aos-animate {
    transition-delay: 1.45s
}

[data-aos][data-aos][data-aos-duration='1500'],body[data-aos-duration='1500'] [data-aos] {
    transition-duration: 1.5s
}

[data-aos][data-aos][data-aos-delay='1500'],body[data-aos-delay='1500'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1500'].aos-animate,body[data-aos-delay='1500'] [data-aos].aos-animate {
    transition-delay: 1.5s
}

[data-aos][data-aos][data-aos-duration='1550'],body[data-aos-duration='1550'] [data-aos] {
    transition-duration: 1.55s
}

[data-aos][data-aos][data-aos-delay='1550'],body[data-aos-delay='1550'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1550'].aos-animate,body[data-aos-delay='1550'] [data-aos].aos-animate {
    transition-delay: 1.55s
}

[data-aos][data-aos][data-aos-duration='1600'],body[data-aos-duration='1600'] [data-aos] {
    transition-duration: 1.6s
}

[data-aos][data-aos][data-aos-delay='1600'],body[data-aos-delay='1600'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1600'].aos-animate,body[data-aos-delay='1600'] [data-aos].aos-animate {
    transition-delay: 1.6s
}

[data-aos][data-aos][data-aos-duration='1650'],body[data-aos-duration='1650'] [data-aos] {
    transition-duration: 1.65s
}

[data-aos][data-aos][data-aos-delay='1650'],body[data-aos-delay='1650'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1650'].aos-animate,body[data-aos-delay='1650'] [data-aos].aos-animate {
    transition-delay: 1.65s
}

[data-aos][data-aos][data-aos-duration='1700'],body[data-aos-duration='1700'] [data-aos] {
    transition-duration: 1.7s
}

[data-aos][data-aos][data-aos-delay='1700'],body[data-aos-delay='1700'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1700'].aos-animate,body[data-aos-delay='1700'] [data-aos].aos-animate {
    transition-delay: 1.7s
}

[data-aos][data-aos][data-aos-duration='1750'],body[data-aos-duration='1750'] [data-aos] {
    transition-duration: 1.75s
}

[data-aos][data-aos][data-aos-delay='1750'],body[data-aos-delay='1750'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1750'].aos-animate,body[data-aos-delay='1750'] [data-aos].aos-animate {
    transition-delay: 1.75s
}

[data-aos][data-aos][data-aos-duration='1800'],body[data-aos-duration='1800'] [data-aos] {
    transition-duration: 1.8s
}

[data-aos][data-aos][data-aos-delay='1800'],body[data-aos-delay='1800'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1800'].aos-animate,body[data-aos-delay='1800'] [data-aos].aos-animate {
    transition-delay: 1.8s
}

[data-aos][data-aos][data-aos-duration='1850'],body[data-aos-duration='1850'] [data-aos] {
    transition-duration: 1.85s
}

[data-aos][data-aos][data-aos-delay='1850'],body[data-aos-delay='1850'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1850'].aos-animate,body[data-aos-delay='1850'] [data-aos].aos-animate {
    transition-delay: 1.85s
}

[data-aos][data-aos][data-aos-duration='1900'],body[data-aos-duration='1900'] [data-aos] {
    transition-duration: 1.9s
}

[data-aos][data-aos][data-aos-delay='1900'],body[data-aos-delay='1900'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1900'].aos-animate,body[data-aos-delay='1900'] [data-aos].aos-animate {
    transition-delay: 1.9s
}

[data-aos][data-aos][data-aos-duration='1950'],body[data-aos-duration='1950'] [data-aos] {
    transition-duration: 1.95s
}

[data-aos][data-aos][data-aos-delay='1950'],body[data-aos-delay='1950'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='1950'].aos-animate,body[data-aos-delay='1950'] [data-aos].aos-animate {
    transition-delay: 1.95s
}

[data-aos][data-aos][data-aos-duration='2000'],body[data-aos-duration='2000'] [data-aos] {
    transition-duration: 2s
}

[data-aos][data-aos][data-aos-delay='2000'],body[data-aos-delay='2000'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2000'].aos-animate,body[data-aos-delay='2000'] [data-aos].aos-animate {
    transition-delay: 2s
}

[data-aos][data-aos][data-aos-duration='2050'],body[data-aos-duration='2050'] [data-aos] {
    transition-duration: 2.05s
}

[data-aos][data-aos][data-aos-delay='2050'],body[data-aos-delay='2050'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2050'].aos-animate,body[data-aos-delay='2050'] [data-aos].aos-animate {
    transition-delay: 2.05s
}

[data-aos][data-aos][data-aos-duration='2100'],body[data-aos-duration='2100'] [data-aos] {
    transition-duration: 2.1s
}

[data-aos][data-aos][data-aos-delay='2100'],body[data-aos-delay='2100'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2100'].aos-animate,body[data-aos-delay='2100'] [data-aos].aos-animate {
    transition-delay: 2.1s
}

[data-aos][data-aos][data-aos-duration='2150'],body[data-aos-duration='2150'] [data-aos] {
    transition-duration: 2.15s
}

[data-aos][data-aos][data-aos-delay='2150'],body[data-aos-delay='2150'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2150'].aos-animate,body[data-aos-delay='2150'] [data-aos].aos-animate {
    transition-delay: 2.15s
}

[data-aos][data-aos][data-aos-duration='2200'],body[data-aos-duration='2200'] [data-aos] {
    transition-duration: 2.2s
}

[data-aos][data-aos][data-aos-delay='2200'],body[data-aos-delay='2200'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2200'].aos-animate,body[data-aos-delay='2200'] [data-aos].aos-animate {
    transition-delay: 2.2s
}

[data-aos][data-aos][data-aos-duration='2250'],body[data-aos-duration='2250'] [data-aos] {
    transition-duration: 2.25s
}

[data-aos][data-aos][data-aos-delay='2250'],body[data-aos-delay='2250'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2250'].aos-animate,body[data-aos-delay='2250'] [data-aos].aos-animate {
    transition-delay: 2.25s
}

[data-aos][data-aos][data-aos-duration='2300'],body[data-aos-duration='2300'] [data-aos] {
    transition-duration: 2.3s
}

[data-aos][data-aos][data-aos-delay='2300'],body[data-aos-delay='2300'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2300'].aos-animate,body[data-aos-delay='2300'] [data-aos].aos-animate {
    transition-delay: 2.3s
}

[data-aos][data-aos][data-aos-duration='2350'],body[data-aos-duration='2350'] [data-aos] {
    transition-duration: 2.35s
}

[data-aos][data-aos][data-aos-delay='2350'],body[data-aos-delay='2350'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2350'].aos-animate,body[data-aos-delay='2350'] [data-aos].aos-animate {
    transition-delay: 2.35s
}

[data-aos][data-aos][data-aos-duration='2400'],body[data-aos-duration='2400'] [data-aos] {
    transition-duration: 2.4s
}

[data-aos][data-aos][data-aos-delay='2400'],body[data-aos-delay='2400'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2400'].aos-animate,body[data-aos-delay='2400'] [data-aos].aos-animate {
    transition-delay: 2.4s
}

[data-aos][data-aos][data-aos-duration='2450'],body[data-aos-duration='2450'] [data-aos] {
    transition-duration: 2.45s
}

[data-aos][data-aos][data-aos-delay='2450'],body[data-aos-delay='2450'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2450'].aos-animate,body[data-aos-delay='2450'] [data-aos].aos-animate {
    transition-delay: 2.45s
}

[data-aos][data-aos][data-aos-duration='2500'],body[data-aos-duration='2500'] [data-aos] {
    transition-duration: 2.5s
}

[data-aos][data-aos][data-aos-delay='2500'],body[data-aos-delay='2500'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2500'].aos-animate,body[data-aos-delay='2500'] [data-aos].aos-animate {
    transition-delay: 2.5s
}

[data-aos][data-aos][data-aos-duration='2550'],body[data-aos-duration='2550'] [data-aos] {
    transition-duration: 2.55s
}

[data-aos][data-aos][data-aos-delay='2550'],body[data-aos-delay='2550'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2550'].aos-animate,body[data-aos-delay='2550'] [data-aos].aos-animate {
    transition-delay: 2.55s
}

[data-aos][data-aos][data-aos-duration='2600'],body[data-aos-duration='2600'] [data-aos] {
    transition-duration: 2.6s
}

[data-aos][data-aos][data-aos-delay='2600'],body[data-aos-delay='2600'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2600'].aos-animate,body[data-aos-delay='2600'] [data-aos].aos-animate {
    transition-delay: 2.6s
}

[data-aos][data-aos][data-aos-duration='2650'],body[data-aos-duration='2650'] [data-aos] {
    transition-duration: 2.65s
}

[data-aos][data-aos][data-aos-delay='2650'],body[data-aos-delay='2650'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2650'].aos-animate,body[data-aos-delay='2650'] [data-aos].aos-animate {
    transition-delay: 2.65s
}

[data-aos][data-aos][data-aos-duration='2700'],body[data-aos-duration='2700'] [data-aos] {
    transition-duration: 2.7s
}

[data-aos][data-aos][data-aos-delay='2700'],body[data-aos-delay='2700'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2700'].aos-animate,body[data-aos-delay='2700'] [data-aos].aos-animate {
    transition-delay: 2.7s
}

[data-aos][data-aos][data-aos-duration='2750'],body[data-aos-duration='2750'] [data-aos] {
    transition-duration: 2.75s
}

[data-aos][data-aos][data-aos-delay='2750'],body[data-aos-delay='2750'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2750'].aos-animate,body[data-aos-delay='2750'] [data-aos].aos-animate {
    transition-delay: 2.75s
}

[data-aos][data-aos][data-aos-duration='2800'],body[data-aos-duration='2800'] [data-aos] {
    transition-duration: 2.8s
}

[data-aos][data-aos][data-aos-delay='2800'],body[data-aos-delay='2800'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2800'].aos-animate,body[data-aos-delay='2800'] [data-aos].aos-animate {
    transition-delay: 2.8s
}

[data-aos][data-aos][data-aos-duration='2850'],body[data-aos-duration='2850'] [data-aos] {
    transition-duration: 2.85s
}

[data-aos][data-aos][data-aos-delay='2850'],body[data-aos-delay='2850'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2850'].aos-animate,body[data-aos-delay='2850'] [data-aos].aos-animate {
    transition-delay: 2.85s
}

[data-aos][data-aos][data-aos-duration='2900'],body[data-aos-duration='2900'] [data-aos] {
    transition-duration: 2.9s
}

[data-aos][data-aos][data-aos-delay='2900'],body[data-aos-delay='2900'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2900'].aos-animate,body[data-aos-delay='2900'] [data-aos].aos-animate {
    transition-delay: 2.9s
}

[data-aos][data-aos][data-aos-duration='2950'],body[data-aos-duration='2950'] [data-aos] {
    transition-duration: 2.95s
}

[data-aos][data-aos][data-aos-delay='2950'],body[data-aos-delay='2950'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='2950'].aos-animate,body[data-aos-delay='2950'] [data-aos].aos-animate {
    transition-delay: 2.95s
}

[data-aos][data-aos][data-aos-duration='3000'],body[data-aos-duration='3000'] [data-aos] {
    transition-duration: 3s
}

[data-aos][data-aos][data-aos-delay='3000'],body[data-aos-delay='3000'] [data-aos] {
    transition-delay: 0
}

[data-aos][data-aos][data-aos-delay='3000'].aos-animate,body[data-aos-delay='3000'] [data-aos].aos-animate {
    transition-delay: 3s
}

[data-aos][data-aos][data-aos-easing=linear],body[data-aos-easing=linear] [data-aos] {
    transition-timing-function: cubic-bezier(.25,.25,.75,.75)
}

[data-aos][data-aos][data-aos-easing=ease],body[data-aos-easing=ease] [data-aos] {
    transition-timing-function: ease
}

[data-aos][data-aos][data-aos-easing=ease-in],body[data-aos-easing=ease-in] [data-aos] {
    transition-timing-function: ease-in
}

[data-aos][data-aos][data-aos-easing=ease-out],body[data-aos-easing=ease-out] [data-aos] {
    transition-timing-function: ease-out
}

[data-aos][data-aos][data-aos-easing=ease-in-out],body[data-aos-easing=ease-in-out] [data-aos] {
    transition-timing-function: ease-in-out
}

[data-aos][data-aos][data-aos-easing=ease-in-back],body[data-aos-easing=ease-in-back] [data-aos] {
    transition-timing-function: cubic-bezier(.6,-.28,.735,.045)
}

[data-aos][data-aos][data-aos-easing=ease-out-back],body[data-aos-easing=ease-out-back] [data-aos] {
    transition-timing-function: cubic-bezier(.175,.885,.32,1.275)
}

[data-aos][data-aos][data-aos-easing=ease-in-out-back],body[data-aos-easing=ease-in-out-back] [data-aos] {
    transition-timing-function: cubic-bezier(.68,-.55,.265,1.55)
}

[data-aos][data-aos][data-aos-easing=ease-in-sine],body[data-aos-easing=ease-in-sine] [data-aos] {
    transition-timing-function: cubic-bezier(.47,0,.745,.715)
}

[data-aos][data-aos][data-aos-easing=ease-out-sine],body[data-aos-easing=ease-out-sine] [data-aos] {
    transition-timing-function: cubic-bezier(.39,.575,.565,1)
}

[data-aos][data-aos][data-aos-easing=ease-in-out-sine],body[data-aos-easing=ease-in-out-sine] [data-aos] {
    transition-timing-function: cubic-bezier(.445,.05,.55,.95)
}

[data-aos][data-aos][data-aos-easing=ease-in-quad],body[data-aos-easing=ease-in-quad] [data-aos] {
    transition-timing-function: cubic-bezier(.55,.085,.68,.53)
}

[data-aos][data-aos][data-aos-easing=ease-out-quad],body[data-aos-easing=ease-out-quad] [data-aos] {
    transition-timing-function: cubic-bezier(.25,.46,.45,.94)
}

[data-aos][data-aos][data-aos-easing=ease-in-out-quad],body[data-aos-easing=ease-in-out-quad] [data-aos] {
    transition-timing-function: cubic-bezier(.455,.03,.515,.955)
}

[data-aos][data-aos][data-aos-easing=ease-in-cubic],body[data-aos-easing=ease-in-cubic] [data-aos] {
    transition-timing-function: cubic-bezier(.55,.085,.68,.53)
}

[data-aos][data-aos][data-aos-easing=ease-out-cubic],body[data-aos-easing=ease-out-cubic] [data-aos] {
    transition-timing-function: cubic-bezier(.25,.46,.45,.94)
}

[data-aos][data-aos][data-aos-easing=ease-in-out-cubic],body[data-aos-easing=ease-in-out-cubic] [data-aos] {
    transition-timing-function: cubic-bezier(.455,.03,.515,.955)
}

[data-aos][data-aos][data-aos-easing=ease-in-quart],body[data-aos-easing=ease-in-quart] [data-aos] {
    transition-timing-function: cubic-bezier(.55,.085,.68,.53)
}

[data-aos][data-aos][data-aos-easing=ease-out-quart],body[data-aos-easing=ease-out-quart] [data-aos] {
    transition-timing-function: cubic-bezier(.25,.46,.45,.94)
}

[data-aos][data-aos][data-aos-easing=ease-in-out-quart],body[data-aos-easing=ease-in-out-quart] [data-aos] {
    transition-timing-function: cubic-bezier(.455,.03,.515,.955)
}

[data-aos^=fade][data-aos^=fade] {
    opacity: 0;
    transition-property: opacity,transform
}

[data-aos^=fade][data-aos^=fade].aos-animate {
    opacity: 1;
    transform: translate(0)
}

[data-aos=fade-up] {
    transform: translateY(100px)
}

[data-aos=fade-down] {
    transform: translateY(-100px)
}

[data-aos=fade-right] {
    transform: translate(-100px)
}

[data-aos=fade-left] {
    transform: translate(100px)
}

[data-aos=fade-up-right] {
    transform: translate(-100px,100px)
}

[data-aos=fade-up-left] {
    transform: translate(100px,100px)
}

[data-aos=fade-down-right] {
    transform: translate(-100px,-100px)
}

[data-aos=fade-down-left] {
    transform: translate(100px,-100px)
}

[data-aos^=zoom][data-aos^=zoom] {
    opacity: 0;
    transition-property: opacity,transform
}

[data-aos^=zoom][data-aos^=zoom].aos-animate {
    opacity: 1;
    transform: translate(0) scale(1)
}

[data-aos=zoom-in] {
    transform: scale(.6)
}

[data-aos=zoom-in-up] {
    transform: translateY(100px) scale(.6)
}

[data-aos=zoom-in-down] {
    transform: translateY(-100px) scale(.6)
}

[data-aos=zoom-in-right] {
    transform: translate(-100px) scale(.6)
}

[data-aos=zoom-in-left] {
    transform: translate(100px) scale(.6)
}

[data-aos=zoom-out] {
    transform: scale(1.2)
}

[data-aos=zoom-out-up] {
    transform: translateY(100px) scale(1.2)
}

[data-aos=zoom-out-down] {
    transform: translateY(-100px) scale(1.2)
}

[data-aos=zoom-out-right] {
    transform: translate(-100px) scale(1.2)
}

[data-aos=zoom-out-left] {
    transform: translate(100px) scale(1.2)
}

[data-aos^=slide][data-aos^=slide] {
    transition-property: transform
}

[data-aos^=slide][data-aos^=slide].aos-animate {
    transform: translate(0)
}

[data-aos=slide-up] {
    transform: translateY(100%)
}

[data-aos=slide-down] {
    transform: translateY(-100%)
}

[data-aos=slide-right] {
    transform: translateX(-100%)
}

[data-aos=slide-left] {
    transform: translateX(100%)
}

[data-aos^=flip][data-aos^=flip] {
    backface-visibility: hidden;
    transition-property: transform
}

[data-aos=flip-left] {
    transform: perspective(2500px) rotateY(-100deg)
}

[data-aos=flip-left].aos-animate {
    transform: perspective(2500px) rotateY(0)
}

[data-aos=flip-right] {
    transform: perspective(2500px) rotateY(100deg)
}

[data-aos=flip-right].aos-animate {
    transform: perspective(2500px) rotateY(0)
}

[data-aos=flip-up] {
    transform: perspective(2500px) rotateX(-100deg)
}

[data-aos=flip-up].aos-animate {
    transform: perspective(2500px) rotateX(0)
}

[data-aos=flip-down] {
    transform: perspective(2500px) rotateX(100deg)
}

[data-aos=flip-down].aos-animate {
    transform: perspective(2500px) rotateX(0)
}

.slick-slider {
    position: relative;
    display: block;
    box-sizing: border-box;
    -webkit-touch-callout: none;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    -ms-touch-action: pan-y;
    touch-action: pan-y;
    -webkit-tap-highlight-color: transparent
}

.slick-list {
    position: relative;
    overflow: hidden;
    display: block;
    margin: 0;
    padding: 0
}

.slick-list:focus {
    outline: 0
}

.slick-list.dragging {
    cursor: pointer;
    cursor: hand
}

.slick-slider .slick-list,.slick-slider .slick-track {
    -webkit-transform: translate3d(0,0,0);
    -moz-transform: translate3d(0,0,0);
    -ms-transform: translate3d(0,0,0);
    -o-transform: translate3d(0,0,0);
    transform: translate3d(0,0,0)
}

.slick-track {
    position: relative;
    left: 0;
    top: 0;
    display: block
}

.slick-track:after,.slick-track:before {
    content: "";
    display: table
}

.slick-track:after {
    clear: both
}

.slick-loading .slick-track {
    visibility: hidden
}

.slick-slide {
    float: left;
    height: 100%;
    min-height: 1px;
    display: none
}

[dir=rtl] .slick-slide {
    float: right
}

.slick-slide img {
    display: block
}

.slick-slide.slick-loading img {
    display: none
}

.slick-slide.dragging img {
    pointer-events: none
}

.slick-initialized .slick-slide {
    display: block
}

.slick-loading .slick-slide {
    visibility: hidden
}

.slick-vertical .slick-slide {
    display: block;
    height: auto;
    border: 1px solid transparent
}

.slick-arrow.slick-hidden {
    display: none
}

.lity {
    z-index: 9990;
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    white-space: nowrap;
    background: #151515;
    background: #151515;
    outline: 0!important;
    opacity: 0;
    -webkit-transition: opacity .3s ease;
    -o-transition: opacity .3s ease;
    transition: opacity .3s ease
}

.lity.lity-opened {
    opacity: 1
}

.lity.lity-closed {
    opacity: 0
}

.lity * {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box
}

.lity-wrap {
    z-index: 9990;
    position: fixed;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    text-align: center;
    outline: 0!important
}

.lity-wrap:before {
    content: '';
    display: inline-block;
    height: 100%;
    vertical-align: middle;
    margin-right: -.25em
}

.lity-loader {
    z-index: 9991;
    color: #333;
    position: absolute;
    top: 50%;
    margin-top: -.8em;
    width: 100%;
    text-align: center;
    font-size: 14px;
    font-family: Arial,Helvetica,sans-serif;
    opacity: 0;
    -webkit-transition: opacity .3s ease;
    -o-transition: opacity .3s ease;
    transition: opacity .3s ease
}

.lity-loading .lity-loader {
    opacity: 1
}

.lity-container {
    z-index: 9992;
    position: relative;
    text-align: left;
    vertical-align: middle;
    display: inline-block;
    white-space: normal;
    max-width: 100%;
    max-height: 100%;
    outline: 0!important
}

.lity-content {
    z-index: 9993;
    width: 100%;
    -webkit-transform: scale(1);
    -ms-transform: scale(1);
    -o-transform: scale(1);
    transform: scale(1);
    -webkit-transition: -webkit-transform .3s ease;
    -o-transition: -o-transform .3s ease;
    transition: transform .3s ease
}

.lity-closed .lity-content,.lity-loading .lity-content {
    -webkit-transform: scale(.8);
    -ms-transform: scale(.8);
    -o-transform: scale(.8);
    transform: scale(.8)
}

.lity-content:after {
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    bottom: 0;
    display: block;
    right: 0;
    width: auto;
    height: auto;
    z-index: -1
}

.lity-close {
    z-index: 9994;
    width: 42px;
    height: 42px;
    position: fixed;
    text-align: center!important;
    right: 20px;
    top: 20px;
    -webkit-appearance: none;
    cursor: pointer;
    text-decoration: none;
    text-align: center;
    padding: 0;
    margin: 0;
    color: #fff;
    font-style: normal;
    font-size: 30px;
    font-family: Arial,sans-serif;
    line-height: 42px;
    border: 0;
    background: 0 0;
    outline: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
    font: 0/0 a;
    text-shadow: none;
    color: transparent;
    border-radius: 50%
}

.lity-close::after,.lity-close::before {
    display: block;
    content: "";
    height: 20px;
    width: 2px;
    background-color: #fff;
    position: absolute;
    top: 11px;
    left: 20px
}

.lity-close::before {
    -webkit-transform: rotate(-45deg);
    -ms-transform: rotate(-45deg);
    transform: rotate(-45deg)
}

.lity-close::after {
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    transform: rotate(45deg)
}

.lity-close::-moz-focus-inner {
    border: 0;
    padding: 0
}

.lity-close:active,.lity-close:focus,.lity-close:hover,.lity-close:visited {
    text-decoration: none;
    text-align: center;
    padding: 0;
    color: #fff;
    font-style: normal;
    font-size: 30px;
    font-family: Arial,sans-serif;
    line-height: 36px;
    border: 0;
    background: 0 0;
    outline: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
    font: 0/0 a;
    text-shadow: none;
    color: transparent
}

.lity-close:active::after,.lity-close:active::before,.lity-close:focus::after,.lity-close:focus::before,.lity-close:hover::after,.lity-close:hover::before,.lity-close:visited::after,.lity-close:visited::before {
    background-color: #f26522
}

.lity-image img {
    max-width: 100%;
    display: block;
    line-height: 0;
    border: 0
}

.lity-iframe .lity-container {
    width: 100%;
    max-width: 964px
}

.lity-iframe-container {
    width: 100%;
    height: 0;
    padding-top: 56.25%;
    overflow: auto;
    pointer-events: auto;
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    -webkit-overflow-scrolling: touch
}

.lity-iframe-container iframe {
    position: absolute;
    display: block;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #000
}

.lity-hide {
    display: none
}

.pswp {
    display: none;
    position: absolute;
    width: 100%;
    height: 100%;
    left: 0;
    top: 0;
    overflow: hidden;
    -ms-touch-action: none;
    touch-action: none;
    z-index: 1500;
    -webkit-text-size-adjust: 100%;
    -webkit-backface-visibility: hidden;
    outline: 0
}

.pswp * {
    -webkit-box-sizing: border-box;
    box-sizing: border-box
}

.pswp img {
    max-width: none
}

.pswp--animate_opacity {
    opacity: .001;
    will-change: opacity;
    -webkit-transition: opacity 333ms cubic-bezier(.4,0,.22,1);
    transition: opacity 333ms cubic-bezier(.4,0,.22,1)
}

.pswp--open {
    display: block
}

.pswp--zoom-allowed .pswp__img {
    cursor: -webkit-zoom-in;
    cursor: -moz-zoom-in;
    cursor: zoom-in
}

.pswp--zoomed-in .pswp__img {
    cursor: -webkit-grab;
    cursor: -moz-grab;
    cursor: grab
}

.pswp--dragging .pswp__img {
    cursor: -webkit-grabbing;
    cursor: -moz-grabbing;
    cursor: grabbing
}

.pswp__bg {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    background: #000;
    opacity: 0;
    -webkit-transform: translateZ(0);
    transform: translateZ(0);
    -webkit-backface-visibility: hidden;
    will-change: opacity
}

.pswp__scroll-wrap {
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    overflow: hidden
}

.pswp__container,.pswp__zoom-wrap {
    -ms-touch-action: none;
    touch-action: none;
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0
}

.pswp__container,.pswp__img {
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
    -webkit-tap-highlight-color: transparent;
    -webkit-touch-callout: none
}

.pswp__zoom-wrap {
    position: absolute;
    width: 100%;
    -webkit-transform-origin: left top;
    -ms-transform-origin: left top;
    transform-origin: left top;
    -webkit-transition: -webkit-transform 333ms cubic-bezier(.4,0,.22,1);
    transition: transform 333ms cubic-bezier(.4,0,.22,1)
}

.pswp__bg {
    will-change: opacity;
    -webkit-transition: opacity 333ms cubic-bezier(.4,0,.22,1);
    transition: opacity 333ms cubic-bezier(.4,0,.22,1)
}

.pswp--animated-in .pswp__bg,.pswp--animated-in .pswp__zoom-wrap {
    -webkit-transition: none;
    transition: none
}

.pswp__container,.pswp__zoom-wrap {
    -webkit-backface-visibility: hidden
}

.pswp__item {
    position: absolute;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    overflow: hidden
}

.pswp__img {
    position: absolute;
    width: auto;
    height: auto;
    top: 0;
    left: 0
}

.pswp__img--placeholder {
    -webkit-backface-visibility: hidden
}

.pswp__img--placeholder--blank {
    background: #222
}

.pswp--ie .pswp__img {
    width: 100%!important;
    height: auto!important;
    left: 0;
    top: 0
}

.pswp__error-msg {
    position: absolute;
    left: 0;
    top: 50%;
    width: 100%;
    text-align: center;
    font-size: 14px;
    line-height: 16px;
    margin-top: -8px;
    color: #ccc
}

.pswp__error-msg a {
    color: #ccc;
    text-decoration: underline
}

.pswp__button {
    width: 44px;
    height: 44px;
    line-height: 1;
    position: relative;
    background: 0 0;
    cursor: pointer;
    overflow: visible;
    -webkit-appearance: none;
    display: block;
    border: 0;
    padding: 0;
    margin: 0;
    float: right;
    opacity: .6;
    -webkit-transition: opacity .2s;
    transition: opacity .2s;
    -webkit-box-shadow: none;
    box-shadow: none
}

.pswp__button:focus,.pswp__button:hover {
    opacity: 1;
    background-color: transparent
}

.pswp__button:active {
    outline: 0;
    opacity: .9
}

.pswp__button::-moz-focus-inner {
    padding: 0;
    border: 0
}

.pswp__ui--over-close .pswp__button--close {
    opacity: 1
}

.pswp__button,.pswp__button--arrow--left:before,.pswp__button--arrow--right:before {
    background-size: 264px 88px;
    width: 44px;
    height: 44px
}

@media (-webkit-min-device-pixel-ratio: 1.1),(-webkit-min-device-pixel-ratio:1.09375),(min-resolution:105dpi),(min-resolution:1.1dppx) {
    .pswp--svg .pswp__button,.pswp--svg .pswp__button--arrow--left:before,.pswp--svg .pswp__button--arrow--right:before {
    }

    .pswp--svg .pswp__button--arrow--left,.pswp--svg .pswp__button--arrow--right {
        background: 0 0
    }
}

.pswp__button--close {
    background-position: 0 -44px
}

.pswp__button--share {
    background-position: -44px -44px
}

.pswp__button--fs {
    display: none
}

.pswp--supports-fs .pswp__button--fs {
    display: block
}

.pswp--fs .pswp__button--fs {
    background-position: -44px 0
}

.pswp__button--zoom {
    display: none;
    background-position: -88px 0
}

.pswp--zoom-allowed .pswp__button--zoom {
    display: block
}

.pswp--zoomed-in .pswp__button--zoom {
    background-position: -132px 0
}

.pswp--touch .pswp__button--arrow--left,.pswp--touch .pswp__button--arrow--right {
    visibility: hidden
}

.pswp__button--arrow--left,.pswp__button--arrow--right {
    background: 0 0;
    top: 50%;
    margin-top: -22px;
    width: 30px;
    height: 32px;
    position: absolute
}

.pswp__button--arrow--left {
    left: 12px
}

.pswp__button--arrow--right {
    right: 12px
}

.pswp__button--arrow--left:before,.pswp__button--arrow--right:before {
    content: '';
    top: 0;
    background-color: rgba(0,0,0,.3);
    height: 30px;
    width: 32px;
    position: absolute;
    border-radius: 3px
}

.pswp__button--arrow--left:before {
    left: 6px;
    background-position: -138px -44px
}

.pswp__button--arrow--right:before {
    right: 6px;
    background-position: -94px -44px
}

.pswp__counter,.pswp__share-modal {
    -webkit-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none
}

.pswp__share-modal {
    display: block;
    background: rgba(0,0,0,.5);
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    padding: 10px;
    position: absolute;
    z-index: 1600;
    opacity: 0;
    -webkit-transition: opacity .25s ease-out;
    transition: opacity .25s ease-out;
    -webkit-backface-visibility: hidden;
    will-change: opacity
}

.pswp__share-modal--hidden {
    display: none
}

.pswp__share-tooltip {
    z-index: 1620;
    position: absolute;
    background: #fff;
    top: 56px;
    border-radius: 3px;
    display: block;
    width: auto;
    right: 44px;
    -webkit-box-shadow: 0 2px 5px rgba(0,0,0,.25);
    box-shadow: 0 2px 5px rgba(0,0,0,.25);
    -webkit-transform: translateY(6px);
    -ms-transform: translateY(6px);
    transform: translateY(6px);
    -webkit-transition: -webkit-transform .25s;
    transition: transform .25s;
    -webkit-backface-visibility: hidden;
    will-change: transform
}

.pswp__share-tooltip a {
    display: block;
    padding: 9px 15px;
    color: #000;
    text-decoration: none;
    font-size: 13px;
    line-height: 18px
}

.pswp__share-tooltip a:hover {
    text-decoration: none;
    color: #000
}

.pswp__share-tooltip a:first-child {
    border-radius: 3px 3px 0 0
}

.pswp__share-tooltip a:last-child {
    border-radius: 0 0 3px 3px
}

.pswp__share-modal--fade-in {
    opacity: 1
}

.pswp__share-modal--fade-in .pswp__share-tooltip {
    -webkit-transform: translateY(0);
    -ms-transform: translateY(0);
    transform: translateY(0)
}

.pswp--touch .pswp__share-tooltip a {
    padding: 16px 12px
}

a.pswp__share--facebook:before {
    content: '';
    display: block;
    width: 0;
    height: 0;
    position: absolute;
    top: -12px;
    right: 15px;
    border: 6px solid transparent;
    border-bottom-color: #fff;
    -webkit-pointer-events: none;
    -moz-pointer-events: none;
    pointer-events: none
}

a.pswp__share--facebook:hover {
    background: #3e5c9a;
    color: #fff
}

a.pswp__share--facebook:hover:before {
    border-bottom-color: #3e5c9a
}

a.pswp__share--twitter:hover {
    background: #55acee;
    color: #fff
}

a.pswp__share--pinterest:hover {
    background: #ccc;
    color: #ce272d
}

a.pswp__share--download:hover {
    background: #ddd
}

.pswp__counter {
    position: absolute;
    left: 6px;
    top: 0;
    height: 44px;
    font-size: 13px;
    line-height: 44px;
    color: #fff;
    opacity: .75;
    padding: 0 10px
}

.pswp__caption {
    position: absolute;
    left: 0;
    bottom: 0;
    width: 100%;
    min-height: 45px
}

.pswp__caption h4 {
    font-size: 1.8rem;
    line-height: 1.333;
    margin: 0 0 .6rem;
    color: #fff
}

.pswp__caption small {
    font-size: 11px;
    color: rgba(255,255,255,.5)
}

.pswp__caption__center {
    text-align: center;
    max-width: 900px;
    margin: 0 auto;
    font-size: 13px;
    padding: 10px;
    line-height: 20px;
    color: rgba(255,255,255,.5)
}

.pswp__caption--empty {
    display: none
}

.pswp__caption--fake {
    visibility: hidden
}

.pswp__preloader {
    width: 44px;
    height: 44px;
    position: absolute;
    top: 0;
    left: 50%;
    margin-left: -22px;
    opacity: 0;
    -webkit-transition: opacity .25s ease-out;
    transition: opacity .25s ease-out;
    will-change: opacity;
    direction: ltr
}

.pswp__preloader__icn {
    width: 20px;
    height: 20px;
    margin: 12px
}

.pswp__preloader--active {
    opacity: 1
}

.pswp__preloader--active .pswp__preloader__icn {
}

.pswp--css_animation .pswp__preloader--active {
    opacity: 1
}

.pswp--css_animation .pswp__preloader--active .pswp__preloader__icn {
    -webkit-animation: clockwise .5s linear infinite;
    animation: clockwise .5s linear infinite
}

.pswp--css_animation .pswp__preloader--active .pswp__preloader__donut {
    -webkit-animation: donut-rotate 1s cubic-bezier(.4,0,.22,1) infinite;
    animation: donut-rotate 1s cubic-bezier(.4,0,.22,1) infinite
}

.pswp--css_animation .pswp__preloader__icn {
    background: 0 0;
    opacity: .75;
    width: 14px;
    height: 14px;
    position: absolute;
    left: 15px;
    top: 15px;
    margin: 0
}

.pswp--css_animation .pswp__preloader__cut {
    position: relative;
    width: 7px;
    height: 14px;
    overflow: hidden
}

.pswp--css_animation .pswp__preloader__donut {
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    width: 14px;
    height: 14px;
    border: 2px solid #fff;
    border-radius: 50%;
    border-left-color: transparent;
    border-bottom-color: transparent;
    position: absolute;
    top: 0;
    left: 0;
    background: 0 0;
    margin: 0
}

@media screen and (max-width: 1024px) {
    .pswp__preloader {
        position:relative;
        left: auto;
        top: auto;
        margin: 0;
        float: right
    }
}

@-webkit-keyframes clockwise {
    0% {
        -webkit-transform: rotate(0);
        transform: rotate(0)
    }

    100% {
        -webkit-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@keyframes clockwise {
    0% {
        -webkit-transform: rotate(0);
        transform: rotate(0)
    }

    100% {
        -webkit-transform: rotate(360deg);
        transform: rotate(360deg)
    }
}

@-webkit-keyframes donut-rotate {
    0% {
        -webkit-transform: rotate(0);
        transform: rotate(0)
    }

    50% {
        -webkit-transform: rotate(-140deg);
        transform: rotate(-140deg)
    }

    100% {
        -webkit-transform: rotate(0);
        transform: rotate(0)
    }
}

@keyframes donut-rotate {
    0% {
        -webkit-transform: rotate(0);
        transform: rotate(0)
    }

    50% {
        -webkit-transform: rotate(-140deg);
        transform: rotate(-140deg)
    }

    100% {
        -webkit-transform: rotate(0);
        transform: rotate(0)
    }
}

.pswp {
    font-family: Montserrat,sans-serif
}

.pswp__ui {
    -webkit-font-smoothing: auto;
    visibility: visible;
    opacity: 1;
    z-index: 1550
}

.pswp__top-bar {
    position: absolute;
    left: 0;
    top: 0;
    height: 44px;
    width: 100%;
    padding: 0 6px
}

.pswp--has_mouse .pswp__button--arrow--left,.pswp--has_mouse .pswp__button--arrow--right,.pswp__caption,.pswp__top-bar {
    -webkit-backface-visibility: hidden;
    will-change: opacity;
    -webkit-transition: opacity 333ms cubic-bezier(.4,0,.22,1);
    transition: opacity 333ms cubic-bezier(.4,0,.22,1)
}

.pswp--has_mouse .pswp__button--arrow--left,.pswp--has_mouse .pswp__button--arrow--right {
    visibility: visible
}

.pswp__caption,.pswp__top-bar {
    background-color: rgba(0,0,0,.5)
}

.pswp__ui--fit .pswp__caption,.pswp__ui--fit .pswp__top-bar {
    background-color: rgba(0,0,0,.3)
}

.pswp__ui--idle .pswp__top-bar {
    opacity: 0
}

.pswp__ui--idle .pswp__button--arrow--left,.pswp__ui--idle .pswp__button--arrow--right {
    opacity: 0
}

.pswp__ui--hidden .pswp__button--arrow--left,.pswp__ui--hidden .pswp__button--arrow--right,.pswp__ui--hidden .pswp__caption,.pswp__ui--hidden .pswp__top-bar {
    opacity: .001
}

.pswp__ui--one-slide .pswp__button--arrow--left,.pswp__ui--one-slide .pswp__button--arrow--right,.pswp__ui--one-slide .pswp__counter {
    display: none
}

.pswp__element--disabled {
    display: none!important
}

.pswp--minimal--dark .pswp__top-bar {
    background: 0 0
}

.rangeslider,.rangeslider__fill {
    display: block
}

.rangeslider {
    position: relative
}

.rangeslider--horizontal {
    height: 20px;
    width: 100%;
    background: rgba(91,178,177,.3);
    box-shadow: none;
    border-radius: 0
}

.rangeslider--vertical {
    width: 20px;
    min-height: 150px;
    max-height: 100%
}

.rangeslider--disabled {
    opacity: .4
}

.rangeslider__fill {
    background: rgba(91,178,177,.47);
    position: absolute
}

.rangeslider--horizontal .rangeslider__fill {
    top: 0;
    height: 100%
}

.rangeslider--vertical .rangeslider__fill {
    bottom: 0;
    width: 100%
}

.rangeslider__handle {
    background: #dfbf5f;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    width: 80px;
    height: 80px;
    position: absolute;
    background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4gPHN2ZyB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PGRlZnM+PGxpbmVhckdyYWRpZW50IGlkPSJncmFkIiBncmFkaWVudFVuaXRzPSJvYmplY3RCb3VuZGluZ0JveCIgeDE9IjAuNSIgeTE9IjAuMCIgeDI9IjAuNSIgeTI9IjEuMCI+PHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iI2ZmZmZmZiIgc3RvcC1vcGFjaXR5PSIwLjAiLz48c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMwMDAwMDAiIHN0b3Atb3BhY2l0eT0iMC4xIi8+PC9saW5lYXJHcmFkaWVudD48L2RlZnM+PHJlY3QgeD0iMCIgeT0iMCIgd2lkdGg9IjEwMCUiIGhlaWdodD0iMTAwJSIgZmlsbD0idXJsKCNncmFkKSIgLz48L3N2Zz4g);
    background-size: 100%;
    background-image: -webkit-gradient(linear,50% 0,50% 100%,color-stop(0,rgba(255,255,255,0)),color-stop(100%,rgba(0,0,0,.1)));
    background-image: -moz-linear-gradient(rgba(255,255,255,0),rgba(0,0,0,.1));
    background-image: -webkit-linear-gradient(rgba(255,255,255,0),rgba(0,0,0,.1));
    background-image: linear-gradient(rgba(255,255,255,0),rgba(0,0,0,.1));
    -moz-border-radius: 50%;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    color: #fff
}

.rangeslider--active .rangeslider__handle,.rangeslider__handle:active {
    background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4gPHN2ZyB2ZXJzaW9uPSIxLjEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PGRlZnM+PGxpbmVhckdyYWRpZW50IGlkPSJncmFkIiBncmFkaWVudFVuaXRzPSJvYmplY3RCb3VuZGluZ0JveCIgeDE9IjAuNSIgeTE9IjAuMCIgeDI9IjAuNSIgeTI9IjEuMCI+PHN0b3Agb2Zmc2V0PSIwJSIgc3RvcC1jb2xvcj0iIzAwMDAwMCIgc3RvcC1vcGFjaXR5PSIwLjEiLz48c3RvcCBvZmZzZXQ9IjEwMCUiIHN0b3AtY29sb3I9IiMwMDAwMDAiIHN0b3Atb3BhY2l0eT0iMC4xMiIvPjwvbGluZWFyR3JhZGllbnQ+PC9kZWZzPjxyZWN0IHg9IjAiIHk9IjAiIHdpZHRoPSIxMDAlIiBoZWlnaHQ9IjEwMCUiIGZpbGw9InVybCgjZ3JhZCkiIC8+PC9zdmc+IA==);
    background-size: 100%;
    background-image: -webkit-gradient(linear,50% 0,50% 100%,color-stop(0,rgba(0,0,0,.1)),color-stop(100%,rgba(0,0,0,.12)));
    background-image: -moz-linear-gradient(rgba(0,0,0,.1),rgba(0,0,0,.12));
    background-image: -webkit-linear-gradient(rgba(0,0,0,.1),rgba(0,0,0,.12));
    background-image: linear-gradient(rgba(0,0,0,.1),rgba(0,0,0,.12));
    transform: scale(1.1)
}

.rangeslider--horizontal .rangeslider__handle {
    top: -30px;
    touch-action: pan-y;
    -ms-touch-action: pan-y
}

.rangeslider--vertical .rangeslider__handle {
    left: -10px;
    touch-action: pan-x;
    -ms-touch-action: pan-x
}

input[type=range]:focus+.rangeslider .rangeslider__handle {
    -moz-box-shadow: 0 0 8px rgba(255,0,255,.9);
    -webkit-box-shadow: 0 0 8px rgba(255,0,255,.9);
    box-shadow: 0 0 8px rgba(255,0,255,.9)
}

@import url(font-awesome/css/fontawesome-all.css);html {
    font-family: sans-serif;
    line-height: 1.15;
    -ms-text-size-adjust: 100%;
    -webkit-text-size-adjust: 100%
}

body {
    margin: 0
}

article,aside,footer,header,nav,section {
    display: block
}

h1 {
    font-size: 2em;
    margin: .67em 0
}

figcaption,figure,main {
    display: block
}

figure {
    margin: 1em 40px
}

hr {
    box-sizing: content-box;
    height: 0;
    overflow: visible
}

pre {
    font-family: monospace,monospace;
    font-size: 1em
}

a {
    background-color: transparent;
    -webkit-text-decoration-skip: objects
}

a:active,a:hover {
    outline-width: 0
}

abbr[title] {
    border-bottom: none;
    text-decoration: underline;
    text-decoration: underline dotted
}

b,strong {
    font-weight: inherit
}

b,strong {
    font-weight: bolder
}

code,kbd,samp {
    font-family: monospace,monospace;
    font-size: 1em
}

dfn {
    font-style: italic
}

mark {
    background-color: #ff0;
    color: #000
}

small {
    font-size: 80%
}

sub,sup {
    font-size: 75%;
    line-height: 0;
    position: relative;
    vertical-align: baseline
}

sub {
    bottom: -.25em
}

sup {
    top: -.5em
}

audio,video {
    display: inline-block
}

audio:not([controls]) {
    display: none;
    height: 0
}

img {
    border-style: none
}

svg:not(:root) {
    overflow: hidden
}

button,input,optgroup,select,textarea {
    font-family: sans-serif;
    font-size: 100%;
    line-height: 1.15;
    margin: 0
}

button,input {
    overflow: visible
}

button,select {
    text-transform: none
}

[type=reset],[type=submit],button,html [type=button] {
    -webkit-appearance: button
}

[type=button]::-moz-focus-inner,[type=reset]::-moz-focus-inner,[type=submit]::-moz-focus-inner,button::-moz-focus-inner {
    border-style: none;
    padding: 0
}

[type=button]:-moz-focusring,[type=reset]:-moz-focusring,[type=submit]:-moz-focusring,button:-moz-focusring {
    outline: 1px dotted ButtonText
}

fieldset {
    border: 1px solid silver;
    margin: 0 2px;
    padding: .35em .625em .75em
}

legend {
    box-sizing: border-box;
    color: inherit;
    display: table;
    max-width: 100%;
    padding: 0;
    white-space: normal
}

progress {
    display: inline-block;
    vertical-align: baseline
}

textarea {
    overflow: auto
}

[type=checkbox],[type=radio] {
    box-sizing: border-box;
    padding: 0
}

[type=number]::-webkit-inner-spin-button,[type=number]::-webkit-outer-spin-button {
    height: auto
}

[type=search] {
    -webkit-appearance: textfield;
    outline-offset: -2px
}

[type=search]::-webkit-search-cancel-button,[type=search]::-webkit-search-decoration {
    -webkit-appearance: none
}

::-webkit-file-upload-button {
    -webkit-appearance: button;
    font: inherit
}

details,menu {
    display: block
}

summary {
    display: list-item
}

canvas {
    display: inline-block
}

template {
    display: none
}

[hidden] {
    display: none
}

html {
    font-size: 62.5%;
    box-sizing: border-box
}

*,::after,::before {
    box-sizing: inherit
}

body {
    font-weight: 400;
    line-height: 1;
    word-wrap: break-word;
    text-rendering: optimizeLegibility;
    -webkit-overflow-scrolling: touch;
    -webkit-text-size-adjust: none
}

body,button,input {
    -moz-osx-font-smoothing: grayscale;
    -webkit-font-smoothing: antialiased
}

img,video {
    max-width: 100%;
    height: auto
}

blockquote,dd,div,dl,dt,form,h1,h2,h3,h4,h5,h6,li,ol,p,pre,td,th,ul {
    margin: 0;
    padding: 0
}

h1,h2,h3,h4,h5,h6 {
    -webkit-font-smoothing: auto;
    -webkit-font-smoothing: antialiased;
    -webkit-font-variant-ligatures: common-ligatures;
    -moz-font-variant-ligatures: common-ligatures;
    font-variant-ligatures: common-ligatures;
    text-rendering: optimizeLegibility
}

em,i {
    font-style: italic;
    line-height: inherit
}

b,strong {
    font-weight: 700;
    line-height: inherit
}

small {
    font-size: 60%;
    line-height: inherit
}

ol,ul {
    list-style: none
}

li {
    display: block
}

a {
    text-decoration: none;
    line-height: inherit
}

a img {
    border: none
}

fieldset {
    margin: 0;
    padding: 0
}

input[type=email],input[type=number],input[type=password],input[type=search],input[type=tel],input[type=text],input[type=url],textarea {
    -webkit-appearance: none;
    -moz-appearance: none;
    -ms-appearance: none;
    -o-appearance: none;
    appearance: none
}

.row {
    width: 89%;
    max-width: 1200px;
    margin: 0 auto
}

.row:after {
    content: "";
    display: table;
    clear: both
}

.row .row {
    width: auto;
    max-width: none;
    margin-left: -20px;
    margin-right: -20px
}

[class*=col-] {
    float: left;
    padding: 0 20px
}

[class*=col-]+[class*=col-].end {
    float: right
}

.collapse>[class*=col-],[class*=col-].collapse {
    padding: 0
}

.col-one {
    width: 8.33333%
}

.col-1-6,.col-two {
    width: 16.66667%
}

.col-1-4,.col-three {
    width: 25%
}

.col-1-3,.col-four {
    width: 33.33333%
}

.col-five {
    width: 41.66667%
}

.col-1-2,.col-six {
    width: 50%
}

.col-seven {
    width: 58.33333%
}

.col-2-3,.col-eight {
    width: 66.66667%
}

.col-3-4,.col-nine {
    width: 75%
}

.col-5-6,.col-ten {
    width: 83.33333%
}

.col-eleven {
    width: 91.66667%
}

.col-full,.col-twelve {
    width: 100%
}

@media only screen and (max-width: 1200px) {
    .row .row {
        margin-left:-15px;
        margin-right: -15px
    }

    [class*=col-] {
        padding: 0 15px
    }

    .md-1-6,.md-two {
        width: 16.66667%
    }

    .md-one {
        width: 8.33333%
    }

    .md-1-4,.md-three {
        width: 25%
    }

    .md-1-3,.md-four {
        width: 33.33333%
    }

    .md-five {
        width: 41.66667%
    }

    .md-1-2,.md-six {
        width: 50%
    }

    .md-seven {
        width: 58.33333%
    }

    .md-2-3,.md-eight {
        width: 66.66667%
    }

    .md-3-4,.md-nine {
        width: 75%
    }

    .md-5-6,.md-ten {
        width: 83.33333%
    }

    .md-eleven {
        width: 91.66667%
    }

    .md-full,.md-twelve {
        width: 100%
    }
}

@media only screen and (max-width: 800px) {
    .row {
        width:90%
    }

    .tab-1-4 {
        width: 25%
    }

    .tab-1-3 {
        width: 33.33333%
    }

    .tab-1-2 {
        width: 50%
    }

    .tab-2-3 {
        width: 66.66667%
    }

    .tab-3-4 {
        width: 75%
    }

    .tab-full {
        width: 100%
    }

    .hide-on-tablet {
        display: none
    }
}

@media only screen and (max-width: 600px) {
    .row {
        width:auto;
        padding-left: 25px;
        padding-right: 25px
    }

    .row .row {
        margin-left: -10px;
        margin-right: -10px;
        padding-left: 0;
        padding-right: 0
    }

    [class*=col-] {
        padding: 0 10px
    }

    .mob-1-4 {
        width: 25%
    }

    .mob-1-3 {
        width: 33.33333%
    }

    .mob-1-2 {
        width: 50%
    }

    .mob-2-3 {
        width: 66.66667%
    }

    .mob-3-4 {
        width: 75%
    }

    .mob-full {
        width: 100%
    }

    .hide-on-mobile {
        display: none
    }
}

@media only screen and (max-width: 400px) {
    .row .row {
        margin-left:0;
        margin-right: 0
    }

    [class*=col-]:not(.col-block) {
        width: 100%!important;
        float: none!important;
        clear: both!important;
        margin-left: 0;
        margin-right: 0;
        padding: 0!important
    }

    [class*=col-]+[class*=col-].end {
        float: none
    }

    .stack .col-block {
        width: 100%!important;
        float: none!important;
        clear: both!important;
        margin-left: 0;
        margin-right: 0
    }
}

[class*=block-]:after {
    content: "";
    display: table;
    clear: both
}

.block-1-6 .col-block {
    width: 16.66667%
}

.block-1-5 .col-block {
    width: 20%
}

.block-1-4 .col-block {
    width: 25%
}

.block-1-3 .col-block {
    width: 33.33333%
}

.block-1-2 .col-block {
    width: 50%
}

.block-1-2 .col-block:nth-child(2n+1),.block-1-3 .col-block:nth-child(3n+1),.block-1-4 .col-block:nth-child(4n+1),.block-1-5 .col-block:nth-child(5n+1),.block-1-6 .col-block:nth-child(6n+1) {
    clear: both
}

@media only screen and (max-width: 1200px) {
    .block-m-1-6 .col-block {
        width:16.66667%
    }

    .block-m-1-5 .col-block {
        width: 20%
    }

    .block-m-1-4 .col-block {
        width: 25%
    }

    .block-m-1-3 .col-block {
        width: 33.33333%
    }

    .block-m-1-2 .col-block {
        width: 50%
    }

    .block-m-full .col-block {
        width: 100%;
        clear: both
    }

    [class*=block-m-] .col-block:nth-child(n) {
        clear: none
    }

    .block-m-1-2 .col-block:nth-child(2n+1),.block-m-1-3 .col-block:nth-child(3n+1),.block-m-1-4 .col-block:nth-child(4n+1),.block-m-1-5 .col-block:nth-child(5n+1),.block-m-1-6 .col-block:nth-child(6n+1) {
        clear: both
    }
}

@media only screen and (max-width: 800px) {
    .block-tab-1-6 .col-block {
        width:16.66667%
    }

    .block-tab-1-5 .col-block {
        width: 20%
    }

    .block-tab-1-4 .col-block {
        width: 25%
    }

    .block-tab-1-3 .col-block {
        width: 33.33333%
    }

    .block-tab-1-2 .col-block {
        width: 50%
    }

    .block-tab-full .col-block {
        width: 100%;
        clear: both
    }

    [class*=block-tab-] .col-block:nth-child(n) {
        clear: none
    }

    .block-tab-1-2 .col-block:nth-child(2n+1),.block-tab-1-3 .col-block:nth-child(3n+1),.block-tab-1-4 .col-block:nth-child(4n+1),.block-tab-1-5 .col-block:nth-child(5n+1),.block-tab-1-6 .col-block:nth-child(6n+1) {
        clear: both
    }
}

@media only screen and (max-width: 600px) {
    .block-mob-1-6 .col-block {
        width:16.66667%
    }

    .block-mob-1-5 .col-block {
        width: 20%
    }

    .block-mob-1-4 .col-block {
        width: 25%
    }

    .block-mob-1-3 .col-block {
        width: 33.33333%
    }

    .block-mob-1-2 .col-block {
        width: 50%
    }

    .block-mob-full .col-block {
        width: 100%;
        clear: both
    }

    [class*=block-mob-] .col-block:nth-child(n) {
        clear: none
    }

    .block-mob-1-2 .col-block:nth-child(2n+1),.block-mob-1-3 .col-block:nth-child(3n+1),.block-mob-1-4 .col-block:nth-child(4n+1),.block-mob-1-5 .col-block:nth-child(5n+1),.block-mob-1-6 .col-block:nth-child(6n+1) {
        clear: both
    }
}

.group:after {
    content: "";
    display: table;
    clear: both
}

.is-hidden {
    display: none
}

.is-invisible {
    visibility: hidden
}

.antialiased {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale
}

.overflow-hidden {
    overflow: hidden
}

.remove-bottom {
    margin-bottom: 0
}

.half-bottom {
    margin-bottom: 1.5rem!important
}

.add-bottom {
    margin-bottom: 3rem!important
}

.no-border {
    border: none
}

.full-width {
    width: 100%
}

.text-center {
    text-align: center
}

.text-left {
    text-align: left
}

.text-right {
    text-align: right
}

.pull-left {
    float: left
}

.pull-right {
    float: right
}

.align-center {
    margin-left: auto;
    margin-right: auto;
    text-align: center
}

/*! Generated by Font Squirrel (https://www.fontsquirrel.com) on July 26, 2018 */

html {
    font-size: 10px
}

@media only screen and (max-width: 400px) {
    html {
        font-size:9.411764705882353px
    }
}

body,html {
    height: 100%
}

body {
    background: #151515;
    font-family: Roboto,sans-serif;
    font-size: 1.7rem;
    font-style: normal;
    font-weight: 400;
    line-height: 1.941;
    color: #595959;
    margin: 0;
    padding: 0
}

a {
    color: #dfbf5f;
    -webkit-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out
}

a:active,a:focus,a:hover {
    color: #035d5c
}

a:active,a:hover {
    outline: 0
}

.h1,.h2,.h3,.h4,.h5,.h6,h1,h2,h3,h4,h5,h6 {
    font-family: proxima_nova,sans-serif;
    font-weight: 600;
    color: #000;
    text-rendering: optimizeLegibility
}

.h1,.h2,.h3,.h4,h1,h2,h3,h4 {
    margin-top: 6rem;
    margin-bottom: 1.8rem
}

@media only screen and (max-width: 600px) {
    .h1,.h2,.h3,.h4,h1,h2,h3,h4 {
        margin-top:5.1rem
    }
}

.h5,.h6,h5,h6 {
    margin-top: 4.2rem;
    margin-bottom: 1.5rem
}

@media only screen and (max-width: 600px) {
    .h5,.h6,h5,h6 {
        margin-top:3.6rem;
        margin-bottom: .9rem
    }
}

.h1,h1 {
    font-size: 3.6rem;
    line-height: 1.25;
    letter-spacing: -.1rem
}

@media only screen and (max-width: 600px) {
    .h1,h1 {
        font-size:3.3rem;
        letter-spacing: -.07rem
    }
}

.h2,h2 {
    font-size: 3rem;
    line-height: 1.3
}

.h3,h3 {
    font-size: 2.4rem;
    line-height: 1.25
}

.h4,h4 {
    font-size: 2.1rem;
    line-height: 1.286
}

.h5,h5 {
    font-size: 1.8rem;
    line-height: 1.333
}

.h6,h6 {
    font-size: 1.6rem;
    line-height: 1.3125;
    text-transform: uppercase;
    letter-spacing: .16rem
}

p img {
    margin: 0
}

p.lead {
    font-family: Roboto,sans-serif;
    font-weight: 300;
    font-size: 2.5rem;
    line-height: 4.5rem;
    margin-bottom: 4.8rem;
    color: #8c8c8c;
    text-align: justify;
}

p.lead.lead--bottom {
    margin-top: 4.8rem;
    margin-bottom: 0
}

@media only screen and (max-width: 1200px) {
    p.lead {
        font-size:2.2rem
    }
}

@media only screen and (max-width: 1000px) {
    p.lead {
        font-size:2.1rem
    }
}

@media only screen and (max-width: 800px) {
    p.lead {
        font-size:2rem
    }
}

b,em,i,strong {
    font-size: inherit;
    line-height: inherit
}

em,i {
    font-family: proxima_nova,serif;
    font-style: italic
}

b,strong {
    font-family: proxima_nova,serif;
    font-weight: 700
}

small {
    font-size: 1.2rem;
    line-height: inherit
}

blockquote {
    margin: 3.9rem 0;
    padding-left: 4.5rem;
    position: relative
}

blockquote:before {
    content: "\201C";
    font-size: 10rem;
    line-height: 0;
    margin: 0;
    color: rgba(0,0,0,.25);
    font-family: arial,sans-serif;
    position: absolute;
    top: 3.6rem;
    left: 0
}

blockquote p {
    font-family: proxima_nova,serif;
    padding: 0;
    font-size: 2.1rem;
    line-height: 1.857;
    color: #151515
}

blockquote cite {
    display: block;
    font-family: proxima_nova,sans-serif;
    font-size: 1.4rem;
    font-style: normal;
    line-height: 1.5
}

blockquote cite:before {
    content: "\2014 \0020"
}

blockquote cite a,blockquote cite a:visited {
    color: rgba(13,13,13,.65);
    border: none
}

abbr {
    font-family: proxima_nova,serif;
    font-weight: 700;
    font-variant: small-caps;
    text-transform: lowercase;
    letter-spacing: .05rem;
    color: rgba(13,13,13,.65)
}

code,kbd,pre,samp,var {
    font-family: Consolas,"Andale Mono",Courier,"Courier New",monospace
}

pre {
    padding: 2.4rem 3rem 3rem;
    background: #f1f1f1;
    overflow-x: auto
}

code {
    font-size: 1.4rem;
    margin: 0 .2rem;
    padding: .3rem .6rem;
    white-space: nowrap;
    background: #f1f1f1;
    border: 1px solid #e1e1e1;
    border-radius: 3px
}

pre>code {
    display: block;
    white-space: pre;
    line-height: 2;
    padding: 0;
    margin: 0
}

pre.prettyprint>code {
    border: none
}

del {
    text-decoration: line-through
}

abbr[title],dfn[title] {
    border-bottom: 1px dotted;
    cursor: help;
    text-decoration: none
}

mark {
    background: #ffd900;
    color: #000
}

hr {
    border: solid rgba(0,0,0,.1);
    border-width: 1px 0 0;
    clear: both;
    margin: 2.4rem 0 1.5rem;
    height: 0
}

ol {
    list-style: decimal
}

ul {
    list-style: disc
}

li {
    display: list-item
}

ol,ul {
    margin-left: 1.7rem
}

ul li {
    padding-left: .4rem
}

ol ol,ol ul,ul ol,ul ul {
    margin: .6rem 0 .6rem 1.7rem
}

ul.disc li {
    display: list-item;
    list-style: none;
    padding: 0 0 0 .8rem;
    position: relative
}

ul.disc li::before {
    content: "";
    display: inline-block;
    width: 8px;
    height: 8px;
    border-radius: 50%;
    background: #dfbf5f;
    position: absolute;
    left: -17px;
    top: 11px;
    vertical-align: middle
}

dt {
    margin: 0;
    color: #dfbf5f
}

dd {
    margin: 0 0 0 2rem
}

.video-container {
    position: relative;
    padding-bottom: 56.25%;
    height: 0;
    overflow: hidden
}

.video-container embed,.video-container iframe,.video-container object,.video-container video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%
}

img.pull-right {
    margin: 1.5rem 0 0 3rem
}

img.pull-left {
    margin: 1.5rem 3rem 0 0
}

table {
    border-width: 0;
    width: 100%;
    max-width: 100%;
    font-family: proxima_nova,serif
}

td,th {
    padding: 1.5rem 3rem;
    text-align: left;
    border-bottom: 1px solid #e8e8e8
}

th {
    color: #000;
    font-family: proxima_nova,sans-serif;
    font-weight: 600
}

td {
    line-height: 1.5
}

td:first-child,th:first-child {
    padding-left: 0
}

td:last-child,th:last-child {
    padding-right: 0
}

.table-responsive {
    overflow-x: auto;
    -webkit-overflow-scrolling: touch
}

.btn,button {
    margin-bottom: 1.2rem
}

fieldset {
    margin-bottom: 1.5rem
}

.cl-custom-select,.video-container,blockquote,dl,figure,form,input,ol,p,pre,select,table,textarea,ul {
    margin-bottom: 3rem
}

.pace {
    -webkit-pointer-events: none;
    pointer-events: none;
    -webkit-user-select: none;
    -moz-user-select: none;
    user-select: none
}

.pace-inactive {
    display: none
}

.pace .pace-progress {
    background: #dfbf5f;
    position: fixed;
    z-index: 900;
    top: 0;
    right: 100%;
    width: 100%;
    height: 4px
}

.oldie .pace {
    display: none
}

#preloader {
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background: #151515;
    z-index: 800;
    height: 100vh;
    width: 100%;
    overflow: hidden
}

.no-js #preloader,.oldie #preloader {
    display: none
}

#loader {
    position: absolute;
    left: 50%;
    top: 50%;
    width: 6px;
    height: 6px;
    padding: 0;
    display: inline-block;
    -webkit-transform: translate3d(-50%,-50%,0);
    -ms-transform: translate3d(-50%,-50%,0);
    transform: translate3d(-50%,-50%,0)
}

#loader>div {
    content: "";
    background: #fff;
    width: 6px;
    height: 6px;
    position: absolute;
    top: 0;
    left: 0;
    border-radius: 50%
}

#loader>div:nth-of-type(1) {
    left: 15px
}

#loader>div:nth-of-type(3) {
    left: -15px
}

.dots-jump>div {
    -webkit-animation: dots-jump 1.2s infinite ease;
    animation: dots-jump 1.2s infinite ease;
    animation-delay: .2s
}

.dots-jump>div:nth-of-type(1) {
    animation-delay: .4s
}

.dots-jump>div:nth-of-type(3) {
    animation-delay: 0s
}

@-webkit-keyframes dots-jump {
    0% {
        top: 0
    }

    40% {
        top: -6px
    }

    80% {
        top: 0
    }
}

@keyframes dots-jump {
    0% {
        top: 0
    }

    40% {
        top: -6px
    }

    80% {
        top: 0
    }
}

.dots-fade>div {
    -webkit-animation: dots-fade 1.6s infinite ease;
    animation: dots-fade 1.6s infinite ease;
    animation-delay: .4s
}

.dots-fade>div:nth-of-type(1) {
    animation-delay: .8s
}

.dots-fade>div:nth-of-type(3) {
    animation-delay: 0s
}

@-webkit-keyframes dots-fade {
    0% {
        opacity: 1
    }

    40% {
        opacity: .2
    }

    80% {
        opacity: 1
    }
}

@keyframes dots-fade {
    0% {
        opacity: 1
    }

    40% {
        opacity: .2
    }

    80% {
        opacity: 1
    }
}

.dots-pulse>div {
    -webkit-animation: dots-pulse 1.2s infinite ease;
    animation: dots-pulse 1.2s infinite ease;
    animation-delay: .2s
}

.dots-pulse>div:nth-of-type(1) {
    animation-delay: .4s
}

.dots-pulse>div:nth-of-type(3) {
    animation-delay: 0s
}

@-webkit-keyframes dots-pulse {
    0% {
        -webkit-transform: scale(1);
        transform: scale(1)
    }

    40% {
        -webkit-transform: scale(1.1);
        transform: scale(1.3)
    }

    80% {
        -webkit-transform: scale(1);
        transform: scale(1)
    }
}

@keyframes dots-pulse {
    0% {
        -webkit-transform: scale(1);
        transform: scale(1)
    }

    40% {
        -webkit-transform: scale(1.1);
        transform: scale(1.3)
    }

    80% {
        -webkit-transform: scale(1);
        transform: scale(1)
    }
}

fieldset {
    border: none
}

input[type=email],input[type=number],input[type=password],input[type=search],input[type=tel],input[type=text],input[type=url],select,textarea {
    display: block;
    height: 6rem;
    padding: 1.5rem 2.4rem;
    border: 0;
    outline: 0;
    color: #151515;
    font-family: proxima_nova,sans-serif;
    font-size: 1.5rem;
    line-height: 3rem;
    max-width: 100%;
    background: rgba(0,0,0,.12);
    -webkit-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out
}

.cl-custom-select {
    position: relative;
    padding: 0
}

.cl-custom-select select {
    -webkit-appearance: none;
    -moz-appearance: none;
    -ms-appearance: none;
    -o-appearance: none;
    appearance: none;
    text-indent: .01px;
    text-overflow: '';
    margin: 0;
    line-height: 3rem;
    vertical-align: middle
}

.cl-custom-select select option {
    padding-left: 2rem;
    padding-right: 2rem
}

.cl-custom-select select::-ms-expand {
    display: none
}

.cl-custom-select::after {
    border-bottom: 2px solid rgba(0,0,0,.5);
    border-right: 2px solid rgba(0,0,0,.5);
    content: '';
    display: block;
    height: 8px;
    width: 8px;
    margin-top: -7px;
    pointer-events: none;
    position: absolute;
    right: 2.4rem;
    top: 50%;
    -webkit-transform-origin: 66% 66%;
    -ms-transform-origin: 66% 66%;
    transform-origin: 66% 66%;
    -webkit-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    transform: rotate(45deg);
    -webkit-transition: all .15s ease-in-out;
    transition: all .15s ease-in-out
}

.oldie .cl-custom-select::after {
    display: none
}

textarea {
    min-height: 20rem
}

input[type=email]:focus,input[type=number]:focus,input[type=password]:focus,input[type=search]:focus,input[type=tel]:focus,input[type=text]:focus,input[type=url]:focus,select:focus,textarea:focus {
    color: #000
}

label,legend {
    font-family: proxima_nova,sans-serif;
    font-weight: 600;
    font-size: 1.4rem;
    margin-bottom: .9rem;
    line-height: 1.714;
    color: #000;
    display: block
}

input[type=checkbox],input[type=radio] {
    display: inline
}

label>.label-text {
    display: inline-block;
    margin-left: 1rem;
    font-family: proxima_nova,serif;
    font-weight: 400;
    line-height: inherit
}

label>input[type=checkbox],label>input[type=radio] {
    margin: 0;
    position: relative;
    top: .15rem
}

.checkbox .help-block {
    transform: translateY(0)!important;
    padding-left: 20px
}

::-webkit-input-placeholder {
    color: rgba(13,13,13,.65)
}

:-moz-placeholder {
    color: rgba(13,13,13,.65)
}

::-moz-placeholder {
    color: rgba(13,13,13,.65)
}

:-ms-input-placeholder {
    color: rgba(13,13,13,.65)
}

.placeholder {
    color: rgba(13,13,13,.65)!important
}

input:-webkit-autofill,input:-webkit-autofill:focus input:-webkit-autofill,input:-webkit-autofill:hover,select:-webkit-autofill,select:-webkit-autofill:focus,select:-webkit-autofill:hover,textarea:-webkit-autofill,textarea:-webkit-autofill:hover textarea:-webkit-autofill:focus {
    -webkit-text-fill-color: #dfbf5f;
    transition: background-color 5000s ease-in-out 0s
}

.btn,button,input[type=button],input[type=reset],input[type=submit] {
    display: inline-block;
    font-family: proxima_nova,sans-serif;
    font-weight: 600;
    font-size: 1.6rem;
    text-transform: uppercase;
    letter-spacing: .3rem;
    height: 5.4rem;
    line-height: 5rem;
    padding: 0 3rem;
    margin: 0 .3rem 1.2rem 0;
    color: #000;
    text-decoration: none;
    text-align: center;
    white-space: nowrap;
    cursor: pointer;
    -webkit-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out;
    background-color: #c5c5c5;
    border: .2rem solid #c5c5c5
}

.btn:focus,.btn:hover,button:focus,button:hover,input[type=button]:focus,input[type=button]:hover,input[type=reset]:focus,input[type=reset]:hover,input[type=submit]:focus,input[type=submit]:hover {
    background-color: #b8b8b8;
    border-color: #b8b8b8;
    color: #000;
    outline: 0
}

.btn.btn--primary,button.btn--primary,input[type=button].btn--primary,input[type=reset].btn--primary,input[type=submit].btn--primary {
    background: #dfbf5f;
    border-color: #dfbf5f;
    color: #fff
}

.btn.btn--primary:focus,.btn.btn--primary:hover,button.btn--primary:focus,button.btn--primary:hover,input[type=button].btn--primary:focus,input[type=button].btn--primary:hover,input[type=reset].btn--primary:focus,input[type=reset].btn--primary:hover,input[type=submit].btn--primary:focus,input[type=submit].btn--primary:hover {
    background: #ed560e;
    border-color: #ed560e
}

.btn.full-width,button.full-width {
    width: 100%;
    margin-right: 0
}

.btn--medium,button.btn--medium {
    height: 5.7rem!important;
    line-height: 5.3rem!important
}

.btn--large,button.btn--large {
    height: 6rem!important;
    line-height: 5.6rem!important
}

.btn--stroke,button.btn--stroke {
    background: 0 0!important;
    border: .2rem solid #000;
    color: #000
}

.btn--stroke:hover,button.btn--stroke:hover {
    background: #000!important;
    border: .2rem solid #000;
    color: #fff
}

.btn--pill,button.btn--pill {
    padding-left: 3rem!important;
    padding-right: 3rem!important;
    border-radius: 1000px!important
}

button::-moz-focus-inner,input::-moz-focus-inner {
    border: 0;
    padding: 0
}

.alert-box {
    padding: 2.1rem 4rem 2.1rem 3rem;
    position: relative;
    margin-bottom: 3rem;
    border-radius: 3px;
    font-family: proxima_nova,sans-serif;
    font-weight: 600;
    font-size: 1.5rem;
    line-height: 1.6
}

.alert-box__close {
    position: absolute;
    right: 1.8rem;
    top: 1.8rem;
    cursor: pointer
}

.alert-box__close.fa {
    font-size: 12px
}

.alert-box--error {
    background-color: #ffd1d2;
    color: #e65153
}

.alert-box--success {
    background-color: #c8e675;
    color: #758c36
}

.alert-box--info {
    background-color: #d7ecfb;
    color: #4a95cc
}

.alert-box--notice {
    background-color: #fff099;
    color: #bba31b
}

.drop-cap:first-letter {
    float: left;
    margin: 0;
    padding: 1.5rem .6rem 0 0;
    font-family: proxima_nova,sans-serif;
    font-weight: 700;
    font-size: 8.4rem;
    line-height: 6rem;
    text-indent: 0;
    background: 0 0;
    color: #000
}

.lining dd,.lining dt {
    display: inline;
    margin: 0
}

.lining dd+dt:before,.lining dt+dt:before {
    content: "\A";
    white-space: pre
}

.lining dd+dd:before {
    content: ", "
}

.lining dd+dd:before {
    content: ", "
}

.lining dd:before {
    content: ": ";
    margin-left: -.2em
}

.dictionary-style dt {
    display: inline;
    counter-reset: definitions
}

.dictionary-style dt+dt:before {
    content: ", ";
    margin-left: -.2em
}

.dictionary-style dd {
    display: block;
    counter-increment: definitions
}

.dictionary-style dd:before {
    content: counter(definitions,decimal) ". "
}

.pull-quote {
    position: relative;
    padding: 2.1rem 3rem 2.1rem 0
}

.pull-quote:after,.pull-quote:before {
    height: 1em;
    position: absolute;
    font-size: 10rem;
    font-family: Arial,Sans-Serif;
    color: rgba(0,0,0,.25)
}

.pull-quote:before {
    content: "\201C";
    top: -3.6rem;
    left: 0
}

.pull-quote:after {
    content: '\201D';
    bottom: 3.6rem;
    right: 0
}

.pull-quote blockquote {
    margin: 0
}

.pull-quote blockquote:before {
    content: none
}

.stats-tabs {
    padding: 0;
    margin: 3rem 0
}

.stats-tabs li {
    display: inline-block;
    margin: 0 1.5rem 3rem 0;
    padding: 0 1.5rem 0 0;
    border-right: 1px solid rgba(0,0,0,.2)
}

.stats-tabs li:last-child {
    margin: 0;
    padding: 0;
    border: none
}

.stats-tabs li a {
    display: inline-block;
    font-size: 2.5rem;
    font-family: proxima_nova,sans-serif;
    font-weight: 700;
    border: none;
    color: #000
}

.stats-tabs li a:hover {
    color: #dfbf5f
}

.stats-tabs li a em {
    display: block;
    margin: .6rem 0 0 0;
    font-family: proxima_nova,sans-serif;
    font-size: 1.4rem;
    font-weight: 400;
    font-style: normal
}

.skill-bars {
    list-style: none;
    margin: 6rem 0 3rem
}

.skill-bars li {
    height: .6rem;
    background: #c9c9c9;
    width: 100%;
    margin-bottom: 6.9rem;
    padding: 0;
    position: relative
}

.skill-bars li strong {
    position: absolute;
    left: 0;
    top: -3rem;
    font-family: proxima_nova,sans-serif;
    font-weight: 700;
    color: #000;
    text-transform: uppercase;
    letter-spacing: .2rem;
    font-size: 1.4rem;
    line-height: 2.4rem
}

.skill-bars li .progress {
    background: #000;
    position: relative;
    height: 100%
}

.skill-bars li .progress span {
    position: absolute;
    right: 0;
    top: -3.6rem;
    display: block;
    font-family: proxima_nova,sans-serif;
    color: #fff;
    font-size: 1.1rem;
    line-height: 1;
    background: #000;
    padding: .6rem .6rem;
    border-radius: 3px
}

.skill-bars li .progress span::after {
    position: absolute;
    left: 50%;
    bottom: -5px;
    margin-left: -5px;
    border-right: 5px solid transparent;
    border-left: 5px solid transparent;
    border-top: 5px solid #000;
    content: ""
}

.skill-bars li .percent5 {
    width: 5%
}

.skill-bars li .percent10 {
    width: 10%
}

.skill-bars li .percent15 {
    width: 15%
}

.skill-bars li .percent20 {
    width: 20%
}

.skill-bars li .percent25 {
    width: 25%
}

.skill-bars li .percent30 {
    width: 30%
}

.skill-bars li .percent35 {
    width: 35%
}

.skill-bars li .percent40 {
    width: 40%
}

.skill-bars li .percent45 {
    width: 45%
}

.skill-bars li .percent50 {
    width: 50%
}

.skill-bars li .percent55 {
    width: 55%
}

.skill-bars li .percent60 {
    width: 60%
}

.skill-bars li .percent65 {
    width: 65%
}

.skill-bars li .percent70 {
    width: 70%
}

.skill-bars li .percent75 {
    width: 75%
}

.skill-bars li .percent80 {
    width: 80%
}

.skill-bars li .percent85 {
    width: 85%
}

.skill-bars li .percent90 {
    width: 90%
}

.skill-bars li .percent95 {
    width: 95%
}

.skill-bars li .percent100 {
    width: 100%
}

.wide {
    max-width: 1400px
}

.narrow {
    max-width: 800px
}

.light-gray {
    background-color: #f0eeee
}

.display-1 {
    font-family: proxima_nova,sans-serif;
    font-weight: 600;
    font-size: 4.7rem;
    line-height: 1.5;
    letter-spacing: -.03rem;
    margin-top: 0;
    margin-bottom: 4.8rem
}

.display-1--light {
    color: #fff
}

.subhead {
    font-family: proxima_nova,sans-serif;
    font-weight: 600;
    font-size: 1.7rem;
    line-height: 1.333;
    text-transform: uppercase;
    letter-spacing: .25rem;
    color: #dfbf5f;
    margin-top: 0;
    margin-bottom: 3.6rem;
    position: relative
}

.subhead::before {
    content: attr(data-num) ".";
    padding-right: 72px;
    font-weight: 700
}

.subhead::after {
    content: "";
    display: block;
    background-color: #dfbf5f;
    height: 1px;
    margin-top: -1px;
    width: 4.5rem;
    position: absolute;
    top: 50%;
    left: 4rem
}

.section-header {
    position: relative
}

.section-header .display-1,.section-header p.lead {
    padding-left: 12rem;
    padding-right: 12rem
}

.section-header .lead-light {
    color: rgba(255,255,255,.3)
}

.btn-animatedbg {
    position: relative;
    background: 0 0!important;
    border-color: #dfbf5f!important;
    border-radius: 100px;
    color: #fff!important;
    height: 6.6rem;
    line-height: 6.2rem;
    padding: 0 8rem 0 4rem;
    overflow: hidden;
    z-index: 1
}

.btn-animatedbg::before {
    content: "";
    height: 100%;
    width: 0;
    background-color: #dfbf5f;
    -webkit-transition: all .2s ease-in-out;
    transition: all .2s ease-in-out;
    position: absolute;
    top: 0;
    left: 0;
    z-index: -1
}

.btn-animatedbg::after {
    display: block;
    content: "";
    width: 2rem;
    height: 2rem;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: contain;
    -webkit-transition: all .2s ease-in-out;
    transition: all .2s ease-in-out;
    margin-top: -1.1rem;
    position: absolute;
    top: 50%;
    right: 4rem
}

.btn-animatedbg:hover::before {
    width: 100%
}

.btn-animatedbg:hover::after {
    right: 3rem
}

@media only screen and (max-width: 1300px) {
    .display-1 {
        font-size:4.5rem
    }

    .section-header .display-1,.section-header p.lead {
        padding-left: 0;
        padding-right: 3rem
    }
}

@media only screen and (max-width: 1200px) {
    .display-1 {
        font-size:4.2rem
    }
}

@media only screen and (max-width: 900px) {
    .display-1 {
        font-size:4rem
    }

    .subhead {
        font-size: 1.5rem
    }

    .section-header .display-1,.section-header p.lead {
        padding-right: 0
    }
}

@media only screen and (max-width: 800px) {
    .display-1 {
        font-size:3.8rem
    }
}

@media only screen and (max-width: 700px) {
    .display-1 {
        font-size:3.6rem;
        margin-bottom: 3.6rem
    }

    .subhead {
        margin-bottom: 2.4rem
    }
}

@media only screen and (max-width: 600px) {
    .display-1 {
        font-size:3.5rem
    }
}

@media only screen and (max-width: 500px) {
    .display-1 {
        font-size:3rem
    }

    .subhead {
        font-size: 1.4rem
    }

    .subhead::before {
        padding-right: 45px
    }

    .subhead::after {
        width: 2.5rem;
        left: 3.5rem
    }
}

@media only screen and (max-width: 400px) {
    .display-1 {
        font-size:2.8rem
    }
}

.s-home {
    width: 100%;
    height: 100vh;
    min-height: 786px;
    background-color: transparent;
    position: relative;
    display: table
}

.video-container-home {
    position: fixed;
    top: -50%;
    left: -50%;
    width: 200%;
    height: 200%
}

#myVideo {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    margin: auto;
    min-width: 50%;
    min-height: 50%
}

@media screen and (max-width: 1040px) {
    #myVideo {
        object-fit:cover
    }
}

.s-home::before {
    display: block;
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    opacity: .4;
    background-color: #000
}

.s-home .shadow-overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    opacity: .8;
    background: linear-gradient(to bottom,rgba(0,0,0,.9) 0,rgba(0,0,0,.7) 100%)
}

.no-js .s-home {
    background: #000
}

.home-content {
    display: table-cell;
    width: 100%;
    height: 100vh;
    vertical-align: middle;
    padding-top: 90px;
    overflow: hidden;
    position: relative
}

.home-content h1 {
    font-size: 6.6rem;
    font-weight: 700;
    line-height: 1.5;
    margin-top: 0;
    color: #fff
}

.home-content__main {
    padding-left: 14rem;
    padding-right: 14rem;
    position: relative;
    max-width: 1400px;
    text-align: center;
    justify-content: center;
}

.home-content__button {
    margin-top: 6rem
}

.home-content__button .btn {
    margin-right: 0
}

.home-content__video {
    position: absolute;
    top: 7.2rem;
    right: 12rem
}

.home-content__video .video-link {
    display: block;
    text-align: center;
    width: 13rem;
    outline: 0;
    position: relative
}

.home-content__video .video-icon {
    display: inline-block;
    height: 8.4rem;
    width: 8.4rem;
    border-radius: 50%;
    background-color: rgba(255,255,255,.1);
    background-repeat: no-repeat;
    background-position: 55% center;
    background-size: 24px 27px;
    -webkit-transition: background-color .3s ease-in-out;
    transition: background-color .3s ease-in-out
}

.home-content__video .video-text {
    display: inline-block;
    text-align: center;
    font-family: proxima_nova,sans-serif;
    font-size: 1.3rem;
    font-weight: 600;
    color: rgba(255,255,255,.5);
    text-transform: uppercase;
    letter-spacing: .4rem;
    -webkit-transition: color .3s ease-in-out;
    transition: color .3s ease-in-out
}

.home-content__video .video-link:hover .video-text {
    color: #fff
}

.home-content__video .video-link:hover .video-icon {
    background-color: #dfbf5f
}

.home-content__scroll {
    position: absolute;
    right: 8rem;
    bottom: 6rem;
    -webkit-transform: rotate(-90deg) translate3d(100%,50%,0);
    -ms-transform: rotate(-90deg) translate3d(100%,50%,0);
    transform: rotate(-90deg) translate3d(100%,50%,0);
    -webkit-transform-origin: right bottom;
    -ms-transform-origin: right bottom;
    transform-origin: right bottom
}

.home-content__scroll .scroll-link {
    font-family: proxima_nova,sans-serif;
    font-weight: 600;
    font-size: 1.3rem;
    text-transform: uppercase;
    letter-spacing: .35rem;
    text-align: left;
    color: #fff;
    position: relative;
    padding-right: 200px
}

.home-content__scroll .scroll-link:hover {
    color: #dfbf5f
}

.home-content__scroll::after {
    content: "";
    display: block;
    background-color: rgba(255,255,255,.3);
    width: 150px;
    height: 1px;
    position: absolute;
    right: 0;
    top: 50%
}

.home-social {
    list-style: none;
    font-family: proxima_nova,sans-serif;
    margin: 0;
    position: absolute;
    top: 6rem;
    right: 6.2rem;
    z-index: 500
}

.home-social a {
    color: #fff;
    -webkit-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out
}

.home-social li {
    position: relative;
    padding: .6rem 0
}

.home-social li a {
    display: block;
    width: 36px;
    height: 36px;
    line-height: 36px
}

.home-social i,.home-social span {
    position: absolute;
    top: 0;
    -webkit-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out
}

.home-social i {
    display: inline-block;
    font-size: 20px;
    text-align: center;
    width: 36px;
    height: 36px;
    line-height: 36px;
    right: 0
}

.home-social span {
    background-color: #151515;
    font-size: 1.2rem;
    line-height: 30px;
    color: #dfbf5f;
    right: 50px;
    padding: 0 15px;
    margin: 3px 0;
    opacity: 0;
    visibility: hidden;
    -webkit-transform: scale(0);
    -ms-transform: scale(0);
    transform: scale(0);
    -webkit-transform-origin: 100% 50%;
    -ms-transform-origin: 100% 50%;
    transform-origin: 100% 50%
}

.home-social span::after {
    display: block;
    content: "";
    width: 0;
    height: 0;
    border-top: 6px solid transparent;
    border-bottom: 6px solid transparent;
    border-left: 6px solid #151515;
    position: absolute;
    top: 50%;
    right: -6px;
    margin-top: -6px
}

.home-social li:hover span {
    opacity: 1;
    visibility: visible;
    -webkit-transform: scale(1);
    -ms-transform: scale(1);
    transform: scale(1)
}

html.cl-preload .home-content__main {
    opacity: 0
}

html.cl-loaded .home-content__main {
    animation-duration: 2s;
    -webkit-animation-name: fadeIn;
    animation-name: fadeIn
}

html.no-csstransitions .home-content__main {
    opacity: 1
}

@-webkit-keyframes fadeIn {
    from {
        opacity: 0;
        -webkit-transform: translate3d(0,150%,0);
        -ms-transform: translate3d(0,150%,0);
        transform: translate3d(0,150%,0)
    }

    to {
        opacity: 1;
        -webkit-transform: translate3d(0,0,0);
        -ms-transform: translate3d(0,0,0);
        transform: translate3d(0,0,0)
    }
}

@keyframes fadeIn {
    from {
        opacity: 0;
        -webkit-transform: translate3d(0,150%,0);
        -ms-transform: translate3d(0,150%,0);
        transform: translate3d(0,150%,0)
    }

    to {
        opacity: 1;
        -webkit-transform: translate3d(0,0,0);
        -ms-transform: translate3d(0,0,0);
        transform: translate3d(0,0,0)
    }
}

@-webkit-keyframes fadeOut {
    from {
        opacity: 1
    }

    to {
        opacity: 0;
        -webkit-transform: translate3d(0,-150%,0);
        -ms-transform: translate3d(0,-150%,0);
        transform: translate3d(0,-150%,0)
    }
}

@keyframes fadeOut {
    from {
        opacity: 1
    }

    to {
        opacity: 0;
        -webkit-transform: translate3d(0,-150%,0);
        -ms-transform: translate3d(0,-150%,0);
        transform: translate3d(0,-150%,0)
    }
}

@media only screen and (max-width: 1600px) {
    .home-content h1 {
        font-size:7.1rem
    }

    .home-content__video {
        right: 13rem
    }
}

@media only screen and (max-width: 1400px) {
    .home-content h1 {
        font-size:6rem
    }
}

@media only screen and (max-width: 1200px) {
    .home-content h1 {
        font-size:5.6rem
    }

    .home-content__main {
        padding-left: 3rem;
        padding-right: 3rem
    }

    .home-content__button,.home-content__video {
        display: inline-block;
        vertical-align: top
    }

    .home-content__video {
        position: static;
        margin-top: 6rem;
        margin-left: 6rem;
        height: 6.6rem;
        line-height: 6.6rem
    }

    .home-content__video .video-link {
        padding-left: 9rem;
        width: auto
    }

    .home-content__video .video-icon {
        height: 6.6rem;
        width: 6.6rem;
        background-size: 12px 13px;
        position: absolute;
        top: 0;
        left: 0
    }
}

@media only screen and (max-width: 1000px) {
    .home-content h1 {
        font-size:5.4rem
    }

    .home-social i {
        font-size: 1.8rem
    }
}

@media only screen and (max-width: 900px) {
    .home-social {
        display:none
    }
}

@media only screen and (max-width: 800px) {
    .home-content {
        padding-top:72px
    }

    .home-content h1 {
        font-size: 5rem
    }

    .home-content__main {
        max-width: 600px
    }

    .home-content__main h1 br {
        display: none
    }

    .home-content__video {
        margin-left: 4rem
    }

    .home-content__video .video-text {
        display: none
    }

    .home-content__scroll {
        right: 6rem;
        bottom: 4.2rem
    }

    .home-content__scroll .scroll-link {
        padding-right: 80px
    }

    .home-content__scroll::after {
        width: 50px
    }
}

@media only screen and (max-width: 700px) {
    .home-content h1 {
        font-size:4.8rem
    }

    .home-content__main {
        max-width: 490px
    }
}

@media only screen and (max-width: 600px) {
    .home-content {
        vertical-align:middle;
        padding-top: 19.8rem;
        padding-bottom: 12rem
    }

    .home-content h1 {
        font-size: 4.2rem
    }

    .home-content__main {
        padding: 0 40px
    }

    .home-content__button {
        margin-top: 3rem
    }

    .home-content__video {
        margin-top: 1.5rem;
        margin-left: 0
    }

    .home-content__video .video-text {
        display: inline-block;
        font-size: 11px
    }

    .home-content__scroll .scroll-link {
        font-size: 11px
    }

    .home-content__scroll::after {
        display: none
    }
}

@media only screen and (max-width: 500px) {
    .s-home {
        min-height:654px
    }

    .home-content h1 {
        font-size: 3.8rem
    }
}

@media only screen and (max-width: 400px) {
    .home-content__main {
        padding:0 25px
    }

    .home-content {
        padding-top: 15rem
    }

    .home-content h1 {
        font-size: 3.5rem
    }

    .home-content__scroll {
        right: 5rem
    }
}

@media only screen and (max-width: 350px) {
    .home-content h1 {
        font-size:3.2rem
    }

    .home-content__button .btn {
        padding: 0 6.5rem 0 3rem
    }
}

.s-oferta-2 {
    padding-top: 18rem;
    padding-bottom: 0;
    background-color: #edf3f5;
    position: relative
}

.s-oferta-2 h1 {
    color: white;
}

.management-process {
    margin-top: 8.4rem
}

.management-process h3 {
    margin-top: 0;
    margin-left: 7.5rem
}

.management-process .col-block {
    margin-bottom: 4rem
}

.management-process .col-block:nth-child(2n+1)>* {
    margin-right: 25px
}

.management-process .col-block:nth-child(2n+2)>* {
    margin-left: 25px
}

.management-process .item-process__header {
    position: relative;
    margin-bottom: 3rem
}

.management-process .item-process__header::before {
    content: "";
    display: block;
    width: 6rem;
    height: 6rem;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: contain;
    -webkit-transform: translate3d(0,-30%,0);
    -ms-transform: translate3d(0,-30%,0);
    transform: translate3d(0,-30%,0);
    position: absolute;
    top: 0;
    left: 0
}

.management-process .item-process__header--planning::before {
}

.v-process .item-process__header--branding::before {
}

.management-process .item-process__header--implementation::before {
}

.v-process .item-process__header--documentation::before {
}

.management-process .item-process__header.icon {
    max-height: 60px;
    max-width: 60px;
    margin: 0 auto 25px!important
}

.logo-process .item-process__header.icon {
    max-height: 100px;
    max-width: 200px;
    margin: 0 auto 25px!important
}

.logo-process .item-process__header.icon.booking {
    margin-top: 37px;
}

.logo-process .item-process__header.icon.haus {
    padding-top: 26px;
}

.management-process .col-block p {
    text-align: center;
    margin: 0!important;
    color: white;
}

.VueCarousel-dot-container {
    display: none !important;
}

.s-management {
    padding-top: 3rem;
    padding-bottom: 0;
    background-color: #edf3f5;
    position: relative;
}

.s-management span {
    position: relative;
    white-space: nowrap
}

.s-management span:before {
    display: block;
    margin: auto;
    border-radius: 50px;
    width: 100%;
    height: 15px;
    background: #dfbf5f;
    content: " ";
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
    z-index: -1;
    opacity: .42
}

@media only screen and (max-width: 1200px) {
    .s-management {
        padding-top:16.2rem;
        padding-bottom: 0
    }
}

@media only screen and (max-width: 1100px) {
    .management-process .col-block:nth-child(2n+1)>* {
        margin-right:15px
    }

    .management-process .col-block:nth-child(2n+2)>* {
        margin-left: 15px
    }
}

@media only screen and (max-width: 900px) {
    .management-process .col-block:nth-child(2n+1)>* {
        margin-right:5px
    }

    .management-process .col-block:nth-child(2n+2)>* {
        margin-left: 5px
    }
}

@media only screen and (max-width: 800px) {
    .management-process {
        margin-top:6rem
    }

    .management-process .col-block:after {
        content: "";
        display: table;
        clear: both
    }

    .management-process .col-block:nth-child(2n+1)>* {
        margin-right: 0
    }

    .v-process .col-block:nth-child(2n+2)>* {
        margin-left: 0
    }
}

@media only screen and (max-width: 500px) {
    .management-process h3 {
        font-size:2.1rem;
        margin-left: 6.5rem
    }

    .management-process .item-process__header::before {
        width: 5.5rem;
        height: 5.5rem;
        top: 0;
        left: 0
    }
}

.s-range {
    padding-top: 18rem;
    padding-bottom: 18rem;
    background-color: #fff;
    position: relative
}

.s-range .section-header {
    z-index: 1
}

.range-process {
    margin-top: 8.4rem
}

.range-process h3 {
    margin-top: 0;
    margin-left: 7.5rem
}

.range-process .col-block {
    margin-bottom: 1.8rem
}

.range-process .col-block:nth-child(2n+1)>* {
    margin-right: 25px
}

.range-process .col-block:nth-child(2n+2)>* {
    margin-left: 25px
}

.range-process .item-process__header {
    position: relative;
    margin-bottom: 3rem
}

.range-process .item-process__header::before {
    content: "";
    display: block;
    width: 6rem;
    height: 6rem;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: contain;
    -webkit-transform: translate3d(0,-30%,0);
    -ms-transform: translate3d(0,-30%,0);
    transform: translate3d(0,-30%,0);
    position: absolute;
    top: 0;
    left: 0
}

.range-process .item-process__header--planning::before {
}

.range-process .item-process__header--branding::before {
}

.range-process .item-process__header--implementation::before {
}

.range-process .item-process__header--documentation::before {
}

.s-range span {
    transition: all .25s ease-in-out
}

.s-range span.active,.s-range span:hover {
    cursor: pointer;
    color: #dfbf5f;
    transition: all .25s ease-in-out
}

.s-range .list {
    padding-left: 12rem;
    padding-right: 12rem;
    counter-reset: range-counter;
    list-style: none;
    margin: 0;
    font-family: Roboto,sans-serif;
    font-weight: 300;
    font-size: 2.5rem
}

.s-range .list li:before {
    content: counter(range-counter,decimal-leading-zero) ".";
    counter-increment: range-counter;
    margin-right: 18px;
    font-weight: 700;
    color: #dfbf5f;
}

.s-range .row.map {
    max-width: 600px;
    position: absolute;
    top: 50%;
    right: 0;
    margin: auto;
    height: auto;
    transform: translate(0,-50%)
}

@media only screen and (max-width: 1200px) {
    .s-range .row.map {
        top:60%
    }
}

@media only screen and (max-width: 900px) {
    .s-range .row.map {
        position:relative;
        transform: translate(0)
    }
}

.s-range .circle {
    width: 16px;
    height: 16px;
    border-radius: 50%;
    position: absolute;
    transform: translate(-50%,-50%)
}

.s-range .circle.active:before {
    content: '';
    position: relative;
    display: block;
    width: 300%;
    height: 300%;
    box-sizing: border-box;
    margin-left: -100%;
    margin-top: -100%;
    border-radius: 45px;
    background-color: #dfbf5f;
    animation: pulse-ring 1.25s cubic-bezier(.215,.61,.355,1) infinite
}

.s-range .circle:after {
    content: '';
    position: absolute;
    left: 0;
    top: 0;
    display: block;
    width: 100%;
    height: 100%;
    background-color: #dfbf5f;
    border-radius: 100px
}

@keyframes pulse-ring {
    0% {
        transform: scale(.33)
    }

    100%,80% {
        opacity: 0
    }
}

@media only screen and (max-width: 1200px) {
    .s-range {
        padding-top:16.2rem;
        padding-bottom: 16.2rem
    }
}

@media only screen and (max-width: 1100px) {
    .range-process .col-block:nth-child(2n+1)>* {
        margin-right:15px
    }

    .range-process .col-block:nth-child(2n+2)>* {
        margin-left: 15px
    }
}

@media only screen and (max-width: 900px) {
    .range-process .col-block:nth-child(2n+1)>* {
        margin-right:5px
    }

    .range-process .col-block:nth-child(2n+2)>* {
        margin-left: 5px
    }
}

@media only screen and (max-width: 800px) {
    .range-process {
        margin-top:6rem
    }

    .range-process .col-block:after {
        content: "";
        display: table;
        clear: both
    }

    .range-process .col-block:nth-child(2n+1)>* {
        margin-right: 0
    }

    .range-process .col-block:nth-child(2n+2)>* {
        margin-left: 0
    }
}

@media only screen and (max-width: 500px) {
    .range-process h3 {
        font-size:2.1rem;
        margin-left: 6.5rem
    }

    .range-process .item-process__header::before {
        width: 5.5rem;
        height: 5.5rem;
        top: 0;
        left: 0
    }
}

@media only screen and (max-width: 1300px) {
    .s-range .list {
        padding-left:0;
        padding-right: 3rem
    }
}

@media only screen and (max-width: 1200px) {
    .s-range .list {
        font-size:2.2rem
    }
}

@media only screen and (max-width: 1000px) {
    .s-range .list {
        font-size:2.1rem
    }
}

@media only screen and (max-width: 900px) {
    .s-range .list {
        padding-right:0
    }
}

@media only screen and (max-width: 800px) {
    .s-range .list {
        font-size:2rem
    }
}

.s-about {
    padding-top: 18rem;
    padding-bottom: 18rem;
    background-color: #edf3f5;
    position: relative
}

.about-process {
    margin-top: 8.4rem
}

.about-process h3 {
    margin-top: 0;
    margin-left: 7.5rem
}

.about-process .col-block {
    margin-bottom: 1.8rem
}

.about-process .col-block:nth-child(2n+1)>* {
    margin-right: 25px
}

.about-process .col-block:nth-child(2n+2)>* {
    margin-left: 25px
}

.about-process .item-process__header {
    position: relative;
    margin-bottom: 3rem
}

.about-process .item-process__header::before {
    content: "";
    display: block;
    width: 6rem;
    height: 6rem;
    background-position: center center;
    background-repeat: no-repeat;
    background-size: contain;
    -webkit-transform: translate3d(0,-30%,0);
    -ms-transform: translate3d(0,-30%,0);
    transform: translate3d(0,-30%,0);
    position: absolute;
    top: 0;
    left: 0
}

.about-process .item-process__header--planning::before {
}

.about-process .item-process__header--branding::before {
}

.about-process .item-process__header--implementation::before {
}

.about-process .item-process__header--documentation::before {
}

.s-about .bottom {
    padding-left: 12rem;
    padding-right: 12rem
}

@media only screen and (max-width: 1300px) {
    .s-about .bottom {
        padding-left:0;
        padding-right: 3rem
    }
}

@media only screen and (max-width: 900px) {
    .s-about .bottom {
        padding-right:0
    }
}

.s-about .list ul {
    list-style: none;
    margin: 30px 0 30px
}

.s-about .list li {
    font-weight: 300;
    font-size: 1.8rem
}

.s-about li {
    margin: 0;
    padding-left: 28px;
    margin-bottom: 15px;
    list-style: none;
    background-repeat: no-repeat;
    background-position: left center;
    background-size: 13px;
    line-height: normal
}

.s-about .list .head {
    color: #000;
    font-weight: 400;
    font-size: 1.8rem
}

.s-about .list .summary {
    color: #000;
    font-weight: 700;
    font-size: 3rem;
    width: 150%;
}

.s-about .boxes {
    padding: 50px 0 0
}

.s-about .box {
    position: relative;
    padding: 20px 35px;
    display: inline-block;
    font-family: proxima_nova,sans-serif;
    line-height: normal;
    border-radius: 8px;
    z-index: 1
}

.s-about .box.box1,.s-about .box.box3 {
    background: #fff
}

.s-about .box.box1:before,.s-about .box.box3:before {
    content: " ";
    width: 34px;
    height: 34px;
    position: absolute;
    top: -6px;
    left: 15px;
    background: #fff;
    border-radius: 8px;
    transform: rotate(45deg);
    z-index: -1
}

.s-about .box.box1 .head,.s-about .box.box3 .head {
    color: #272727;
    font-size: 3.1rem;
    letter-spacing: .1em;
    font-weight: 700
}

.s-about .box.box1 .dsc,.s-about .box.box3 .dsc {
    color: #b2b2b2;
    font-size: 1.5rem;
    letter-spacing: .2em;
    text-transform: uppercase;
    font-weight: 600
}

.s-about .box.box2,.s-about .box.box4 {
    background: #dfbf5f;
    margin-bottom: 20px
}

.s-about .box.box2:before,.s-about .box.box4:before {
    content: " ";
    width: 34px;
    height: 34px;
    position: absolute;
    bottom: -6px;
    right: 15px;
    background: #dfbf5f;
    border-radius: 8px;
    transform: rotate(45deg);
    z-index: -1
}

.s-about .box.box2 .head,.s-about .box.box4 .head {
    color: #fff;
    font-size: 3.1rem;
    letter-spacing: .1em;
    font-weight: 700
}

.s-about .box.box2 .dsc,.s-about .box.box4 .dsc {
    color: #386f6f;
    text-transform: uppercase;
    font-size: 1.5rem;
    letter-spacing: .2em;
    font-weight: 600
}

.s-about .box.box1 {
    margin-right: 15px;
    margin-bottom: 15px;
    margin-left: 20px;
    margin-top: -50px;
    float: left
}

.s-about .box.box3 {
    margin-left: 14%
}

.s-about .box.box4 {
    margin-top: 15px;
    margin-left: 56%
}

@media only screen and (max-width: 800px) {
    .s-about .boxes {
        margin-top:50px
    }

    .s-about .box.box3 {
        margin-left: 5%
    }

    .s-about .box.box4 {
        margin-left: 26%
    }
}

@media only screen and (max-width: 1200px) {
    .s-about {
        padding-top:16.2rem;
        padding-bottom: 16.2rem
    }
}

@media only screen and (max-width: 1100px) {
    .about-process .col-block:nth-child(2n+1)>* {
        margin-right:15px
    }

    .about-process .col-block:nth-child(2n+2)>* {
        margin-left: 15px
    }
}

@media only screen and (max-width: 900px) {
    .about-process .col-block:nth-child(2n+1)>* {
        margin-right:5px
    }

    .about-process .col-block:nth-child(2n+2)>* {
        margin-left: 5px
    }
}

@media only screen and (max-width: 800px) {
    .about-process {
        margin-top:6rem
    }

    .about-process .col-block:after {
        content: "";
        display: table;
        clear: both
    }

    .about-process .col-block:nth-child(2n+1)>* {
        margin-right: 0
    }

    .about-process .col-block:nth-child(2n+2)>* {
        margin-left: 0
    }
}

@media only screen and (max-width: 500px) {
    .about-process h3 {
        font-size:2.1rem;
        margin-left: 6.5rem
    }

    .about-process .item-process__header::before {
        width: 5.5rem;
        height: 5.5rem;
        top: 0;
        left: 0
    }
}

.s-services {
    padding-top: 0;
    padding-bottom: 18rem;
    background-color: #edf3f5;
    background-size: cover;
    position: relative;
    color: rgba(255,255,255,.5)
}

.s-services h4 {
    margin-top: 0;
    color: #fff
}

.s-services a {
    color: #dfbf5f
}

.s-services a:active,.s-services a:focus,.s-services a:hover {
    color: #fff
}

.services-list {
    margin-top: 7.8rem;
    counter-reset: ctr;
    position: relative
}

.services-list .item-service {
    margin-bottom: 1.5rem
}

.services-list .item-service::before {
    display: block;
    content: counter(ctr,decimal-leading-zero) ".";
    counter-increment: ctr;
    margin-bottom: 4.8rem;
    font-weight: 700;
    font-size: 3.6rem;
    line-height: 1;
    color: #dfbf5f
}

.s-services .rangeslider {
    margin-top: 50px
}

.s-services .rangeslider .row {
    padding-left: 12rem;
    padding-right: 12rem
}

@media only screen and (max-width: 1300px) {
    .s-services .rangeslider .row {
        padding-left:0;
        padding-right: 3rem
    }
}

@media only screen and (max-width: 900px) {
    .s-services .rangeslider .row {
        padding-right:0
    }
}

@media only screen and (max-width: 800px) {
    .s-services .rangeslider {
        margin-bottom:50px
    }
}

.s-services .rangeslider p {
    font-family: Roboto,sans-serif;
    font-weight: 500;
    color: #000;
    font-size: 1.6rem;
    margin-bottom: 50px
}

.s-services .rangeslider .box {
    margin-bottom: 16px;
    border-radius: 8px;
    padding: 20px 20px 15px
}

.s-services .rangeslider .box .left {
    width: 40px;
    display: inline-block;
    margin-right: 18px
}

.s-services .rangeslider .box .right {
    display: inline-block
}

.s-services .rangeslider .box .text {
    font-family: proxima_nova,sans-serif;
    color: #386f6f;
    font-size: 1.2rem;
    font-weight: 600;
    letter-spacing: .2em;
    line-height: normal;
    text-transform: uppercase;
    margin-bottom: 5px
}

.s-services .rangeslider .box .price {
    font-family: proxima_nova,sans-serif;
    color: #fff;
    font-size: 3.3rem;
    font-weight: 700;
    letter-spacing: .2em;
    line-height: normal
}

.s-services .rangeslider .box .price.rent-rate {
    color: #000
}

.s-services .rangeslider .box.bg {
    background: #dfbf5f;
}

.s-services .rangeslider .box.border {
    border: 1px solid #dfbf5f;
}

.s-services .rangeslider .box.border .text {
    color: #dfbf5f;
}

.s-services .rangeslider .box.bg {
    background: #dfbf5f;
}

.s-services .slider {
    -webkit-appearance: none;
    width: 100%;
    height: 18px;
    background: rgba(91,178,177,.3);
    outline: 0
}

.s-services .slider::-webkit-slider-thumb {
    -webkit-appearance: none;
    appearance: none;
    width: 90px;
    height: 90px;
    border-radius: 50%;
    background: #dfbf5f;
    cursor: pointer
}

.s-services .slider::-moz-range-thumb {
    width: 90px;
    height: 90px;
    border-radius: 50%;
    background: #dfbf5f;
    cursor: pointer;
    content: "test"
}

@media only screen and (max-width: 1200px) {
    .s-services {
        padding-top:0;
        padding-bottom: 16.2rem
    }
}

@media only screen and (max-width: 800px) {
    .services-list {
        margin-top:6rem
    }
}

@media only screen and (max-width: 500px) {
    .services-list .item-service::before {
        font-size:3.3rem
    }
}

.s-oferta {
    padding-top: 18rem;
    padding-bottom: 18rem;
    background-color: #151515;
    background-repeat: no-repeat;
    background-position: center center;
    background-image: url('../static/ponuda.png');
    background-size: cover;
    position: relative
}

.s-oferta .head {
    font-size: 2.5rem;
    color: #fff
}

.s-oferta .head span {
    color: #dfbf5f;
    font-weight: 700;
    margin-right: 18px
}

.s-oferta .tab-full.list p {
    color: rgba(255,255,255)
}

.s-works {
    padding-top: 18rem;
    padding-bottom: 18rem;
    background-color: #fff;
    position: relative
}

.portfolio {
    margin-top: 9rem
}

.item-folio {
    position: relative;
    overflow: hidden;
    font-family: proxima_nova,sans-serif
}

.item-folio__thumb a {
    display: block
}

.item-folio__thumb a::before {
    display: block;
    background-color: rgba(0,0,0,.85);
    content: "";
    opacity: 0;
    visibility: hidden;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    -webkit-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out;
    z-index: 1
}

.item-folio__thumb a::after {
    z-index: 1;
    content: "+";
    font-family: sans-serif;
    font-size: 2.4rem;
    color: #fff;
    display: block;
    height: 30px;
    width: 30px;
    line-height: 30px;
    margin-left: -15px;
    margin-top: -15px;
    position: absolute;
    left: 50%;
    top: 50%;
    text-align: center;
    opacity: 0;
    visibility: hidden;
    -webkit-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out;
    -webkit-transform: scale(.5);
    -ms-transform: scale(.5);
    transform: scale(.5)
}

.item-folio__thumb img {
    vertical-align: bottom
}

.item-folio__text {
    padding: 0 3rem;
    -webkit-transform: translate3d(0,-100%,0);
    -ms-transform: translate3d(0,-100%,0);
    transform: translate3d(0,-100%,0);
    opacity: 0;
    visibility: hidden;
    -webkit-transition: all .5s ease-in-out;
    transition: all .5s ease-in-out;
    position: absolute;
    left: 0;
    top: 3.6rem;
    z-index: 2
}

.item-folio__title {
    color: #fff;
    font-size: 1.8rem;
    margin: 0
}

.item-folio__cat {
    color: rgba(255,255,255,.4);
    font-size: 1.4rem;
    margin-bottom: 0
}

.item-folio__project-link {
    display: block;
    font-weight: 600;
    font-size: 1.2rem;
    color: #000;
    background-color: #fff;
    padding: .6rem 1.2rem;
    opacity: 0;
    visibility: hidden;
    -webkit-transform: translate3d(-100%,0,0);
    -ms-transform: translate3d(-100%,0,0);
    transform: translate3d(-100%,0,0);
    position: absolute;
    bottom: 3.9rem;
    left: 3rem;
    z-index: 500
}

.item-folio__project-link::before {
    display: block;
    content: "";
    height: 1px;
    width: 3rem;
    background-color: rgba(255,255,255,.3);
    position: absolute;
    top: 50%;
    left: -3rem
}

.item-folio__project-link:active,.item-folio__project-link:focus,.item-folio__project-link:hover {
    background-color: #dfbf5f;
    color: #fff
}

.item-folio__caption {
    display: none
}

.item-folio:hover .item-folio__thumb a::before {
    opacity: 1;
    visibility: visible
}

.item-folio:hover .item-folio__thumb a::after {
    opacity: 1;
    visibility: visible;
    -webkit-transform: scale(1);
    -ms-transform: scale(1);
    transform: scale(1)
}

.item-folio:hover .item-folio__project-link {
    opacity: 1;
    visibility: visible;
    -webkit-transform: translate3d(0,0,0);
    -ms-transform: translate3d(0,0,0);
    transform: translate3d(0,0,0)
}

.item-folio:hover .item-folio__text {
    opacity: 1;
    visibility: visible;
    -webkit-transform: translate3d(0,0,0);
    -ms-transform: translate3d(0,0,0);
    transform: translate3d(0,0,0)
}

@media only screen and (max-width: 1400px) {
    .item-folio__title {
        font-size:1.7rem
    }

    .item-folio__cat {
        font-size: 1.3rem
    }
}

@media only screen and (max-width: 1200px) {
    .s-works {
        padding-top:16.2rem
    }

    .item-folio__title {
        font-size: 1.8rem
    }

    .item-folio__cat {
        font-size: 1.4rem
    }
}

@media only screen and (max-width: 1000px) {
    .item-folio__title {
        font-size:1.7rem
    }

    .item-folio__cat {
        font-size: 1.3rem
    }
    .s-about .list .summary {
        width: unset;
    }
}

@media only screen and (max-width: 450px) {
    .item-folio {
        width:100%!important;
        float: none!important;
        clear: both!important;
        margin-left: 0;
        margin-right: 0
    }
}

.testimonials-wrap {
    margin-top: 7.8rem
}

.testimonials-header {
    text-align: center
}

.testimonials {
    font-family: proxima_nova,sans-serif;
    font-weight: 400;
    font-size: 1.8rem;
    line-height: 2;
    margin-top: 4.5rem;
    padding-bottom: 7.2rem;
    position: relative
}

.testimonials__slider {
    position: relative
}

.testimonials__slider .slick-slide {
    outline: 0
}

.testimonials__slider .slick-dots {
    display: block;
    list-style: none;
    width: 100%;
    padding: 0;
    margin: 4.5rem 0 0 0;
    text-align: center;
    position: absolute;
    top: 100%;
    left: 0
}

.testimonials__slider .slick-dots li {
    display: inline-block;
    width: 27px;
    height: 27px;
    margin: 0;
    padding: 9px;
    cursor: pointer
}

.testimonials__slider .slick-dots li button {
    display: block;
    width: 10px;
    height: 10px;
    line-height: 10px;
    border-radius: 50%;
    background: rgba(0,0,0,.4);
    border: none;
    padding: 0;
    margin: 0;
    cursor: pointer;
    font: 0/0 a;
    text-shadow: none;
    color: transparent
}

.testimonials__slider .slick-dots li button:focus,.testimonials__slider .slick-dots li button:hover {
    outline: 0
}

.testimonials__slider .slick-dots li.slick-active button,.testimonials__slider .slick-dots li:hover button {
    background: #000
}

.testimonials__slide {
    position: relative;
    padding-left: 12rem;
    padding-right: 3rem
}

.testimonials__icon {
    display: block;
    height: 3.3rem;
    width: 3.3rem;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: contain;
    position: absolute;
    top: 0;
    left: 5.5rem
}

.testimonials__author {
    display: inline-block;
    position: relative;
    padding-top: 1.5rem;
    padding-left: 9rem;
    min-height: 7.2rem
}

.testimonials__author span {
    display: block
}

.testimonials__avatar {
    width: 7.2rem;
    height: 7.2rem;
    border-radius: 100%;
    outline: 0;
    position: absolute;
    top: 0;
    left: 0
}

.testimonials__name {
    font-size: 1.6rem;
    font-weight: 700;
    line-height: 1.875rem;
    color: #000
}

.testimonials__position {
    font-size: 1.4rem;
    line-height: 2.7rem
}

@media only screen and (max-width: 1000px) {
    .testimonials__slide {
        text-align:center;
        padding: 0 6rem
    }

    .testimonials__icon {
        display: none
    }

    .testimonials__author {
        text-align: left
    }
}

@media only screen and (max-width: 800px) {
    .testimonials-wrap {
        margin-top:6rem
    }

    .testimonials {
        margin-top: 1.5rem
    }

    .testimonials__slide {
        padding: 0 3rem
    }
}

@media only screen and (max-width: 600px) {
    .testimonials-header h2 {
        font-size:3rem
    }

    .testimonials__slide {
        padding: 0 1.5rem
    }
}

@media only screen and (max-width: 500px) {
    .testimonials {
        font-size:1.6rem
    }

    .testimonials-header {
        padding: 0 10px
    }

    .testimonials-header h2 {
        font-size: 2.6rem
    }

    .testimonials__slide {
        padding: 0
    }

    .testimonials__author {
        padding-left: 8rem
    }

    .testimonials__avatar {
        width: 6rem;
        height: 6rem;
        top: .5rem
    }
}

.s-clients {
    padding-top: 18rem;
    padding-bottom: 18rem;
    background-color: #2a2a2a;
    position: relative
}

.s-clients a {
    color: #dfbf5f
}

.s-clients a:active,.s-clients a:focus,.s-clients a:hover {
    color: #fff
}

.clients-list {
    margin-top: 7.2rem
}

.item-client {
    border-color: rgba(255,255,255,.05);
    border-width: 1px;
    border-style: none solid solid none;
    text-align: center;
    padding: 2.4rem 0
}

.item-client a {
    display: block
}

.item-client img {
    -webkit-transform: scale(.65);
    -ms-transform: scale(.65);
    transform: scale(.65);
    -webkit-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out
}

.item-client:nth-child(4n) {
    border-style: none none solid none
}

.item-client:nth-last-child(-n+4) {
    border-bottom-style: none
}

.item-client a:hover img {
    -webkit-transform: scale(.8);
    -ms-transform: scale(.8);
    transform: scale(.8);
    opacity: 1
}

@media only screen and (max-width: 1000px) {
    .item-client {
        padding:1.5rem 0
    }

    .item-client img {
        -webkit-transform: scale(.6);
        -ms-transform: scale(.6);
        transform: scale(.6)
    }
}

@media only screen and (max-width: 800px) {
    .item-client:nth-child(n) {
        border-style:none solid solid none
    }

    .item-client:nth-child(3n) {
        border-style: none none solid none
    }

    .item-client:nth-last-child(-n+2) {
        border-bottom-style: none
    }
}

@media only screen and (max-width: 600px) {
    .clients-list {
        margin-top:6rem
    }

    .item-client:nth-child(n) {
        border-style: none solid solid none
    }

    .item-client:nth-child(2n) {
        border-style: none none solid none
    }

    .item-client:nth-last-child(-n+2) {
        border-bottom-style: none
    }
}

@media only screen and (max-width: 400px) {
    .clients-list {
        margin-top:3rem
    }
}

.s-stats {
    padding-top: 6.6rem;
    padding-bottom: 5.4rem;
    color: rgba(255,255,255,.5);
    background-color: #000;
    background-repeat: no-repeat;
    background-position: center bottom;
    background-size: cover;
    overflow: hidden;
    position: relative
}

.s-stats::before {
    content: "";
    display: block;
    background-color: #151515;
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    opacity: .6
}

.stats-block {
    text-align: center
}

.item-stats {
    margin: 5.4rem 0;
    padding: 0 2rem;
    position: relative;
    overflow: hidden;
    white-space: nowrap
}

.item-stats__count {
    font-family: proxima_nova,sans-serif;
    font-weight: 600;
    font-size: 9rem;
    line-height: 1;
    color: #fff;
    margin-bottom: 1.5rem
}

.item-stats h5 {
    font-size: 1.4rem;
    line-height: 1.714;
    text-transform: uppercase;
    letter-spacing: .25rem;
    color: rgba(255,255,255,.25);
    margin-top: 0
}

@media only screen and (max-width: 1200px) {
    .stats-block {
        max-width:900px
    }

    .item-stats {
        margin: 3rem 0
    }

    .item-stats__count {
        font-size: 8.8rem
    }
}

@media only screen and (max-width: 600px) {
    .item-stats__count {
        font-size:8.2rem
    }
}

@media only screen and (max-width: 400px) {
    .s-stats {
        padding-top:4.5rem;
        padding-bottom: 4.5rem
    }

    .item-stats__count {
        font-size: 8rem
    }
}

.s-contact {
    padding-top: 18rem;
    padding-bottom: 12rem;
    background-color: #151515;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    position: relative
}

.s-contact-prvi {
    padding-top: 18rem;
    padding-bottom: 12rem;
    background-color: #edf3f5;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: cover;
    position: relative
}

.s-contact .display-1 {
    margin: 0
}

.s-contact .display-1 a {
    color: #035d5c
}

.s-contact .display-1 a:active,.s-contact .display-1 a:focus,.s-contact .display-1 a:hover {
    color: #dfbf5f
}

.s-contact .contact-infos {
    background: rgba(0,0,0,.6)
}

.s-contact .form {
    padding: 50px 60px 70px
}

.s-contact .info {
    background: #000;
    padding: 50px 60px 70px
}

.s-contact .box {
    margin: 40px 0 0
}

.s-contact h4 {
    margin: 0;
    color: #fff;
    font-size: 1.2rem;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: .2em
}

.s-contact h5 {
    color: #dfbf5f;
    font-size: 1.8rem
}

.s-contact p {
    color: #8c8c8c;
    font-size: 1.6rem;
    line-height: 30px;
    font-weight: 300
}

.s-contact a {
    color: #dfbf5f
}

.s-contact a:active,.s-contact a:focus,.s-contact a:hover {
    color: #fff
}

.contact-infos {
    margin-top: 12rem;
    margin-bottom: 3rem;
    font-family: Roboto,sans-serif;
    font-weight: 400;
    font-size: 2.8rem;
    line-height: 1.714;
    color: #fff
}

.contact-infos [class*=contact-] {
    padding-bottom: 3rem
}

.contact-list {
    list-style: none;
    margin-left: 0
}

.contact-list a {
    color: #fff
}

.contact-list li {
    padding-left: 0
}

.contact-infos .box .in {
    line-height: normal
}

.contact-infos .email,.contact-infos .phone {
    color: #fff;
    font-size: 1.8rem;
    line-height: 0;
    font-family: proxima_nova,sans-serif;
    font-weight: 600
}

.contact-infos .social {
    position: relative;
    margin-right: 20px;
    line-height: 0;
    display: inline-block
}

.contact-infos .social img {
    height: 30px;
    width: 30px
}

.contact-infos .link {
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0
}

.contact-button {
    position: relative;
    padding-top: 6.6rem
}

.contact-button::before {
    content: "";
    display: block;
    height: 1px;
    width: 150px;
    background-color: rgba(255,255,255,.1);
    position: absolute;
    top: .6rem;
    left: 20px
}

.mc-form {
    margin-top: 2.1rem;
    width: 100%;
    position: relative
}

#mc-form-1 {
    margin-top: 2.1rem;
    width: 40vw;
    position: relative
}

.mc-form .help-block {
    font-size: 12px;
    color: red;
    transform: translateY(-16px)
}

.alert-boxx {
    font-size: 15px;
    text-align: center;
    padding-top: 30px;
    color: green
}

.mc-form input,.mc-form textarea {
    font-family: Roboto,sans-serif;
    color: #4f4f4f;
    width: 100%;
    height: 6.6rem;
    padding: 1.8rem 0 1.8rem 0;
    margin-bottom: 1.8rem;
    border: none;
    border-bottom: 1px solid #4f4f4f;
    background: 0 0;
    font-size: 1.5rem
}

.mc-form input.has-error,.mc-form textarea.has-error {
    border-bottom: 1px solid red
}

.mc-form input:focus {
    color: #4f4f4f
}

.mc-form input::-webkit-input-placeholder {
    color: #4f4f4f
}

.mc-form input:-moz-placeholder {
    color: #4f4f4f
}

.mc-form input::-moz-placeholder {
    color: #4f4f4f
}

.mc-form input:-ms-input-placeholder {
    color: #4f4f4f
}

.mc-form input.placeholder {
    color: #4f4f4f
}

.mc-form label {
    color: #fff;
    font-size: 1.3rem;
    padding: 0 2rem
}

.mc-form label i {
    padding-right: 6px
}

.mc-form textarea::-webkit-input-placeholder {
    color: #4f4f4f
}

.mc-form textarea::-moz-placeholder {
    color: #4f4f4f
}

.mc-form textarea:-ms-input-placeholder {
    color: #4f4f4f
}

.mc-form textarea:-moz-placeholder {
    color: #4f4f4f
}

@media only screen and (max-width: 1200px) {
    .s-contact {
        padding-top:16.2rem
    }

    .contact-infos {
        font-size: 2.6rem
    }

    .contact-number {
        clear: both
    }
}

@media only screen and (max-width: 900px) {
    .s-contact h4 {
        font-size:1.5rem
    }
}

@media only screen and (max-width: 800px) {
    .contact-infos {
        margin-top:7.2rem;
        font-size: 2.8rem
    }

    .contact-bottom {
        padding-top: 6rem;
        border-top: 1px solid rgba(255,255,255,.05)
    }

    .contact-button {
        padding-top: 0
    }

    .contact-button::before {
        display: none
    }

    .contact-subscribe {
        margin-top: 6rem
    }
}

@media only screen and (max-width: 600px) {
    .s-contact {
        padding-bottom:4.2rem
    }

    #mc-form-1 {
        margin: 0 auto;
        margin-top: 2.1rem;
        width: 80%;
        position: relative
    }

    .s-contact h4 {
        margin-bottom: 2.4rem
    }

    .contact-bottom {
        text-align: center
    }

    .mc-form input {
        padding: 1.8rem 30px 1.8rem 30px;
        text-align: center
    }

    .mc-form input {
        position: static;
        width: 100%;
        margin-bottom: 1.8rem
    }
}

@media only screen and (max-width: 500px) {
    .contact-infos {
        font-size:2.2rem
    }

    .contact-infos [class*=contact-] {
        padding-bottom: 1.5rem
    }
}

@media only screen and (max-width: 400px) {
    .contact-infos {
        font-size:1.8rem
    }
}

footer {
    font-family: Roboto,sans-serif;
    font-weight: 400;
    border-top: 1px solid rgba(255,255,255,.03);
    color: #4f4f4f;
    background: #000;
    position: relative
}

footer a,footer a:visited {
    color: #fff
}

.cl-copyright {
    font-size: 13px;
    letter-spacing: .1em;
    margin: 20px 0
}

.cl-go-top {
    position: fixed;
    bottom: 6rem;
    right: 6rem;
    z-index: 600;
    opacity: 0;
    transition: .5s
}

.cl-go-top.show {
    opacity: 1
}

@media only screen and (max-width: 600px) {
    .cl-go-top {
        position:absolute;
        top: 20px;
        right: 6rem;
        opacity: 1
    }
}

.cl-go-top a {
    text-decoration: none;
    border: 0 none;
    display: block;
    height: 50px;
    width: 50px;
    border-radius: 8px;
    line-height: 50px;
    text-align: center;
    background: #dfbf5f;
    color: #fff;
    text-align: center;
    text-transform: uppercase;
    -webkit-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out;
    background-repeat: no-repeat;
    background-position: center center;
    background-size: 10px 16px;
    box-shadow: 0 3px 10px rgba(0,0,0,.16)
}

.cl-go-top a:focus,.cl-go-top a:hover {
    background-color: #dfbf5f;
    color: #fff
}

@media only screen and (max-width: 1200px) {
    .cl-go-top {
        right:3rem;
        bottom: 3rem
    }
}

@media only screen and (max-width: 900px) {
    .cl-go-top {
        right:10px;
        bottom: 10px
    }

    .cl-go-top::after,.cl-go-top::before {
        display: none
    }
}

@media only screen and (max-width: 600px) {
    .cl-copyright {
        margin-top:9rem;
        padding: 0;
        text-align: center
    }

    .cl-copyright span {
        display: block
    }

    .cl-copyright span::after {
        display: none
    }

    .cl-go-top {
        right: 50%;
        margin-right: -30px
    }
}

@media only screen and (max-width: 400px) {
    .cl-copyright span {
        font-size:13px
    }
}

@media only screen and (min-width: 801px) {
    .cl-copyright .col-block.right {
        text-align:right
    }
}

.mc-form input[type=submit] {
    height: 6.6rem;
    line-height: 6.2rem;
    margin: 50px 0 0;
    color: #FFF;
    background: #dfbf5f;
    border-color: #dfbf5f;
    padding: 0 20px;
    border-radius: 100px;
}

@media only screen and (max-width: 801px) {
    .s-management,
    .s-range,
    .s-management,
    .s-oferta,
    .s-about,
    .s-contact  {
        padding-top: 8.2rem;
        padding-bottom: 4.1rem;
    }
    .map-markers {
        margin-top: 4.1rem;
    }

    #rijeka {
        display: none;
    }

    .mc-form input, .mc-form textarea {
        text-align: center;
    }

    .s-contact .form {
        padding-top: 50px !important;
    }

}


</style>
