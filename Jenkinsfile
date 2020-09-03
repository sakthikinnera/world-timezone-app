Pipeline
 {
 agent any
stages{
stage(‘Build Application’){
steps{
//sh ‘mvn clean install’--- for Linux
bat ‘mvn clean install’
}
}
stage(‘Deploy Application To MuleSoft CloudHub’){
steps{
bat ‘mvn package deploy -DmuleDeploy’
}
}
}
}
