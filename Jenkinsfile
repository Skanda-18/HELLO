pipeline {
    agent any
    stages {
        stage('One') {
                steps {
                        echo 'Hi, this is Skanda and this is our demo Pipeline project'
			
                }
        }
	    stage('Two'){
		    
		steps {
			input('Do you want to proceed?')
        }
	    }
        stage('Three') {
                when {
                        not {
                                branch "master"
                        }
                }
                steps {
			echo "Hello"
                        }
        }
 
    }
}
