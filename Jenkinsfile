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
		stage("checking a file"){
            steps{
                Boolean bool = fileExists 'index.html'

                  if (bool) {
                        println "File exist"
                   } else {
                       println "File doesn't exist"
                    }
            }
		}	
    }
}