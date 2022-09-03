pipeline {
    agent any
    stages {
         stage ('Build') {
            steps {
                echo "Building"
            }
        }

         stage ('Test') {
            steps {
                echo "Testing"
            }
        }
        
        stage ('Deploy') {
            steps {
                cp sample.war /usr/local/tomcat9/webapps
            }
        }
    }
}
     

        
        

    
