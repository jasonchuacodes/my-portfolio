<template>
  <div class="navbar navbar-expand-md navbar-light bg-light">
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
          <!-- nav-item -->
            <li class="nav-item"> 
              <a href="#" class="nav-link">ABOUT
                <span class="nav-link-tooltip">ABOUT</span>
              </a>
            </li>
            <li class="nav-item"> 
              <a href="#" class="nav-link">SKILLS
                <span class="nav-link-tooltip">SKILLS</span>
              </a>
            </li>
            <li class="nav-item"> 
              <a href="#" class="nav-link">LEARNING
                <span class="nav-link-tooltip">LEARNING</span>
              </a>
            </li>
            <li class="nav-item"> 
              <a href="#" class="nav-link">CONTACT
                <span class="nav-link-tooltip">CONTACT</span>
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

/* Nav-item */
.nav-item {
  overflow: hidden;
  margin: 0 0.5rem;
}
.nav-link {
  position: relative;
  transition: ease-in 0.2s;
  top: 0%;
}
.nav-link-tooltip {
  position: absolute;
  top: 120%;
  left: 0%;
  padding: 0.5rem; 
  transition: ease-in 0.2s;
  font-weight: bold;
}

.nav-item:hover .nav-link {
  top: -120%;
}
</style>