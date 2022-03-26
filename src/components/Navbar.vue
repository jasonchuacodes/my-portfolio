<template>
	<div class="navbar navbar-expand-lg navbar-light bg-light">
		<div class="container-fluid">
			<a href="#" class="navbar-brand">CHUA
				<span class="brand-tooltip">CHUA</span>
			</a>
			<button class="navbar-toggler" 
				data-bs-toggle="collapse" 
				data-bs-target="#navCollapsableItems"
			>
				<i class="fa-solid fa-bars"></i>
			</button>		
			<div class="navbar-container collapse navbar-collapse" id="navCollapsableItems">
				<ul class="navbar-nav">
					<li class="nav-item">
						<a href="#" class="nav-link">ABOUT
						<span class="nav-item-tooltip">ABOUT</span>
						</a>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">LEARNING
						<span class="nav-item-tooltip">LEARNING</span>
						</a>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">LEARNING
						<span class="nav-item-tooltip">LEARNING</span>
						</a>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">CONTACT
						<span class="nav-item-tooltip">CONTACT</span>
						</a>
					</li>
				</ul>
			</div>
		</div>
		
	</div>

	
</template>
<style scoped>
.navbar-brand{
	position: relative;
	padding: 0.5rem;
	/* overflow: hidden; */
	border-radius: 0.3rem;
}
.brand-tooltip{
	position: absolute;
	top: -120%;
	left: 0%;
	background-color: grey;
	padding: 0.5rem;
	transition: ease-in 0.15s;
}
.navbar-brand:hover .brand-tooltip {
	top: 0%;
	left: 0%;
	color: white;
}
.navbar-container {
	justify-content: end;	
}
.nav-item a{ 
	position: relative;
	/* overflow: hidden; */
	border-radius: 0.3rem;
}
.nav-item-tooltip {
	position: absolute; 
	background-color: grey;
	top: -150%;
	left: 0%;
	padding: 0.5rem;
	transition: ease-in 0.15s;
}
.nav-item a:hover .nav-item-tooltip {
	top: 0%;
	left: 0%;
	color: white;
} 
</style>