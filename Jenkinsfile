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
			   sh '''docker images -a '''
            //powershell(echo:"ol")
            echo "$GIT_BRANCH"
         }
		}
	}  
	
}

