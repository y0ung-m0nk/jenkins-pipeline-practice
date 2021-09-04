pipeline {
    agent any
    environment {
        user_name = "Himasnhu"
        user_id = 33
    }
    stages {
        stage("ENV") {
            steps {
                sh "printenv | sort"
            }
        }
   
    
        stage("ENV Details") {
            steps {
                echo " BUILD NUMBER IS : ${BUILD_NUMBER}"
                echo "User name is ${env.user_name}"
                echo "User id is ${env.user_id} (type: ${env.user_id.class}"
            }
        }
        
    }    
}