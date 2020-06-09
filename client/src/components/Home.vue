<template>
    <div class="container">
        <h1>EIZOFT TECHNOLOGIES</h1>
        <p>Together We Create</p>
    </div>
</template>


<style scoped>
.container {
    display: grid;
    justify-content: center;
    align-content: center;
}
.container > h1 {
    font-size: 55px;
    margin-top: 32%;
    color: white;
    font-family:'Audiowide', cursive, Avenir, Helvetica, Arial, sans-serif;
    
}
.container > h1:after {
    content: ""; /* This is necessary for the pseudo element to work. */ 
    display: block; /* This will put the pseudo element on its own line. */
    margin: 0 auto; /* This will center the border. */
    width: 50%; /* Change this to whatever width you want. */
    padding-top: 5px; /* This creates some space between the element and the border. */
    border-bottom: 3px solid white; /* This creates the border. Replace black with whatever color you want. */
}
.container > p {
    color: white;
    font-size: 55px;
    margin: 0% auto;
    font-family:'Dancing Script', cursive, Avenir, Helvetica, Arial, sans-serif;
}
</style>

