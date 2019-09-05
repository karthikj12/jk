pipeline {
	agent any
		stages {
		stage('one') {
			steps {
				echo ' hi karthik'
			}
		}
		stage('Two') {
			steps {
				input('proceed')
			}
		}
		stage('Three')	{
			when {
				not {
					branch "master"
				}
			}
			steps {
				echo "hello"
			}
		}
}
}

