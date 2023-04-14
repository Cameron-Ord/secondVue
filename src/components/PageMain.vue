<template>
    <div>
        <section class="section_main">
            <article class="article_main">
                <span class="images"><img
                        src="https://www.corydonanimalhospital.ca/wp-content/uploads/sites/80/2019/02/shutterstock_585457394.jpg"
                        alt="bird"></span>
                <span class="images"> <img
                        src="https://www.thesprucepets.com/thmb/MeHHEawFdQ9nfo0mw_7K_NyIQpg=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/cockatiels-as-pets-1236728-hero-78cbdaa2b96343a7bd3c11d4117fb931.jpg"
                        alt="a cockatiel"></span>
                <span class="images"> <img src="https://southwickszoo.com/wp-content/uploads/IMG_4245-scaled.jpg"
                        alt="a cute birdy"></span>
                <span class="images"> <img
                        src="https://petkeen.com/wp-content/uploads/2021/07/white-faced-cockatiel_Zdenka-Kincel_Shutterstock-760x507.webp"
                        alt="white faced cockatiel"></span>
            </article>
            <article class="article_main">
                <span class="images"><img
                        src="https://www.corydonanimalhospital.ca/wp-content/uploads/sites/80/2019/02/shutterstock_585457394.jpg"
                        alt="bird"></span>
                <span class="images"> <img
                        src="https://www.thesprucepets.com/thmb/MeHHEawFdQ9nfo0mw_7K_NyIQpg=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/cockatiels-as-pets-1236728-hero-78cbdaa2b96343a7bd3c11d4117fb931.jpg"
                        alt="a cockatiel"></span>
                <span class="images"> <img src="https://southwickszoo.com/wp-content/uploads/IMG_4245-scaled.jpg"
                        alt="a cute birdy"></span>
                <span class="images"> <img
                        src="https://petkeen.com/wp-content/uploads/2021/07/white-faced-cockatiel_Zdenka-Kincel_Shutterstock-760x507.webp"
                        alt="white faced cockatiel"></span>
            </article>
        </section>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.section_main {

    display: grid;

    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    
    justify-items: center;
    
    align-items: center;
}


.article_main {

    display: grid;

    grid-template-rows: 1fr 1fr 1fr 1fr;

    justify-items: center;

    align-items: center;
}


.images {

    display: grid;

    justify-items: center;

    align-items: center;

    background-color: #B2DFD5;

    width: 85%;

    border-radius: 25px;

    padding-bottom: 75px;

    padding-top: 75px;

    margin-bottom: 50px;

    margin-top: 50px;
}

p {

    width: 75%;
}

img {

    width: 75%;

    height: 100%;

    border-radius: 25px;

}


@media only screen and (min-width: 700px) {
    .section_main {

        grid-template-columns: repeat(auto-fit, minmax(500px, 2fr));
    }


}

@media only screen and (min-width: 1000px) {



    .section_main {

        grid-template-columns: repeat(auto-fit, minmax(700px, 2fr));
    }


    .article_main {

        display: grid;

        grid-template-columns: 2fr 2fr;

        max-height: 80vh;

        min-height: 80vh;

        justify-items: center;

        align-items: center;

    }

    .images {

        display: grid;

        justify-items: center;

        align-items: center;

        background-color: #B2DFD5;

        width: 85%;

        border-radius: 25px;

        padding-bottom: 75px;

        padding-top: 75px;

        margin-bottom: 50px;

        margin-top: 50px;
    }

}</style>