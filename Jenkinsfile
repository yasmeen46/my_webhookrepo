pipeline {
    agent any 
    stages {
        stage('build') {
            steps {
               echo "build started"
    	       git 'https://github.com/yasmeen46/my_webhookrepo.git'
            }
        }


	stage('deploy') {
            steps {
                echo 'Hello world!'
            }
	}

	stage('test') {
            steps {
                echo 'test files'
            }
        }
    }
}
