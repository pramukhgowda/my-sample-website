pipeline{
    agent{label "web3cpull"}
    stages{
        stage('clone/pull'){
            steps{
                sh "pwd"
                sh "cd my-sample-website ; git pull https://github.com/pramukhgowda/my-sample-website.git"
            }
        }
        stage("maven"){
            steps{
                sh "pwd"
            }
        }
    }
}
