</* Imported some fonts*/
@import url('https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap');
@import url("https://fonts.googleapis.com/css?family=Secular+One#standard-styles");
@import url("https://fonts.googleapis.com/css?family=Open+Sans&display=swap");
@import url("https://fonts.googleapis.com/css?family=Licorice");
@import url("https://fonts.googleapis.com/css?family=Kalam");
@import url("https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap");

/* General Property to be applied to every page*/
*{
    padding: 0;
    margin: 0;
    font-family:sans-serif;
    box-sizing: border-box;
    overflow:auto;
}

/* HOMEPAGE STARTS HERE */
.hero{
    height: 100vh;
    width: 100%;
    background-image: url(../img/black-white-background.jpg);
    background-size: cover;
    background-position: center;
}

/* Navigation bar */
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding-top: 20px;
    padding-left: 3%;
    padding-right: 3%;
    position: fixed;
    z-index: 9999;
    background-color: whitesmoke;
    width: 100%;
}

/* Customized fonts for word "Portfolio" */
.logo{
    color: black;
    font-size: 40px;
    letter-spacing: 1.5px;
    cursor: pointer;
}
span{
    color:rgb(255, 81, 0)
}

/* Navigation Style */
nav ul li{
    list-style-type: none;
    display: inline-block;
    padding: 10px 20px;
}

/* Linked Pages */
nav ul li a{
    color: rgb(0, 0, 0);
    text-decoration: none;
    font-family:Arial, Helvetica, sans-serif;
    font-weight: bold;
    font-size: large;
    text-transform: capitalize;
}
.qwe{
  color: white;
}
/* On Hover Effect*/
nav ul li a:hover{
    color: rgb(255, 81, 0);
    transition: .4s;
}

/* Content for Homepage */
.content{
    position: absolute;
    top: 50%;
    left: 3%;
    transform: translateY(-50%);
}
h1{
    color: rgb(0, 0, 0);
    margin: 20px 0px 20px;
    font-size: 75px;
}
h3{
    font-family:sans-serif;
    color:black;
    font-size: 25px;
    margin-bottom: 50px;
}
h4{
    font-family:sans-serif;
    color:black;
    letter-spacing: 2px;
    font-size: 20px;
}

.newsletter form{
    width: 380px;
    max-width: 100%;
    position: relative;
}
.newsletter form input:first-child{
    display: inline-block;
    width: 100%;
    padding: 14px 130px 14px 15px;
    border: 2px solid rgb(255, 81, 0);
    outline: none;
    border-radius: 30px;
}
.newsletter form input:last-child{
    position: absolute;
    display: inline-block;
    outline: none;
    border: none;
    padding: 10px 30px;
    border-radius: 30px;
    background-color: rgb(255, 81, 0);
    color: white;
    box-shadow: 0px 0px 5px rgb(199, 0, 0), 0px 0px 15px #03ff74;
    top: 6.24px;
    right: 6px;
}

/* ABOUT PAGE STARTS HERE */
.about{
    width: 100%;
    padding: 100px 0px;
    background-color: #299bf8;
}
.about img{
    height: auto;
    width: 500px;
}
.about-text{
    color: rgb(0, 0, 0);
    width: 430px;
}
.about-text h2{
    font-family:sans-serif;
    color: rgb(0, 0, 0);
    font-size: 75px;
    text-transform: capitalize;
    margin-bottom: 20px;
}
.about-text h5{
    color: rgb(0, 0, 0);
    letter-spacing: 2px;
    font-size: 22px;
    margin-bottom: 25px;
    text-transform: capitalize;
}
.about-text p{
    font-family:sans-serif;
    color: rgb(0, 0, 0);
    letter-spacing: 1px;
    line-height: 28px;
    font-size: 18px;
    margin-bottom: 45px;
}
.main{
    width: 1130px;
    max-width: 95%;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-around;
}

button{
    background-color: rgb(255, 81, 0);
    color: white;
    text-decoration: none;
    border: 2px solid transparent;
    font-weight: bold;
    padding: 13px 30px;
    border-radius: 30px;
    transition: 0.4s;
}
button:hover{
    background-color: transparent;
    border: 2px solid rgb(255, 81, 0);
    cursor: pointer;
    color: rgb(0, 0, 0);
}
.content{
  position: absolute;
  top: 50%;
  left: 3%;
  transform: translateY(-50%);
}
  
.about{
    width: 100%;
    padding: 100px 0px;
    background-color: grey;
}
.about img{
    height: auto;
    width: 500px;
}
.about-text{
    color: rgb(0, 0, 0);
    width: 430px;
}
.about-text h2{
    font-family:sans-serif;
    color: rgb(0, 0, 0);
    font-size: 75px;
    text-transform: capitalize;
    margin-bottom: 20px;
}
.about-text h5{
    color: rgb(0, 0, 0);
    letter-spacing: 2px;
    font-size: 22px;
    margin-bottom: 25px;
    text-transform: capitalize;
}
.about-text p{
    font-family:sans-serif;
    color: rgb(0, 0, 0);
    letter-spacing: 1px;
    line-height: 28px;
    font-size: 18px;
    margin-bottom: 45px;} 
    

    /* skills STARTS HERE*/
.skills{
  width: 100%;
  padding: 30px 0px;
  padding-top: 100px;
  background-color: #73bfdd;
}
.title h1{
  color: rgb(0, 0, 0);
  font-family: sans-serif;
  font-size: 75px;
  width: 1130px;
  margin: 30px auto;
  text-align: center;
}
.box1{
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 250px;
}
.card1{
  height: 200px;
  width: 335px;
  padding: 20px 35px;
  background: #191919;
  border-radius: 20px;
  margin: 15px;
  position: relative;
  overflow: hidden;
  text-align: center;
}
.card1 h5{
  color: white;
  font-family: sans-serif;
  font-weight: bold;
  font-size: 15px;
  margin-bottom: 15px;
}
.desc h4{
  color: rgb(179, 115, 118);
  font-family: sans-serif;
  font-size: 10px;
  line-height: 17px;
  margin-bottom: 10px;

}
.desc h3{
  color: rgb(255, 255, 255);
  font-size: 15px;
  line-height: 17px;
  margin-bottom: 15px;
}
.desc .button{
  background-color: rgb(255, 81, 0);
  color: white;
  text-decoration: none;
  border: 2px solid transparent;
  font-weight: bold;
  padding: 5px 22px;
  border-radius: 30px;
  transition: 0.4s;
}
.desc .button:hover{
  background-color: transparent;
  border: 2px solid rgb(255, 81, 0);
  cursor: pointer;
  color: rgb(255, 255, 255);
}
.box2{
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 400px;
}
 .card2{
  height: 200px;
  width: 650px !important;
  padding: 20px 35px;
  background: none;
 
  margin: 15px;
  position:absolute;
  overflow: hidden;
  text-align: center;
}
