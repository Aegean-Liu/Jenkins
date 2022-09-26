node('slave'){
    container('dind-kubectl'){
        stage('deploy'){
            sh 'ls'
            sh 'kubectl apply -f ./jenkins/redis-deploy.yaml'
        }
        
    }
}
