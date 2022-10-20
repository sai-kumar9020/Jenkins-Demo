pipeline {
    agent any
    options{
        timestamps()
    }
    stages{
        stage("Stage 1"){
            steps{
                echo "Start timestamps"
            }
        }
        stage("Stage 2"){
            steps{
                echo "end TimeStamps"
            }
        }
		stage("stage 3"){
            steps{
                if (fileExists('C:/Users/sai kumar/Jenkins-Demo/index.html'){
                 echo "File C:/Users/sai kumar/Jenkins-Demo/index.html found!"
                )
            }
		}	
    }
}