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
                                sh 'java Sample.java'
                        }
                }
	}
}
