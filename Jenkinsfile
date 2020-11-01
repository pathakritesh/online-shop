node{

    stage('SCM Checkout')
    {
        git credentialsId: ' url: 'https://github.com/pathakritesh/online-shop.git'
    }
    
    stage('Run Docker Compose File')
    {
        sh 'sudo docker-compose build'
        sh 'sudo docker-compose up -d'
         
    }
}
