node('slave'){
    container('dind-kubectl'){
        stage('deploy'){
            sh 'ls'
            sh 'kubectl apply -f ./redis-deploy.yaml'
        }
        
    }
}
