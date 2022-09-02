<template>    
    <div>
        <Header></Header>            
                <h1>Test Page</h1>
                <nuxt-link to="/">Home</nuxt-link>
                <Grid></Grid>                
        <Footer></Footer>   
    </div> 
</template>
<script>
import Grid from '../../components/Grid.vue';
import Header from '../../components/Header.vue';
import Footer from '../../components/Footer.vue';
    export default{ 
        components: { Grid,Header,Footer },        
        head(){
            return{
            title: 'About the App',
            meta: [
            {
                hid:'description',
                name:'descrpition',
                content: "The place with Test"
            }
            ]
            }
        }
    };
</script>

<style>

</style>