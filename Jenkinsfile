pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac Hello.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java Hello"""
				}
			}
	 }
			
	}
