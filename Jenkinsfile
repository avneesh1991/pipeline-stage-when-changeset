pipeline {

    agent any

	

    stages {

        stage('Build') {

		

			when{

				changeset glob: "*.js", caseSensitive: true

			}

		

            steps {                

                echo 'Hello World changeset JS'

            }

        }

    }

}
	
