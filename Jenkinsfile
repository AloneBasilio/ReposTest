pipeline {
	agent any

	stages {
		stage ('Inicial') {
			steps {
				echo 'Iniciando a pipeline'
			}
		}
		
		stage ('execute python file') {
			steps {
				sh 'python file.py'
			}
		}
	}

}
