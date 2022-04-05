<template>
    <div class="container"> 
        <h1 class="head">Profile </h1>
        <p class="para">I am Creative Web Developer </p>
        <div class="photo">
        </div>
        <div class="about-me">
            <h4 class="h4">About Me </h4>
            <p>I am creative Web Developer. I am expert in javaScript and Ui Frame-Works like Vue and React. Worked With Various types of clients.  </p>
        </div>
        <div class="details">
            <h4>Details </h4>
            <p> <b>Name: </b> </p>
            <p>Abhilash Nyamagoud </p>
            <p><b>Age: </b> </p>
            <p>25 Years </p>
             <p><b>Location: </b> </p>
              <p>Bangalore </p>
              <p><b>Mobile: </b> </p>
              <p>8792655457 </p>
              <p><b>Email: </b> </p>
              <p>abhilashnyamagoud7999@gmail.com</p>
        </div>
    </div>
</template>

<script>
    export default {
        
    }
</script>

<style lang="css" scoped>
    .head{
        font-family: fantasy;
        letter-spacing: 3px;
        /* margin-top: 20px; */
    }
    .para{
        font-family: cursive;
        font-size: 20px;
    }
    .photo{
        background: url('./abhi1.png');
        width: 150px;
        height: 150px;
        background-size: cover;
       border-radius: 60px;
        margin: 0 auto;
    }
    .about-me{
        background: rgb(95, 95, 212);
        padding:10px 50px 50px 50px;
        width: 50%;
        height: 50%;
        margin: 20px auto;
        color: white;
        font-family: monospace;
    }
    .h4{
        font-family: cursive;
    }
    .details{
        color: black;
        font-family:monospace;
    }
</style>