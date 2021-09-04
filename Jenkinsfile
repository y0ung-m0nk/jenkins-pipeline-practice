pipeline {
    agent any
    
    stages {
        stage("ENV") {
            steps {
                sh "printenv | sort"
            }
        }
   
    
        stage("ENV Details") {
            steps {
                echo " BUILD NUMBER IS : ${BUILD_NUMBER}"
            }
        }
        
    }    
}