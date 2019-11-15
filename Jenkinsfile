pipeline {
     agent any
	  
	 stages {
	     stage ('compile stage'){
		 
		    steps {
			    with maven : 'maven_3_5_4') {
			      sh 'mvn clean compile '
				
				}
						
			}
			
		 
		 }
	 
	 }

      stage ('Testing  stage'){
		 
		    steps {
			    with maven : 'maven_3_5_4') {
			      sh 'mvn test '
				
				}
						
			}
			
		 
		 }
	 
	 }
