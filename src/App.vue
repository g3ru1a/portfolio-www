<template>
  <div>
    <!-- <div id="nav">
        <router-link to="/">Home</router-link> |
        <router-link to="/about">About</router-link>
    </div> -->
    <router-view />
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200;300;400;500;600;700;800&display=swap');

* {
    @apply font-manrope;
}



@media only screen and (min-device-width: 960px) {

  /* width */
::-webkit-scrollbar {
  width: 7px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #f1f1f1; 
}
 
/* Handle */
::-webkit-scrollbar-thumb {
  background: #D55659; 
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #ad4747; 
}

}
</style>
