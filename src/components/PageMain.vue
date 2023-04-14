<template>
    <section class="section_main">
        <article class="article_main">
            <span class="span_main">
                <h1>Welcome</h1>
                <p>I don't know what to put here so I'll just put a pic of some birdies</p>
                <img src="https://www.corydonanimalhospital.ca/wp-content/uploads/sites/80/2019/02/shutterstock_585457394.jpg" alt="carp brut">
            </span>

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

    justify-items: center;
    align-items: center;
}

.span_main{

    display: grid;
    
    justify-items: center;

    align-items: center;

    text-align: center;

    grid-template-rows: 50px 100px 1fr;

}


p{

    width: 75%;
}

img{

width: 75%;
height: 100%;


}
</style>