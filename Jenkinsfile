pipeline {
	agent {
		label{
			label "slave-linux"
		
		}
	}

             stages{
			 stage('git_checkout'){
			 steps{
			 git "https://github.com/sunildevops77/maven.git"
			 }
			 }
			 stage('build'){
			 steps{
			 sh "mvn package"
			 }
			 }
			 }
}
