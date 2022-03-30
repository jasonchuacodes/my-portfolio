<template>
  <div class="navbar navbar-expand-md navbar-light bg-light">
    <div class="brand">
      <a href="#">CHUWIE</a>
    </div>
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
		
</template>
<style scoped>
/* Navbar brand */
.brand {
  display: flex;
  justify-content: center;
  margin: 0 1rem;
  padding: 0 0.8rem;
  font-size: 1.25rem;
  text-decoration: none;
  white-space: nowrap;
  position: relative;
}
.brand::before {
  color: #6c757d;
  position: absolute;
  top: 100%;
  left: 0;
  height: 2px;
  width: 100%;
  content: '';
  background-color: #6c757d;
  transform: scale(0.5);
  transition: ease 0.4s;
}
.brand::after {
  color: #6c757d;
  position: absolute;
  top: 100%;
  left: 0;
  height: 2px;
  width: 100%;
  content: '';
  background-color: #6c757d;
  transform: scale(0.8);
  transition: ease 0.4s;
}
.brand:hover::before{
  transform: scale(1);
  top: 0;
  color: #212325;
}
.brand:hover::after{
  transform: scale(1);
  color: #212325;
}
.brand a{
  text-decoration: none;
  color: #6c757d;
}
.brand a:hover {
  color: #212325;
}
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