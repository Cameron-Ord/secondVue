

<template>
  <div>
    <header id="PageHeader">
      <page-header></page-header>
    </header>
    <main id="PageMain">
      <page-main></page-main>
    </main>
    <footer id="PageFooter">
      <page-footer></page-footer>
    </footer>
  </div>
</template>



<script>
import PageHeader from './components/PageHeader.vue';
import PageMain from './components/PageMain.vue';
import PageFooter from './components/PageFooter.vue';
export default {
  name: 'App',
  components: {
 PageHeader,
 PageMain,
 PageFooter
  }
}
</script>



<style>


*{


  padding: 0px;
  margin: 0px;
}


body{

background-color: #ECEBDA;

}

#PageHeader{
min-height: 10vh;
display: grid;
background-color: #B2DFD5;
grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
}

#PageMain{
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  display: grid;
  min-height: 80vh;
}


#PageFooter{
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
min-height: 10vh;
  display: grid;
  background-color: #B2DFD5;



}

@media only screen and (min-width:  700px){


  #PageHeader{
    grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
}


  #PageMain{
  grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));

}

  #PageFooter{
  grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));

  }

}

@media only screen and (min-width: 1000px){

  #PageHeader{
grid-template-columns: repeat(auto-fit, minmax(700px, 1fr));
}

#PageMain{
  grid-template-columns: repeat(auto-fit, minmax(700px, 1fr));


  min-height: 70vh;
}


#PageFooter{
  grid-template-columns: repeat(auto-fit, minmax(700px, 1fr));


  min-height: 10vh;
  
}
}
</style>
