<template>
    <section id="Start">
     
        <div id="nav">
            <img id="img1" src="../assets/PrekiletLogo.png" alt="Logo" />
            <button id="button1id" class="mybutton">
                <i class="fas fa-user"></i> Sign in
            </button>
        </div>
        
     
        <div id="main">
                    <div class="container1">
                        <h1>Welcome to Preskilet</h1>
                        <h2>"Make Your Skills Shine with Preskilet"</h2>
                        <h3>
                        Create Video Resumes & Engage Students with Interactive Learning
                        </h3>
                        <button @click="toggleNewComponents" id="button2id" class="mybutton">Get started  </button>
                        <new-component v-if="showNewComponent" />
                    </div>
  
  
                    <div id="container2">
                        <div id="box1">
                            <h2 id="about1"></h2>
                            <p>
                            Welcome to preskilet, before you start creating your own videos for
                            your live video profile, go through a brief introduction of sections
                            in our website, it will help you create profile easily.
                            </p>
                        </div>
                       
                        <div id="box2"></div> 
                      
                    </div>
                    <div id="box3"></div>
  
  
    </div>
  
    </section>
  </template>
  
  <script>

  export default {
   
    },
    
 
  </script>
  
  <style>
  body {
    background-color: white;
  }
  
  #nav{
        display:flex;
        align-items:center; 
        flex-direction:row;
        width:100%;
        justify-content: space-between;
  }
  
  #main{
    display: flex;
    height:500px;
    flex-direction:row;
    width:100%;
    position: relative;
     align-items: center;   
  }
  
  
  
  img {
    height: 70px;
    position: relative;
  }
  
  .mybutton {
    height: min-content;
    min-height: 48px;
    border-radius: 24px;
    padding-top: 12px;
    padding-bottom: 12px;
    padding-left: 24px;
    padding-right: 24px;
    text-align: center;
    font-size: 16px;
    font-weight: 600;
    line-height: 1.25;
    color: white;
    border: 2px solid white;
    background-color: #0a66c2;
  }
  .mybutton:hover {
    background-color: #c3edff;
    color: #0a66c2;
    border: 2px solid #0a66c2;
    cursor:pointer;
  }
  #button1id {
    position: relative;
    right: 50px;
  }
  
  #button2id {
    margin:10px
  }
  
  .container1{
      background: white;
      padding: 1rem 2rem 2rem;
      border-radius: 2rem;
      text-align: center;
      transition: .5s ease;
  }
  
  .container1 h1 {
    font-size: 45px;
    text-align: center;
    font-weight: 600;
    color: black;
    padding:2px;
    margin:2px;
  
  }
  
  .container1 h2 {
    text-align: center;
    font-weight: 200;
    font-size: 26px;
    margin: 20px 0;
    color: #0a66c2;
    padding:2px
  }
  .container1 h3 {
    text-align: center;
    font-weight: 100;
    font-size: 16px;
    color: #0a66c2;
  }
  
  #container2 {
    height: 500px;
    width: 650px;
    display: flex;
    flex-direction: row;
    /* border: 1px solid black; */
    align-items: center;
  
    position: relative;
    top: 50px;
    left: 250px;
  }
  
  #box1 {
    height: 320px;
    width: 450px;
    padding: 120px 130px 0px 0px;
    border: 0px solid black;
    background-color: #0a66c2;
    border-radius: 10% 0% 0% 10%;
    color: white;
    z-index: -2;
  }
  
  #about1 {
    text-align: center;
    font-weight: 700;
    font-style: arial;
    color: rgb(70, 130, 169);
  }
  
  #box2 {
    height: 420px;
    width: 280px;
    padding: 10px;
    border: 0px solid black;
    background-color: #c3edff;
    border-radius: 0% 10% 10% 0%;
    z-index: -2;
  }
  
  #box3 {
    height: 240px;
    width: 220px;
    padding: 10px;
    border: 1px solid rgb(226, 226, 226);
    background-color: rgb(226, 226, 226);
    border-radius: 0% 10% 0% 10%;
    box-shadow: 5px 5px 2px black;
  
    position: relative;
    top:50px;
    right:80px;
  
    background-image: url("https://jmdiacademy.com/wp-content/uploads/2023/01/ezgif.com-gif-maker-5.gif");
    background-size: cover;
  }
  </style>







