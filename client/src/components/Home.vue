<template>
    <div class="container">
        <div class="title">
            <p>Together We 
            <vue-typer
                :text='["Code.","Create.","Build."]'
                :repeat='Infinity'
                :shuffle='false'
                initial-action='typing'
                :pre-type-delay='500'
                :type-delay='120'
                :pre-erase-delay='2000'
                :erase-delay='120'
                erase-style='backspace'
                :erase-on-complete='false'
                caret-animation='expand'
            ></vue-typer>
        </p>
        </div>
    </div>
</template>


<style>
.container {
    display: grid;
    justify-content: center;
    margin-top: 19%;
}


.title > p {
    color: white;
    font-size: 80px;
    margin: 0% auto;
    font-family:'Dancing Script', cursive, Avenir, Helvetica, Arial, sans-serif;
}

.vue-typer .custom.char.typed {
    color:white;
}

/* .vue-typer .custom.caret {
  display: none;
} */

.vue-typer .custom.caret {
  width: 3px;
  background-color: white;
}

</style>

