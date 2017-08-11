node {
   stage ('Preparation'){
       checkout scm
   }
   stage ('Build'){
       sh 'docker build -t tcrud/ca:1.0'
   }
   stage('Run') {
       sh 'docker run tcrud/ca:1.0'
   }
}
