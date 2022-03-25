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
						<a href="#" class="nav-link">ABOUT</a>
						<span class="nav-item-tooltip">ABOUT</span>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">SKILLS</a>
						<span class="nav-item-tooltip">SKILLS</span>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">LEARNING</a>
						<span class="nav-item-tooltip">LEARNING</span>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">CONTACT</a>
						<span class="nav-item-tooltip">CONTACT</span>
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


.navbar-nav .nav-item{
	position: relative;
	/* overflow: hidden; */
}
.nav-item:hover .nav-item-tooltip {
	top: -50%;
	transform: translate(0%, 50%);
  padding: 0.5rem;
  text-decoration: none;
	transition: ease-in 0.2s;
}
.nav-item-tooltip {
	background-color: #ddd;
	color: black;
	position: absolute;
  padding: 0.5rem;
	top: -200%;
	transform: translate(0%, 50%);
}

</style>