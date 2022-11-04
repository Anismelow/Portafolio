# Portafolio
 mi primer portafolio solo con html y css
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  color: aliceblue;
}
body {
  background: #c31432; /* fallback for old browsers */
  background: -webkit-linear-gradient(
    to right,
    #240b36,
    #c31432
  ); /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(
    to right,
    #240b36,
    #c31432
  ); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */

  font-family: "Oswald", sans-serif;
  font-size: 16px;
}

.container{
  opacity: 0.8;
  background: #232526;  /* fallback for old browsers */
  background: -webkit-linear-gradient(to bottom, #414345, #232526);  /* Chrome 10-25, Safari 5.1-6 */
  background: linear-gradient(to bottom, #414345, #232526); /* W3C, IE 10+/ Edge, Firefox 16+, Chrome 26+, Opera 12+, Safari 7+ */
  
border-radius: 4%;  
}

a {
  font-size: 30px;
  text-decoration: none;
}
ul {
  list-style: none;
}

.container {
  justify-content: center;
  align-items: center;
  width: 70%;
  margin: auto;
}
/*navegacion*/

.nav-main {
  border-radius: 10%;
  width: 100%;
  margin: 70px 0px 40px 0px ;
  padding: 60px 0px 90px 0px;
}

.logo {
  width: 60px;
  padding-top: 0px;
}

.nav-menu {
  font-size: 17px;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 0px;
  padding: 0px 0px;
}

.nav-main ul {
  display: flex;
}
.nav-main ul li {
  padding: 60px;
}
nav-main ul li a {
  padding: 10px;
}

a {
  color: aliceblue;
}

.nav-main ul li a:hover {
  border-bottom: 2px solid wheat;
}

hr {
  margin-top: 0px;
  margin-bottom: 0px;
}
.sobre-mi {
  width: 100%;
  margin-top: 10px;
  padding: 90px 0px 90px 0px;
}

.sobre-mi h2 {
  font-size: 60px;
  display: flex;
  justify-content: center;
  margin-bottom: 20px;
}

.sobre-mi p {

  font-size: 30px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 50px 180px 50px 180px;
}

/*new card */


.new-card{
 
  display: grid;
grid-template-columns: repeat(4, 1fr);
margin: 10px 0px;
}
h2{
  display: flex;
  justify-content: center;
}

.new-card{
  margin: 90px 0px 50px 0px;
padding: 50px 40px 50px 40px;
}

h2{
  padding: 50px 0px 50px 0px;
  font-size: 60px;
}
.new-card img{
  width: 70%;
}

.new-card h3{
  font-size: 20px;
  margin: 10px 0px 0px 20px ;
}

.logo1 h3{
  padding:  0px 0px 0px 30px ;
}

.logo2 h3{
padding: 0px 0px 0px 30px;
}

.logo4 h3{
  padding: 0px 0px 0px 30px;
}
.logo5 h3{
  padding: 0px 0px 0px 19px;
}

.contacto h2{
  margin: 0px 0px 60px 0px;
}
.contacto{

padding: 50px;
}

.contacto ul li img{
  
  width: 50px;
  display: flex;
}

.contacto ul li{
 
  display: inline-flex;
  align-items: center;
  padding: 0px 50px ;
 
}

.contacto ul{
  margin: 0px 0px 0px 400px;
  padding: 0px 0px ;
}
