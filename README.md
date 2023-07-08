
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>EDUCA - LEARN ONLINE</title>
    <!-- <link rel="stylesheet" href="style.css" /> -->
    <style>
      @import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300;500&display=swap');
*{
    margin: 0;
    padding: 0;
}
html{
    scroll-behavior: smooth;
}
.navbar{
    display: flex;
    align-items: center;
    justify-content: center;
    position: sticky;
    top: 0;
    cursor: pointer;
    /* height: 500px; */
}
.nav-list{
    width: 70%;
    /* background-color: black; */
    display: flex;
    align-items: center;
}
.nav-list li{
    list-style: none;
    padding: 23px 23px;
    /* margin: 23px; */
}
.nav-list li a{
    text-decoration: none;
    color: white;
    font-family: 'Ubuntu', sans-serif;
    font-size: 20px;
}
.nav-list li a:hover{
    text-decoration: underline;
    color: yellow;
}
.logo {
    margin: 10px;
    justify-content: center;
    align-items: center;
    height: 100px;
    width: 100px;
}
.logo img{
    height: 70px;
    width: 70px;
    border: 2px solid white;
    border-radius: 50px;
}
.rightnav{
    /* background-color: blueviolet; */
    width: 30%;
    text-align: right;
    padding: 0 23px;
}

#search{
    padding: 5px;
    font-size: 18px;
    border: 2px solid white;
    border-radius: 10px;
}
.background{
    background: rgba(0, 0, 0, 0.7) url('https://source.unsplash.com/1600x900/?buildings,collegecampus');
    background-size: cover;
    background-blend-mode: darken;
}

.firstsection{
    height: 100vh;;
}

.box-main {
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
    max-width: 100%;
    margin: auto;
    height: 85%;
}
.shalf img{
    /* height: 70%; */
    width: 20rem;
    /* padding: 10px; */
    border: 4px solid white;
    /* border-radius: 200px; */
    display: block;
    margin: auto;
}

.fhalf{
    width: 80%;
    display: flex;
    justify-content: center;
    flex-direction: column;
}

.shalf{
    width: 30%;
}

.text-big{
    text-transform: capitalize;
    font-size: 38px;
    margin: 3px;
    text-align: center;
}

.text-small {
    margin: 10px;
    text-align: center;
    font-size: 18px;
}

.buttons{
    display: flex;
    align-items: center;
    justify-content: center;
}
.btn-sm{
    padding: 6px 10px ;
    vertical-align: middle;
}

.btn {
    text-decoration: none;
    background: transparent;
    border-radius: 10px;
    border: 2px solid white;
    padding: 5px 15px;
    margin: 10px 3px;
    color: white;
    cursor: pointer;
    font-family: 'Ubuntu', sans-serif;
    font-size: 18px;
}

.dark{
    color: black;
    border: 2px solid grey;
}
.dark:hover{
    color: white;
    background-color: black;
    text-decoration: underline;
    border: 2px solid burlywood;
}

.section{
    margin: auto;
    max-width: 100%;
    /* height: 500px; */
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    font-family: 'Ubuntu', sans-serif;
}
.left{
    flex-direction: row-reverse;
}
.para{
    padding: 0 70px;
}

.imgfluid{
    width: 30rem;
    margin: 1rem;
    border: 2px solid black;
}

.section-tag{
    padding: 16px 0px;
}
.section-subtag{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}

.contact{
    background-color: #f6f5f4;
    height: 100vh;
}

.textcentre{
    font-size: 40px;
    text-align: center;
    padding: 20px;
    font-family: 'Ubuntu', sans-serif;
}

.form{
    max-width: 62%;
    margin: 16px auto;
}

.form-input{
    text-align: center;
    padding: 3px 3px;
    margin: 16px 0px;
    width: 100%;
    font-size: 17px;
    border: 2px solid grey;
    border-radius: 10px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
.textfooter{
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 40px;
    padding: 20px;
    font-family: 'Ubuntu', sans-serif;
    color: white;
}
.burger{
    display: none;
position: absolute;
cursor: pointer;
right: 5px;
top: 15px;
}

.line{
    width: 33px;
    height: 4px;
    background-color: wheat;
    margin: 5px;
}

@media only screen and (max-width: 1518px) {
    .nav-list{
        flex-direction: column;
    }
    .navbar{
        flex-direction: column;
        transition: all 1.5s ease-out;
        height: 480px;
        }
    .rightnav{
        text-align: center;
    }
    #search{
        width: 100%;
    }
    .burger{
        display: block;
    }
    .h-nav-resp{
        height: 72px;
    }
    .v-class-resp{
        opacity: 0;
    }
    .box-main{
        flex-direction: column;
        width: 100%;
    }
    .section{
        flex-direction: column-reverse;
    }
    .image{
        margin: 0;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .text-small .text-small .buttons{
        text-align: center;
    }
    /* .text-big{
        text-align: center;
    }
    .buttons{
        text-align: center;
    } */
    .para{
        padding: 0;
    }
    .imgfluid{
        width: 20rem;
        margin: 1rem;
        border: 2px solid black;
    }
    .shalf{
        width: 100%;
    }
}

    </style>
  </head>
  <body>
    <nav class="navbar background h-nav-resp " >
      <div class="burger">
        <div class="line"></div>
        <div class="line"></div>
        <div class="line"></div>
      </div>
      <ul class="nav-list v-class-resp ">
        <div class="logo"><img src="https://source.unsplash.com/1600x900/?educationlogo,school" alt="logo" /></div>
        <li><a href="#main">HOME</a></li>
        <li><a href="#about">ABOUT</a></li>
        <li><a href="#services">SERVICES</a></li>
        <li><a href="#contact">CONTACT US</a></li>
      </ul>
      <div class="rightnav v-class-resp">
        <input type="text" name="search" id="search" />
        <button class="btn btn-sm">Search</button>
      </div>
    </nav>

    <section class="background firstsection">
      <div class="box-main" id="main">
        <div class="fhalf">
          <p class="text-big">The future of education is here</p>
          <p class="text-small">
            The future of education is here. Lorem ipsum dolor sit amet,
            consectetur adipisicing elit. Repellat dolores minima nesciunt fugit
            ex magnam nemo totam esse odit blanditiis.
          </p>
          <div class="buttons">
            <button class="btn">Subscribe</button>
            <button class="btn">Watch Video</button>
          </div>
        </div>
        <div class="shalf">
          <img class="image" src="https://source.unsplash.com/1600x900/?collegestudents" alt=" image" />
        </div>
      </div>
    </section>
    <section class="section" id="about">
      <div class="para">
        <p class="section-tag text-big">
          Lorem ipsum dolor sit amet consectetur.
        </p>
        <p class="section-subtag text-small">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corporis
          numquam reprehenderit commodi ipsa, molestiae fugiat adipisci
          distinctio? Veritatis, ex fugiat? Itaque est consectetur eum
          temporibus cupiditate facilis aliquam perspiciatis impedit sapiente
          ullam voluptates repellendus tempora praesentium accusantium id, nihil
          doloremque nemo aut rem sit deserunt! Minima labore quisquam
          doloremque nostrum nobis, maiores error eos laborum magnam nemo sunt
          deleniti aperiam molestias deserunt enim provident doloribus rem quis!
          Molestiae minus neque enim in, quae fuga temporibus molestias ipsa
          veritatis, explicabo expedita repellat suscipit modi consectetur quos
          quibusdam, quaerat porro odit. Voluptas incidunt pariatur quas tempore
          minima. Temporibus itaque sunt aperiam inventore optio rerum, nesciunt
          ratione molestias eum natus id esse dolorum! Nemo a eius sit minima
          iure praesentium enim accusamus minus voluptatum facilis, suscipit cum
          explicabo officiis eaque corrupti sunt error. Reprehenderit ullam
          eveniet placeat libero. Quam asperiores suscipit doloribus.
          Reprehenderit totam magnam, quae ullam eligendi libero aliquid
          voluptas, iste consequuntur, saepe nam animi blanditiis repellat
          voluptates sequi! Tenetur unde neque ab sunt corporis facilis dicta
          quisquam minus saepe consectetur ad quas, eaque mollitia aliquam
          delectus aspernatur aut optio, rem temporibus. Suscipit perferendis
          odio ipsum asperiores. Fugiat, vero illo. Ea voluptatem debitis
          repudiandae, aliquid earum placeat animi ratione quae eum nihil?
        </p>
      </div>
      <div class="thumbnail">
        <img
          src="https://source.unsplash.com/1600x900/?coding,html"
          alt="image"
          class="imgfluid"
        />
      </div>
    </section>
    <section class="section left">
      <div class="para">
        <p class="section-tag text-big">
          Lorem ipsum dolor sit amet consectetur.
        </p>
        <p class="section-subtag text-small">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corporis
          numquam reprehenderit commodi ipsa, molestiae fugiat adipisci
          distinctio? Veritatis, ex fugiat? Itaque est consectetur eum
          temporibus cupiditate facilis aliquam perspiciatis impedit sapiente
          ullam voluptates repellendus tempora praesentium accusantium id, nihil
          doloremque nemo aut rem sit deserunt! Minima labore quisquam
          doloremque nostrum nobis, maiores error eos laborum magnam nemo sunt
          deleniti aperiam molestias deserunt enim provident doloribus rem quis!
          Molestiae minus neque enim in, quae fuga temporibus molestias ipsa
          veritatis, explicabo expedita repellat suscipit modi consectetur quos
          quibusdam, quaerat porro odit. Voluptas incidunt pariatur quas tempore
          minima. Temporibus itaque sunt aperiam inventore optio rerum, nesciunt
          ratione molestias eum natus id esse dolorum! Nemo a eius sit minima
          iure praesentium enim accusamus minus voluptatum facilis, suscipit cum
          explicabo officiis eaque corrupti sunt error. Reprehenderit ullam
          eveniet placeat libero. Quam asperiores suscipit doloribus.
          Reprehenderit totam magnam, quae ullam eligendi libero aliquid
          voluptas, iste consequuntur, saepe nam animi blanditiis repellat
          voluptates sequi! Tenetur unde neque ab sunt corporis facilis dicta
          quisquam minus saepe consectetur ad quas, eaque mollitia aliquam
          delectus aspernatur aut optio, rem temporibus. Suscipit perferendis
          odio ipsum asperiores. Fugiat, vero illo. Ea voluptatem debitis
          repudiandae, aliquid earum placeat animi ratione quae eum nihil?
        </p>
      </div>
      <div class="thumbnail">
        <img
          src="https://source.unsplash.com/1600x900/?school,studing"
          alt="image"
          class="imgfluid"
        />
      </div>
    </section>
    <section class="section" id="services">
      <div class="para">
        <p class="section-tag text-big">
          Lorem ipsum dolor sit amet consectetur.
        </p>
        <p class="section-subtag text-small">
          Lorem ipsum dolor, sit amet consectetur adipisicing elit. Corporis
          numquam reprehenderit commodi ipsa, molestiae fugiat adipisci
          distinctio? Veritatis, ex fugiat? Itaque est consectetur eum
          temporibus cupiditate facilis aliquam perspiciatis impedit sapiente
          ullam voluptates repellendus tempora praesentium accusantium id, nihil
          doloremque nemo aut rem sit deserunt! Minima labore quisquam
          doloremque nostrum nobis, maiores error eos laborum magnam nemo sunt
          deleniti aperiam molestias deserunt enim provident doloribus rem quis!
          Molestiae minus neque enim in, quae fuga temporibus molestias ipsa
          veritatis, explicabo expedita repellat suscipit modi consectetur quos
          quibusdam, quaerat porro odit. Voluptas incidunt pariatur quas tempore
          minima. Temporibus itaque sunt aperiam inventore optio rerum, nesciunt
          ratione molestias eum natus id esse dolorum! Nemo a eius sit minima
          iure praesentium enim accusamus minus voluptatum facilis, suscipit cum
          explicabo officiis eaque corrupti sunt error. Reprehenderit ullam
          eveniet placeat libero. Quam asperiores suscipit doloribus.
          Reprehenderit totam magnam, quae ullam eligendi libero aliquid
          voluptas, iste consequuntur, saepe nam animi blanditiis repellat
          voluptates sequi! Tenetur unde neque ab sunt corporis facilis dicta
          quisquam minus saepe consectetur ad quas, eaque mollitia aliquam
          delectus aspernatur aut optio, rem temporibus. Suscipit perferendis
          odio ipsum asperiores. Fugiat, vero illo. Ea voluptatem debitis
          repudiandae, aliquid earum placeat animi ratione quae eum nihil?
        </p>
      </div>
      <div class="thumbnail">
        <img
          src="https://source.unsplash.com/1600x900/?students,books"
          alt="image"
          class="imgfluid"
        />
      </div>
    </section>
    <section class="contact" id="contact">
      <h2 class="textcentre">CONTACT US</h2>
      <div class="form">
        <input
          class="form-input"
          type="text"
          name="name"
          id="name"
          placeholder="Enter Your Name"
        />
        <input
          class="form-input"
          type="number"
          name="phone number"
          id="phonenumber"
          placeholder="Enter Your phone number"
        />
        <input
          class="form-input"
          type="email"
          name="email"
          id="email"
          placeholder="Enter Your age"
        />
        <input
          class="form-input"
          type="age"
          name="age"
          id="age"
          placeholder="Enter Your age"
        />
        <textarea
          class="form-input"
          name="text"
          id="text"
          cols="30"
          rows="10"
          placeholder="Give Your Feedback"
        ></textarea>
        <button class="btn dark btn-sm">SUBMIT</button>
      </div>
    </section>
    <footer>
      <p class="textfooter background">
        Copyright &copy; 2023 Educa - All rights reserved
      </p>
    </footer>
    <!-- <script src="res.js"></script> -->
    <script>
      burger = document.querySelector('.burger')
navbar = document.querySelector('.navbar')
navlist = document.querySelector('.nav-list')
rightnav = document.querySelector('.rightnav')

burger.addEventListener('click',()=>{
    rightnav.classList.toggle('v-class-resp')
    navlist.classList.toggle('v-class-resp')
    navbar.classList.toggle('h-nav-resp')
})
    </script>
  </body>
</html>
