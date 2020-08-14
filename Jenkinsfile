
node {

   stage('SCM') {
         // git clone
	 	  git 'https://github.com/rbclokesh/game-of-life.git'
		     }
		        
			   stage ('build the packages') {
			         // mvn package
				 	  sh 'mvn package'
					     }
					     stage('arch'){
						//artifactory
						archive 'gameoflife-web/target/*.war'
					     }
					         
						 }
