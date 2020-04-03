<template>
<div class="main">
	
	<div class="bio">
		
			<h1>Sehun  dev</h1>
		
		
			<h3>
				Senior Software Engineer
			</h3>
	
			<p> im a  software engineer specialised in frontend and backend development for 
				complex scalable web apps. I write about software development on <span style="color:#54B689;">my blog</span>. Want 
				to know how I may help your project? Check out my project <span style="color:#54B689;">portfolio</span> and <span style="color:#54B689;">online resume.</span>
 
</p>
<button class="btn1"><i class="fa fa-home"></i> view portfolio</button> 
<button class="btn"><i class="fa fa-bars"></i> view resume</button>
		
	</div>
	<div class="image">
		 <div class="image">
		  <img src="@/assets/ne.jpg">
	  </div>
	</div>
  

</div>
</template>
<style scoped>
h3{
	font-size: 1.5rem;
}
.main{
	background-color:#fafafa !important; 
	width: 81.5%;
	max-width: 82.5%;
	height: 29em;
	float:right;
		display: flex;
		
		align-items: stretch;
 

}
div.bio{

  margin-left: 3rem;
  width: 50em;
  margin-top: 3em;
}
image{
	width: 30em;
	
	
}
img{
	width: 30em;
	height: 22em;
	margin: 3em;
}
.btn1 {
  background-color: #54B689; /* Blue background */
  border: none; /* Remove borders */
  color: white; /* White text */
  padding: 12px 16px; /* Some padding */
  font-size: 16px; /* Set a font size */
  cursor: pointer; /* Mouse pointer on hover */
  margin: 1em;
  border-radius: 0.5em;
  
}
.btn {
  background-color: black; /* Blue background */
  border: none; /* Remove borders */
  color: white; /* White text */
  padding: 12px 16px; /* Some padding */
  font-size: 16px; /* Set a font size */
  cursor: pointer; /* Mouse pointer on hover */
  margin: 1em;
  border-radius: 0.5em;
  
}
p{
	font-size: 1.5em;
}

</style>