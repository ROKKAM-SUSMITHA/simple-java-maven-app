pipeline {
    agent any
     tools {
        maven 'Maven4'
        // jdk 'openjdk-11'  
    }
    stages {
        stage('Build') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
