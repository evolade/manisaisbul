<header>
	<div class="row">
		<div class="column">
			<a href="/">
				<img src="/logo.jpeg" alt="" class="logo">
			
			</a>

		</div>
		
	</div>
	<div class="center">
		

		<a href="/"><button class="hbutton">Ana sayfa</button></a>
		<a href="/hakkimizda" class="dropdown">
			<button class="hbutton">Hakkımızda</button>
			<div class="dropdown-content">
				<a href="/hakkimizda"><p>Hakkımızda</p></a>
				<a href="/referanslarimiz"><p>Neden biz?</p></a>
				<a href="/referanslarimiz"><p>Vizyonumuz</p></a>
				<a href="/referanslarimiz"><p>Değerlerimiz</p></a>
				<a href="/referanslarimiz"><p>Uzmanlık alanlarımız</p></a>
			
			</div>
		</a>
		<a href="/referanslarimiz"><button class="hbutton">Referanslarımız</button></a>
		
		<a href="/cvdoldur"><button class="hbutton">Başvuru yap</button></a>
		<a href="/iletisim"><button class="hbutton">İletişim</button></a>

	</div>

		

</header>


<style>
	.center {
		text-align: center;
		
		background-color: rgb(220, 220, 220)
	}
	.hbutton {
		border-radius: 1px;
		border-width: 0px;
		
		
		
		
		background-color: rgb(220, 220, 220);
		padding: 5px;
		margin: 5px;
		margin-left: 20px;
		margin-right: 20px;
	}
	
	.logo {
		height: 130px;
		margin: 30px;
	}
	.column {
  float: left;
  
  padding: 5px;
}
	.columnu {
  float: left;
  
  padding: 5px;
  text-align: center;
  
  margin-top: 50px;
  margin-left: 20px;
}

/* Clear floats after image containers */
.row::after {
  content: "";
  clear: both;
  display: table;
}
	h1 {
		text-align: center;
	}

	.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  padding: 12px 16px;
  z-index: 1;
}

.dropdown:hover .dropdown-content {
  display: block;
}
</style>