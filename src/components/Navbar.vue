<template>
	<div class="navbar navbar-expand-lg navbar-light bg-light">
		<div class="container-fluid">
			<a href="#" class="navbar-brand">CHUA</a>
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
				</ul>
			</div>
		</div>
		
	</div>

	
</template>
<style scoped>
.navbar-container {
	justify-content: end;	
}
.nav-item a{ 
	position: relative;
	overflow: hidden;
}
.nav-item-tooltip {
	position: absolute; 
	background-color: grey;
	top: -150%;
	left: -20%;
	padding: 0.5rem;
	transition: ease-in 0.2s;
}
.nav-item a:hover .nav-item-tooltip {
	top: 0%;
	left: 0%;
	color: white;
} 
</style>