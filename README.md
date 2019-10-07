# Portfolio
A portfolio showcasing some of my projects that I completed.


The CSS code is below:



{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font: 15px/1.5em Courier, Helvetcia, sans-serif;
  background-color: white;
  color: #7d97ad;
}

/*Global*/

.logo{
  color: black;
}

.container {
  justify-content: space-between;
  display: flex;
  flex-wrap: wrap;
  width: 70%;
  margin: auto;
  overflow: hidden;
  }


/*Header*/

.header {
  display: flex;
  justify-content: space-between;
  border-bottom: #7d97ad 5px solid;
  margin: 2em;
  width: 70%;
  margin-left: 15%;
  align-items: center;
}

.logo {
  font-size: 9em;
  
}

#name {
  font: bold 5em Courier, Helvetcia, sans-serif;
  margin-bottom: 5px;
}

#descriptor {
  font: bold 1.5em Courier, Helvetcia, sans-serif;
  text-align: right;

}

/* Showcase */
.main-image {
  width: 100%;
  height: auto;
  margin-bottom: 3em;  
}

/* Featured Projects  */

  .featured-image {
  width: 100%;
  height: auto;
}

.work-header {
    width: 100%;
    height: 50px;
    align-items: center;
    font-size: 2.8em;
    margin-bottom: 1em;
    display:flex;
}

.featured-title {
  text-align: center;
  margin-bottom: 3em;
}

.featured-title {
  font-size: 1.5em;
}

/* Footer */
footer {
  text-align: center;
  border-top: 2px solid;
  min-height:50px;
}


.credit-quote {
  padding-top: 1em;
  align-content: center; 
}

#footer-name {
  font-weight: bold;
}

footer blockquote {
  font-size: 0.7em;
}

/* Responsive */

@media screen and (max-width: 550px){
  .header{
    width: 90%;
    margin: 10px auto;
  }
  .logo {
    font-size: 4em;
  }

  .header-title {
    text-align: right;
    font-size: 8px;

    
  } 
   #featured {
    font-size: .7em;
    text-align: center;
    margin: auto;
  }
   
  .container{
    flex-direction: column;
    width: 100%;
     
  }
  
  .featured-image{
    height: 300px;
    margin-bottom: 1em;
  }
  .featured-title{
    margin-bottom: 1em;
  }
}

@media screen and (min-width: 551px) and (max-width: 999px) {
  
  #featured {
    font-size: 1em; 
    text-align: center;
    margin: auto;
    
  }

  
  .logo {
    font-size: 7em; 
  }

  .header-title {
    text-align: right;
    font-size: 10px;
  }
  
   .featured-image {
  border:solid;
}
  .featured-project1 {
    width: 30%
  }
  .featured-project2 {
    width: 30%
  }
  .featured-project3 {
    width: 30%
  }
   .footer{
    flex-direction: column;
    align-content: center;
  }
 
}

@media screen and (min-width: 1000px) {
  
  .project-content {
    display: flex;
    
  }
  .featured-project1 {
    width: 30%;
    order: 1;
  }
  .featured-project2 {
    width: 30%;
    order: 2;
  }
  .featured-project3 {
    width: 30%;
    order: 3;
  }
}
