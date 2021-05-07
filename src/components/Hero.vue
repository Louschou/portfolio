<template>
    <div id="home">

        <h1>Louise Schou</h1>
        <transition
            appear
            @before-enter="beforeEnter"
            @enter="enter"
        >
        <h2>Multimediedesigner</h2>
        </transition>
        
            
    </div>
</template>

<script>
import gsap from 'gsap'

export default { 

    methods: {
        beforeEnter: (el) => {
            console.log('before enter - set initial state')
            el.style.transform = 'translateY(-60)'
            el.style.opacity = 0
        },
        enter: (el) => {
          console.log('starting to enter - make transition')
          gsap.to(el, {
                duration: 1,
                delay: 1,
                y: 0,
                opacity: 1,
                ease: "bounce.out", 
            })
        }
    },

  data: () => ({
      model: 0,
      colors: [
        'primary',
        'secondary',
        'yellow darken-2',
        'red',
        'orange',
      ],
    }),
}
</script> 


<style scoped>
    div {
        background-color: #F5EFEF;
        padding: 15em;
    }

    @media screen and (max-width: 768px) {
        div {
            padding: 1em;
        }
    }

    h1 {
        text-align: center;
        font-size: 70px;
    }

    h2{
        text-align: center;
        font-size: 40px;
    }
</style>