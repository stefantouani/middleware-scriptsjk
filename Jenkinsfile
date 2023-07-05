pipeline {
    agent any
    stages{
        stage("create zip file"){
            steps {
                dcrip{ 
             zip middlewasreScript-${BUILD_NUMBER}.zip *  --exclude Jenkinsfile README.md
                }

                echo "build"
            }
        
    }

}