node {
   stage("Checkout") { 
      // Get some code from a GitHub repository
      git ' https://github.com/deepasreetk/Nginx_Docker_deploy.git'
      // Get the docker build
      
      
   }
   
    stage("build image") {
    
        app = docker.build("deepasreetk/nginx")
    
        
       }
     }
