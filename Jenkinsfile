pipeline{
    agent{
        label "any"
    }
    stages{
        stage("Git Checkout"){
            steps{
                
                git branch: 'main', url: 'https://github.com/spring-projects/spring-petclinic.git'
            }
        }
    }
}