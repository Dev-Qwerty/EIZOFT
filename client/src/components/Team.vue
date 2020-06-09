<template>
    <div class="container">
        <div class="heading">
            <h1>MEET THE TEAM</h1>
        </div>
        <div class="team">
            <di class="team-row-1">
                <div class="member">
                <img src="../assets/afif-ashraf.jpeg">
                <h5>AFIF C ASHRAF</h5>
                <p>UI/UX Designer</p>
            </div>
            <div class="member">
                <img src="../assets/alan-mathew.jpeg">
                <h5>ALAN MATHEW</h5>
                <p>Frontend Developer</p>
            </div>
            <div class="member">
                <img src="../assets/albin-jose.png">
                <h5>ALBIN JOSE</h5>
                <p>Backend Developer</p>
            </div>
            <div class="member">
                <img src="../assets/amal-jose.jpeg">
                <h5>AMAL JOSE</h5>
                <p>Backend Developer</p>
            </div>
            </di>
            <div class="team-row-2">
                <div class="member">
                <img src="../assets/aneesh-jose.jpeg">
                <h5>ANEESH JOSE</h5>
                <p>Flutter Developer</p>
            </div>
            <div class="member">
                <img src="../assets/james-kaviyil.jpeg">
                <h5>JAMES KAVIYIL JOSE</h5>
                <p>MEVN Stack Developer</p>
            </div>
            <div class="member">
                <img src="../assets/christy-oommen.png">
                <h5>CHRISTY OOMMEN VARGHESE</h5>
                <p>Frontend Developer</p>
            </div>
            </div>
            
        </div>
    </div>
</template>

<style scoped>
.container {
    display: grid;
    margin-top: 35px;
}

.heading {
    display: flex;
    justify-content: center;
    font-family:'Balsamiq Sans', cursive, Avenir, Helvetica, Arial, sans-serif;
   
}
.heading > h1{
    color: white;
    font-size: 50px;
}
img {
    width: 160px;
    border-radius: 50%;
}
.team {
    display: grid;
    grid-template-rows: 1fr 1fr;
    grid-row-gap: 85px;
    margin-top: 25px;
}
.team-row-1 {
    display: flex;
    justify-content: space-evenly;
}
.team-row-2 {
    display: flex;
    justify-content: space-evenly;
}
.member {
    color: white;
    text-align: center;
    
}
.member > h5 {
    font-family:'Bellota Text', cursive, Avenir, Helvetica, Arial, sans-serif;
    font-size: 20px;
    margin-bottom: 15px;
}
.member > p {
    font-family: 'Merriweather', serif, Avenir, Helvetica, Arial, sans-serif;;
    font-size: 15px;
}
</style>