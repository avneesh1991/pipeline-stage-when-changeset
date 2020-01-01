pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset glob: "*helloworld.js", caseSensitive: true
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
