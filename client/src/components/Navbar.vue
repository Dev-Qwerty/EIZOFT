<template>
<div id=nav>
    <router-link class="nav-item-main" :to="{ path: '/' }">EIZOFT</router-link>
    <router-link class="nav-item-sub" :to="{ path: '/about' }">ABOUT</router-link>
    <router-link class="nav-item-sub" :to="{ path: '/team' }">TEAM</router-link>
</div>
  
</template>

<style>
#nav {
    display: grid;
    grid-template-columns: 5fr 1fr 1fr;
    margin-left: 75px;
    align-items: center;
}
#nav:after {
    content: ""; /* This is necessary for the pseudo element to work. */ 
    display: block; /* This will put the pseudo element on its own line. */
    margin: 0 auto; /* This will center the border. */
    width: 126%; /* Change this to whatever width you want. */
    border-bottom: 1px solid #3c1053; /* This creates the border. Replace black with whatever color you want. */
}
.nav-item-main,.nav-item-sub {
    text-decoration: none;
    color: white;
}
.nav-item-main {
    font-size: 41px;
    font-family:'Acme', Avenir, Helvetica, Arial, sans-serif;
}
.nav-item-sub{
    font-size: 32px;
    font-family:'Teko', Avenir, Helvetica, Arial, sans-serif;
}
</style>

