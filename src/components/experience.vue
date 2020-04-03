<template>
	<div class="main">
		<div class="body">
			<div class="list">
	<ul  v-for="(icon,i) in icons" v-bind:key="i" >
  <li><a :class='icon.icon' href="#home"> </a></li>
 <h2> <li><a >  {{icon.title}}</a></li></h2>
  <li><a >  {{icon.text}}</a></li>
  
</ul>
</div>
	  </div>
	</div>
</template>
<script>
export default {
   data(){
	   return{
		     icons:[
			  
				{icon:"fab fa-twitter fa-2x",title:'Vanilla JavaScript',text:'List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.aremu'},  
				{icon:"fab fa-twitter fa-2x ",title:'Angular, React & Vue',text:'List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.'},
				{icon:"fab fa-twitter fa-2x",title:'Node.js',text:'List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.'},
				{icon:"fab fa-twitter fa-2x",title:'Python & Django',text:'List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.'},
				{icon:"fab fa-twitter fa-2x",title:'PHP', text:'List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.'},
				{icon:"fab fa-twitter fa-2x",title:'npm, Gulp & Grunt', text:'List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.'},
				{icon:"fab fa-twitter fa-2x",title:'HTML & CSS', text:'List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.'},
				{icon:"fab fa-twitter fa-2x",title:'Sass & LESS', text:'List skills/technologies here. You can change the icon above to any of the 1500+ FontAwesome 5 free icons available. Aenean commodo ligula eget dolor.'}
			  
		  ]

	   }
   }
}
</script>
<style scoped>
.main{
	
	width: 81.5%;
	max-width: 82.5%;
	float:right;
	
		
		margin-top: 10em;

}
ul{
	list-style-type:none;
	margin-top:1px;
}
li a {
 
  color: black;
  padding: 4px 8px;
  margin-top:1px;
   font-size: 1.2em;
 
  text-decoration: none;
  
}
.list{

		display: grid;
  grid-column-gap: 50px;
  grid-template-columns: auto auto auto auto;
		 
}
.body{
	margin-left:3rem;
}
</style>