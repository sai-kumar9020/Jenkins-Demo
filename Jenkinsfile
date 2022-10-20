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
			def exists=fileExists 'index.html'
                if (exists ('C:/Users/sai kumar/Jenkins-Demo/index.html'))
				{
                 echo "File C:/Users/sai kumar/Jenkins-Demo/index.html found!"
                }
            }
		}	
    }
}