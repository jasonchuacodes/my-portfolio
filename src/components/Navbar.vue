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
						<a href="#" class="nav-link" data-bs-toggle="tooltip">ABOUT
						</a>
						<span class="tooltip">ABOUT</span>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">SKILLS</a>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">LEARNING</a>
					</li>
					<li class="nav-item">
						<a href="#" class="nav-link">CONTACT</a>
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
.nav-item {
}
.nav-item:hover {
	background-color: red;
	transition: ease-in 0.2s;
}
</style>