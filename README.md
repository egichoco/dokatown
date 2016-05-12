# dokatown
<html>
<head>
<title>Doka Town</title>
<!--<link rel="stylesheet" type="text/css" href="Doka.css">-->
<style>
* {
  margin:0px;
  padding:0px;
}
#header{
  background-color: black;
  height: 50px;
  min-width: 100%;
}
body{
  font-family:  calibri;
}
img{
  width: 50px;
  margin: 4.8px;
  margin-left:41pt;
  float: left;
  height: 41px;
}
#header ul,#header a{
  font-size: 16pt;
  text-decoration: none;
  color: white;
  list-style-type: none;
  font-family: "Berlin Sans FB Demi";
}

ul.menu{
  height: 30px;
  width: 80%;
  float: left;
}
ul.menu li{
  margin-top: 11px;
  margin-left: 123px; 
  float: left;
  position: relative;
}
ul.submenu {
  margin-left: -45px;
  margin-top: 13px;
  z-index: 999;
  position: absolute;
  display: none;
}
ul.submenu li{
  background-color: black;
  margin-left: 0px;
  width:123px;
  margin-top: 4px;
  text-align: center;
  border-radius: 5px;
  
  
}
#search {
  position: fixed;
  margin: 4px;

}
input{
  display: none;
  margin-left: 5pt;
  padding: 2px;
  height:30pt;
  width: 1299px;
  font-size: 18pt;
}
ul.submenu:hover + .submenu li{
  display:block;
}

</style></head>
<body>
<div id="header">
	<a href="http://www.dokatown.com"><img src="doka.png" alt="logo"/></a>
		
		<ul class="menu">
		<li><a href="">Handphone</a></li>
		<li><span><a href="">PC</a></span>
		<ul class="submenu">
			<li><a href="">Laptop</a></li>
			<li><a href="">Netbook</a></li>
			<li><a href="">Desktop</a></li>
			</ul>
		</li>
		<li><a href="">TV</a></li>
		<li><a href="">Jam</a></li>
		<li><a href="">Tentang kami</a></li>
		</ul>
		<form id="search">
			<input type="text" name="Pencarian" value="search"/>
		</form>
		<a href=""><img src="search.png"></a>
</div>
<div id="conten">
	
</div>
<div id="footpage">
	<ul class="navbottom">
		<li><h3>Category</h3>
			<ul class="category">
				<li><a href="">Handphone</a></li>
				<li><a href="">PC</a></li>
				<li><a href="">TV</a></li>
				<li><a href="">Jam</a></li>
			</ul>
		</li>
		<li><h3>Bantuan</h3>
			<ul class="bantuan">
				<li><a href="">Syarat & ketentuan</a></li>
				<li><a href="">Kebijakan privasi</a></li>
				<li><a href="">Hubungi Kami</a></li>
			</ul></li>
	</ul>
</div>
</body>
