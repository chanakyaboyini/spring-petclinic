pipeline{
    agent any
    stages{
        stage("Git checkout"){
            steps{
                git branch: 'main', url: 'https://github.com/spring-projects/spring-petclinic.git'
            }
            
        }
    }
}