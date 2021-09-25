pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				tag "1.*"
			}
		
            steps {                
                echo 'Hello World building tag'
            }
        }
    }
}
