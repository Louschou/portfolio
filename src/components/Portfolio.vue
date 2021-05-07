<template>
  <section>
    <div id="about">
      <v-row>
        <v-col cols="12" md="9">
          <v-row>
            <v-col md="3"></v-col>
            <v-col cols="12" md="3">
              <h3 class="pt-5 text--center">Hvem er jeg?</h3>
            </v-col>
            <v-col md="2"></v-col>
          </v-row>
          <v-row>
            <v-col md="3"></v-col>
            <v-col cols="12" md="8">
              <transition appear @before-enter="beforeEnter" @enter="enter">
                <p>
                  Mit navn er Louise Schou, jeg er 24 år gammel og bor i Varde.
                  Til dagligt studerer jeg til multimediedesigner på
                  Erhvervsakademi SydVest i Esbjerg, da jeg ønsker at blive
                  klogere på, og videreudvikle mine evner inden for den kreative
                  og digitale verden. På uddannelsen har mit hovedfokus og
                  interesse især været på SoMe content, fotografi/videografi,
                  kommunikation og digitale medier, hvorfor jeg også søger
                  udfordringer inden for dette område. Som person opfatter jeg
                  mig selv som en kreativ, loyal, ansvarsbevidst og
                  reflekterende sjæl, hvilket også kommer til udtryk i, at jeg
                  altid har øje for detaljer og overholder deadlines. Så udforsk
                  mit portfolie, hvor du finder alt lige fra små faglige
                  projekter fra studiet til mere personlige ting, herunder min
                  interesse for fotografi og rejser.
                </p>
              </transition>
            </v-col>
            <v-col md="2"></v-col>
          </v-row>
          <v-row class="mb-10">
            <v-col class="text-center">
              <v-btn
                class="mr-5"
                href="https://youtu.be/XvcYgLHd-wU"
                target="_blank"
                >Video CV</v-btn
              >
              <v-btn href="files/CanvasCVpdf.pdf" target="_blank">CV</v-btn>
            </v-col>
          </v-row>
        </v-col>
        <v-col cols="12" md="3">
          <img
            id="portofolio-img"
            class="pt-10 mr-3"
            src="../assets/Rundt billede port.png"
          />
        </v-col>
      </v-row>
    </div>

    <div id="pictures">
      <a name="Pictures"></a>
      <!-- Billeder starter her -->
      <v-container>
        <v-row>
          <v-col cols="12">
            <h2 class="pt-5 text--center">Portfolio</h2>
          </v-col>
        </v-row>
        <v-row>
          <v-col columns="4"
            ><v-img
              contain
              max-height="550"
              max-width="320"
              src="../assets/Signup.png"
            ></v-img
          ></v-col>
          <v-col columns="4"
            ><v-img
              contain
              max-height="550"
              max-width="450"
              src="../assets/treting.png"
            ></v-img
          ></v-col>
          <v-col columns="4"
            >
            
                <v-img
                contain
                max-height="700"
                max-width="380"
                src="../assets/Hjerting.png"
                ></v-img>

                <a href="files/HjertingBrochure.pdf" target="_blank">Åbn for at læse brochure</a>
          </v-col>
        </v-row>
      </v-container>
    </div>

    <div id="photos">
        <h2 class="pt-5 text--center">Fotografi</h2>
<v-row>
  
          <v-col cols="3"
            ><v-img
              contain
              max-height="400"
              max-width="600"
              src="../assets/Vandfaldphoto.jpg"
            ></v-img
          ></v-col>
          <v-col cols="3"
            ><v-img
              contain
              max-height="400"
              max-width="600"
              src="../assets/Mexicotempel.jpg"
            ></v-img
          ></v-col>
          <v-col cols="3"
            >
             <v-img
                contain
                max-height="400"
                max-width="600"
                src="../assets/pinkvand.jpg"
                ></v-img>
          </v-col>
          <v-col cols="3">
                <v-img
                contain
                max-height="400"
                max-width="600"
                src="../assets/kelingkingphoto.jpg"
                ></v-img>
                

          </v-col>
<v-col cols="3"
            ><v-img
              contain
              max-height="400"
              max-width="600"
              src="../assets/filiview.jpg"
            ></v-img
          ></v-col>
          <v-col cols="3"
            ><v-img
              contain
              max-height="400"
              max-width="600"
              src="../assets/kokos.jpg"
            ></v-img
          ></v-col>
          <v-col cols="3"
            >
             <v-img
                contain
                max-height="400"
                max-width="600"
                src="../assets/palmestrand.jpg"
                ></v-img>
          </v-col>
          <v-col cols="3">
                <v-img
                contain
                max-height="400"
                max-width="600"
                src="../assets/costaricabeach.jpg"
                ></v-img>
                

          </v-col>
<v-col cols="3"
            ><v-img
              contain
              max-height="400"
              max-width="600"
              src="../assets/Orangeblad.jpg"
            ></v-img
          ></v-col>
          <v-col cols="3"
            ><v-img
              contain
              max-height="400"
              max-width="600"
              src="../assets/Tempellodret.jpg"
            ></v-img
          ></v-col>
          <v-col cols="3"
            >
             <v-img
                contain
                max-height="400"
                max-width="600"
                src="../assets/orangeblomster.jpg"
                ></v-img>
          </v-col>
          <v-col cols="3">
                <v-img
                contain
                max-height="400"
                max-width="600"
                src="../assets/Cubadame.jpg"
                ></v-img>
                

          </v-col>
          <v-col cols="3"
            ><v-img
              contain
              max-height="400"
              max-width="600"
              src="../assets/Aber.jpg"
            ></v-img
          ></v-col>
          <v-col cols="3"
            ><v-img
              contain
              max-height="400"
              max-width="600"
              src="../assets/kiwiphoto.jpg"
            ></v-img
          ></v-col>
          <v-col cols="3"
            >
             <v-img
                contain
                max-height="400"
                max-width="600"
                src="../assets/blomster.jpg"
                ></v-img>
          </v-col>
          <v-col cols="3">
                <v-img
                contain
                max-height="400"
                max-width="600"
                src="../assets/sanjose.jpg"
                ></v-img>
                

          </v-col>
          <v-col cols="6"
            ><v-img
              contain
        
              src="../assets/Vietnamdameikano.jpg"
            ></v-img
          ></v-col>
          <v-col cols="6"
            ><v-img
              contain
              
          
              src="../assets/Halongbayfoto.jpg"
            ></v-img
          ></v-col>
          <v-col cols="6"
            >
             <v-img
                contain
                src="../assets/munke.jpg"
                ></v-img>
          </v-col>
          <v-col cols="6">
                <v-img
                contain
                src="../assets/Vietnamdamerfoto.jpg"
                ></v-img>
                

          </v-col>
        </v-row>
        <v-row>
        </v-row>
        
    </div>
    <div id="kontakt">

      <v-container class="pt-16">
        <v-row>
          <v-col cols="6">
            <h2 class="pt-5 text-left">Kontakt</h2>
            <h5 class="pt-5 pb-10 text--center">Vil du i kontakt med mig, er du velkommen til at kontakte mig på nedenstående addresser:</h5>
            <p class="tekst"> Mail: Louise.schou23@gmail.com </p>
            <p class="tekst"> LinkedIn: //Louise Schou </p>
            <p class="tekst"> Tlf: + 45 22 44 41 12 </p>
            <p class="tekst"> Varde, Danmark </p>
          </v-col>
          <v-col cols="6" class="text-left">
            <v-img
              contain
              max-height="400"
              max-width="450"
              src="../assets/billedeCVV.jpg"
              ></v-img>
          </v-col>
        </v-row>
      </v-container>

      



    </div>
  </section>
  
</template>

<script>
import gsap from "gsap";

export default {
  methods: {
    beforeEnter: (el) => {
      console.log("before enter - set initial state");
      el.style.transform = "translateY(-60)";
      el.style.opacity = 0;
    },
    enter: (el) => {
      console.log("starting to enter - make transition");
      gsap.to(el, {
        duration: 1,
        delay: 1,
        y: 0,
        opacity: 1,
        ease: "bounce.out",
      });
    },
  },

  data: () => ({
    model: 0,
    colors: ["primary", "secondary", "yellow darken-2", "red", "orange"],
  }),
};
</script> 


<style scoped>
#photos {
    background-color: #F5EFEF;
    text-align: center;
    font-size: 40px;
}

#kontakt  {
  background-color: #FFFF;
  text-align: center;
  font-size: 20px;
}
#pictures {
  background-color: white;
}

#portofolio-img {
  width: 80%;
}
#about {
  background-color: #fbc1b5;
  /* padding: 15em;*/
}
h1 {
  text-align: center;
  font-size: 70px;
}

h2 {
  text-align: center;
  font-size: 40px;
}
h5 {
  text-align: left;
}
h6 {
  text-align: left;
}
.tekst {font-size: 15px;
text-align: left;}
</style>