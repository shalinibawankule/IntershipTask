<!-- <template>
    <section>
            <img id="img1" src="../assets/PrekiletLogo.png" alt="Logo">
            <button id="button1id" class="mybutton"><i class="fas fa-user"></i> Sign in </button>
     

        
            <div class="heading">
                <h1>Welcome to Preskilet</h1>
                <h2>"Make Your Skills Shine with Preskilet"</h2>
                <h3>Create Video Resumes & Engage Students with Interactive Learning</h3>
                <button id="button2id" class="mybutton">Get started</button>
            </div>

            <div id="container2">
                <div id="box1">
                    <h2 id="about1"> </h2>
                    <p>
                        Welcome to preskilet, before you start creating your own videos for your live video profile, go
                        through a brief introduction of sections in our website, it will help you create profile easily.
                    </p>
                </div>
                <div id="box2"> </div>
            </div>
            <div id="box3"></div>
       

    </section>
</template>




<script>
export default {


}
</script>


<style>
body {
    /* background-color:rgb(145,200,228); */
    background-color: white;
}

#start {
    background-color: white;
}



img {
    height: 70px;
    position: absolute;
    top: 10px;
    right: 1000px;
    bottom: 0px;
    left: 10px;
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
}

#button1id {
    position: absolute;
    top: 30px;
    right: 50px;
    left: 1300px;
}

#button2id {
    position: absolute;
    top: 410px;
    right: 1030px;
    bottom: 250px;
    left: 300px;
}

.heading h1 {
    position: absolute;
    top:130px;
    right: 800px;
    left: 100px;
    font-size:45px;
    /* text-align: left; */
    font-weight: 600;
    color:black;
}

.heading h2 {
    position: absolute;
    top: 240px;
    right: 800px;
    bottom: 480px;
    left: 165px;

    text-align: left;
    font-weight: 200;
    font-size: 26px;
    margin: 20px 0;
    color: #0a66c2;

}
.heading h3{
    position: absolute;
    top: 290px;
    right: 700px;
 
    left: 10px;

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
    left: 750px;
}

#box1 {
    height: 320px;
    width: 450px;
    padding: 120px 130px 0px 0px;
    border: 0px solid white;
    background-color: #0a66c2;
    /* rgb(116, 155, 144); */
    /* border-width: 2px;
    border-style:solid; */
    border-radius: 10% 0% 0% 10%;
    color:white;
    /* position: relative;
    top: 2px;
    left: 800px; */

    align-content: start;
}

#about1 {
    text-align: center;
    font-weight: 700;
    font-style: arial;
    color: rgb(70, 130, 169);
}


#box2 {
    height: 420px;
    width: 180px;
    padding: 10px;
    border: 0px solid white;
    background-color: #c3edff;
    /* border-width: 2px;
    border-style:solid; */
    border-radius: 0% 10% 10% 0%;
  

    /* position: relative;
    top: 100px;
    right: 0px;
    bottom: 0px;
    left: 1300px; */
}

#box3 {
    height: 240px;
    width: 220px;
    padding: 10px;
    /* border: 1px solid rgb(226, 226, 226); */
    background-color: rgb(226, 226, 226);
    border-radius: 0% 10% 0% 10%;
    box-shadow: 5px 5px 2px black;

    position: relative;
    bottom: 330px;
    left: 1120px;

    background-image: url("https://jmdiacademy.com/wp-content/uploads/2023/01/ezgif.com-gif-maker-5.gif");
    background-size: cover;



/* Media queries */
/* Adjustments for smaller screens */
@media screen and (max-width: 1024px) {
    img {
        height: 50px;
        position: absolute;
        top: 10px;
        right: 10px;
        left: auto;
    }

    .heading h1 {
        font-size: 30px;
        top: 80px;
        right: 400px;
        left: 50px;
    }

    .heading h2 {
        top: 160px;
        right: 400px;
        left: 85px;
    }

    .heading h3 {
        top: 210px;
        right: 200px;
        left: 10px;
    }

    #button1id {
        top: 30px;
        right: 50px;
        left: auto;
    }

    #button2id {
        top: 370px;
        right: 300px;
        left: auto;
    }

    #container2 {
        width: 500px;
        left: 550px;
    }
}

/* Adjustments for smaller screens */
@media screen and (max-width: 768px) {
    img {
        height: 40px;
        position: absolute;
        top: 10px;
        right: 10px;
        left: auto;
    }

    .heading h1 {
        font-size: 25px;
        top: 60px;
        right: 200px;
        left: 30px;
    }

    .heading h2 {
        top: 130px;
        right: 200px;
        left: 50px;
    }

    .heading h3 {
        top: 180px;
        right: 50px;
        left: 10px;
    }

    #button1id {
        top: 30px;
        right: 20px;
        left: auto;
    }

    #button2id {
        top: 320px;
        right: 100px;
        left: auto;
    }

    #container2 {
        width: 400px;
        left: 350px;
    }
}

    
}
</style> -->


















<!-- <template>

    <section>
      <nav class="nav">
          <img class="logo" src="../assets/PrekiletLogo.png" alt="Logo" />
        <button id="btn">Sign Up</button>
      </nav>
  
      <div id="content">
        <div class="left-content">
          <div class="Heading">
            <div id="h1">Welcome to Preskilet</div>
            <div id="h2">Make Your Skills Shine with Preskilet</div>
            <div id="h3">
              Create Video Resumes & Engage Students with Interactive Learning
            </div>
            <button id="btn1">Get Started</button>
          </div>
          <div id="mid">
            <p>
              Welcome to preskilet, before you start creating your own videos for your
              live video profile, go through a brief introduction of sections in our
              website, it will help you create profile easily.
            </p>
          </div> 
        </div>
        <div class="right-content">
            <p>
              Welcome to preskilet, before you start creating your own videos for your
              live video profile, go through a brief introduction of sections in our
              website, it will help you create profile easily.
            </p>
        </div>
      </div>
    </section>
  </template>
  
  <script>
  export default {};
  </script>
  
  <style>
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
  }
  
  .nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #fff; /* Background color for the navigation */
  }
  
  .logo {
    height: 80px;
  }
  
  .logo img {
    height: 100px;
    padding: 10px;
  }
  
  #btn {
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: #0a66c2;
    border: 2px solid #0a66c2;
    border-radius: 25px;
    background-color: #fff;
    cursor: pointer;
  }
  
  #content {
    display: flex;
  }
  
  .left-content {
    flex: 1;
    padding: 20px;
    /* background-color: black; */
  }
  
  .right-content {
    flex: 1;
    background-color: #2480dc; /* Blue color applied only to this container */
    z-index: -1;
  }

  .right-content {
  flex: 1.5; /* Increase the flex value to occupy more space */
  background-color: #2480dc; /* Blue color applied only to this container */
  position: relative; /* Add position relative */
  text-align:center;
  color:white;
}

.right-content p{
    
}
  
  .Heading {
    text-align: center;
  }
  
  #h1 {
    font-size: 48px;
    /* color:white; */
  }
  
  #h2 {
    font-size: 24px;
    margin: 20px 0;
    color: #2480dc;
  }
  
  #h3 {
    font-size: 18px;
    color: #2480dc;
  }
  
  #mid {
    padding: 20px;
    background-color: black;
    top:200px;
    left:800px;
    right:20px;
  }
  
  #mid {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  padding: 20px;
  background-color: black;
  color: white; /* Adjust text color */
  z-index: 1; /* Ensure the #mid div appears above other content */
}

/* Adjustments to other styles as needed */


  #btn1 {
    margin-top: 50px;
    padding: 10px 20px;
    font-size: 16px;
    font-weight: bold;
    color: #fff;
    background-color: #0a66c2;
    border: none;
    border-radius: 25px;
    cursor: pointer;
  }
  
  /* Media queries for responsiveness */
  @media screen and (max-width: 768px) {
    .nav {
      flex-direction: column;
      align-items: flex-start;
    }
  
    .logo {
      margin-bottom: 10px;
    }
  
    #btn {
      margin-top: 10px;
    }
  
    #content {
      flex-direction: column;
      justify-content: center;
      text-align: center;
    }
  
    .left-content {
      padding: 10px;
    }
  
    .right-content {
      display: none; /* Hide the blue color container on smaller screens */
    }
  }
  </style>
   -->

<template>
    <section id="Start">
        <!-- //continer1 -->
        <div id="nav">
            <img id="img1" src="../assets/PrekiletLogo.png" alt="Logo" />
            <button id="button1id" class="mybutton">
                <i class="fas fa-user"></i> Sign in
            </button>
        </div>
        
        <!-- //container2 -->
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
    /* background-color:rgb(145,200,228); */
    background-color: white;
  }
  
  #nav{
     display:flex;
      align-items:center; 
      /* flex-wrap:wrap; */
      flex-direction:row;
      /* margin:auto; */
      width:100%;
      /* max-width: 1128px; */
      /* padding-left: 8px;
      padding-right: 8px; */
      justify-content: space-between;
  }
  
  #main{
    display: flex;
    height:500px;
    /* width:700px; */
     
      /* align-items: center; */
      /* flex-wrap: wrap; */
      flex-direction:row;
        width:100%;
      /* max-width: 1128px; */
      position: relative;
      align-items: center;
      
    
     
  }
  
  
  
  img {
    height: 70px;
    position: relative;
    /* top: 0px;
    right: 1000px;
    bottom: 0px;
    left: 10px; */
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
     /* top: 30px; */
  
    /* left: 1250px; */ 
    right: 50px;
  }
  
  #button2id {
    /* position: absolute;
    top: 400px;
    right: 1000px;
    bottom: 250px;
    left: 300px; */
    margin:10px
  }
  
  .container1{
    /* flex: 1 1 30rem; */
      background: white;
      padding: 1rem 2rem 2rem;
      border-radius: 2rem;
      text-align: center;
      /* border: 0.2rem solid gray; */
      transition: .5s ease;
  }
  
  .container1 h1 {
    /* position: absolute;
    top: 130px;
    right: 800px;
    left: 100px;*/
    font-size: 45px;
    text-align: center;
    font-weight: 600;
    color: black;
    padding:2px;
    margin:2px;
  
  }
  
  .container1 h2 {
    /* position: absolute;
    top: 240px;
    right: 800px;
    bottom: 480px;
    left: 165px; */
  
    text-align: center;
    font-weight: 200;
    font-size: 26px;
    margin: 20px 0;
    color: #0a66c2;
    padding:2px
  }
  .container1 h3 {
    /* position: absolute;
    top: 290px;
    right: 700px;*/
  
    /* left: 10px;  */
  
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
    /* rgb(116, 155, 144); */
    /* border-width: 2px;
      border-style:solid; */
    border-radius: 10% 0% 0% 10%;
    color: white;
    /* position: relative;
      top: 2px;
      left: 800px; */
  
    /* align-content: start; */
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
    /* border-width: 2px;
      border-style:solid; */
    border-radius: 0% 10% 10% 0%;
    z-index: -2;
    /* position: relative;
      top: 100px;
      right: 0px;
      bottom: 0px;
      left: 1300px; */
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







