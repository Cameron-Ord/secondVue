<template>
    <section class="section_main">
        <article class="article_main">
            <span class="span_main">
                <h1>Welcome</h1>
                <p>I don't know what to put here so I'll just put a pic of some birdies</p>
                <img src="https://www.corydonanimalhospital.ca/wp-content/uploads/sites/80/2019/02/shutterstock_585457394.jpg" alt="carp brut">
            </span>
            <span class="images"> <img src="https://www.thesprucepets.com/thmb/MeHHEawFdQ9nfo0mw_7K_NyIQpg=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/cockatiels-as-pets-1236728-hero-78cbdaa2b96343a7bd3c11d4117fb931.jpg" alt="a cockatiel"></span>
            <span class="images"> <img src="https://southwickszoo.com/wp-content/uploads/IMG_4245-scaled.jpg" alt="a cute birdy"></span>
            <span class="images"> <img src="https://petkeen.com/wp-content/uploads/2021/07/white-faced-cockatiel_Zdenka-Kincel_Shutterstock-760x507.webp" alt="white faced cockatiel"></span>
        </article>
    </section>
</template>

<script>
export default {

}
</script>

<style scoped>
.section_main{

    display: grid;
   

    justify-items: center;
    align-items: center;
}

.article_main{

    display: grid;
    grid-template-rows: 1fr 1fr 1fr 1fr;

    justify-items: center;
    align-items: center;
}

.span_main{


    margin-bottom: 50px;

    margin-top: 50px;
    
    display: grid;
    
    justify-items: center;

    align-items: center;

    text-align: center;

    grid-template-rows: 50px 100px 1fr 50px;

    background-color: #B2DFD5;

    width: 85%;

    border-radius: 25px;

}

.images{

    display: grid;
    
    justify-items: center;

    align-items: center;

    background-color: #B2DFD5;

    width: 85%;

    border-radius: 25px;

    padding-bottom: 75px;

    padding-top: 75px;
}
p{

    width: 75%;
}

img{

width: 75%;
height: 100%;
border-radius: 25px;

}
</style>