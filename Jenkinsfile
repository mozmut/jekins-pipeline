@Library("tools") _
pipeline{
    agent{ label "linux"}
    stages{
        stage('Example'){
            steps{
            helloWorld(name:"mozmut", dayOfWeek:"Tuesday")
            }
        }
    }
}