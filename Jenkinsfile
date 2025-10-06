pipeline{
	agent any
	stages{
		stage("cloning"){
			steps{
				echo "Cloning repo is completed"
			}
		}
		stage("Program Execution"){
                        steps{
                                bat 'java Sample.java'
                        }
                }
	}
}
