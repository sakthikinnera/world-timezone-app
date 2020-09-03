Pipeline
 {
  agent any
   stages{
    stage('build'){
     steps{
      bat 'mvn clean install'
      }
      }
   stage('Deploy Application To MuleSoft CloudHub'){
    steps{
     bat 'mvn package deploy -DmuleDeploy'
      }
      }
 }
}
