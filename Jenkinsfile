pipeline {
     agent any
	  
	 stages {
	     stage ('compile stage'){
		 
		    steps {
			    with maven : 'maven 3.5.4') {
			      sh 'mvn clean compile '
				
				}
						
			}
			
		 
		 }
	 
	 }

      stage ('Testing  stage'){
		 
		    steps {
			    with maven : 'maven 3.5.4') {
			      sh 'mvn test '
				
				}
						
			}
			
		 
		 }
	 
	 }
