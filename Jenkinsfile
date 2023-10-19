pipeline {
  agent any
  stages {
    stage('buildstage') {
      steps {
        sh '''sudo docker login -u poojapekamwar -p Pooja@1525
sudo docker build -t poojapekamwar/myrepo3:${BUILD_NUMBER} .
sudo docker push poojapekamwar/myrepo3:${BUILD_NUMBER}'''
      }
    }

  }
}