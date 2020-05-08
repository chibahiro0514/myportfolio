<template>
  <div class="contact-wrapper">

    <h2>Contact</h2>
    <h3 class="contact_message">Please choise contact tool as you like ...</h3>

    <div class="link">
      <a href="mailto:sho1228.k@gmail.com" class="link-icon"><font-awesome-icon icon="envelope" class="web-icon mail"/></a>
      <a href="https://github.com/chibahiro0514" class="link-icon"><font-awesome-icon :icon="['fab','github']" class="web-icon github"/></a>
      <a href="https://www.facebook.com/boogaloo.hiroakinagai" class="link-icon"><font-awesome-icon :icon="['fab','facebook']" class="web-icon facebook"/></a>
      <a href="https://www.instagram.com/chibahiro0514/" class="link-icon"><font-awesome-icon :icon="['fab','instagram']" class="web-icon instagram"/></a>
      <a href="https://twitter.com/chiba_hiro0514/" class="link-icon"><font-awesome-icon :icon="['fab','twitter']" class="web-icon twitter"/></a>
    </div>

  </div>

</template>

<style>
.contact-wrapper{
    text-align:center;
}
    
  
.link{
    display:inline-flex;
    width: 30%;
    justify-content: center;
}

.link-icon{
    margin: 0 10px;
    margin-bottom: 60px;
}

.web-icon{
    font-size: 2em;
    background-color: white;
    padding:0.3em;
    border-radius: 50%;
}

.web-icon:hover{
    color: white;
}

.twitter{
    color: #1DA1F2;
}
.twitter:hover{
    background-color: #1DA1F2;
}

.instagram{
    color: #f15245; 
}

.instagram:hover{
    background: radial-gradient(circle at 33% 100%, #fed373 4%, #f15245 30%, #d92e7f 62%, #9b36b7 85%, #515ecf);
    color:white;
}

.mail{
    color: #DD5144;
}
.mail:hover{
    background-color: #DD5144;
}

.github{
    color: #171515;
}
.github:hover{
    background-color: #171515;
}

.facebook{
    color: #4267B2;
}
.facebook:hover{
    background-color: #4267B2;
}

@media screen and (max-width: 768px){
    .web-icon{
        color:white;
    }

    .twitter{
        background-color: #1DA1F2;
    }

    .mail{
        background-color: #DD5144;
    }

    .github{
        background-color: #171515;
    }

    .hateblo{
        background-color: #193278;
    }
}
</style>