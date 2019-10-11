
pipeline{
	agent any 
		stages{ 
			stage('Test Stage 1'){
				steps{
					echo 'Executing Test stage 1'
				}
			}
			stage('Test Stage 2'){
				steps{
					echo 'Executing Test stage 2'
				}
			}
			stage('Test Stage 3'){
				steps{
					echo 'Executing Test stage 3'
				}
			}
			stage('Test Stage 4'){
				when{
					branch "master"
				}
				steps{
					echo 'Executing Test stage 4'
				}
			}				
		}
}