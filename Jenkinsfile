pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            echo "$GIT_BRANCH"
        }
	}

		stage('Docker build')
		{
         steps{
			   //powershell(script: 'docker images -a')
            powershell(script:"ol")
            echo "$GIT_BRANCH"
         }
		}
	}  
	
}

