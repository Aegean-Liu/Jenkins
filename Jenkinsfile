node('slave'){
    checkout scm
    container('dind-kubectl'){
        stage('deploy'){
            sh 'ls'
            sh 'kubectl apply -f ./redis-deploy.yaml'
        }
        
    }
}
