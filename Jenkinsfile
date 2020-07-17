node{
   stage('SCM Checkout'){
   git 'https://github.com/akhaitan-salesforce/training'
   }
   
   stage('Clean'){
   sh 'mvn clean'
   
   }
   stage('Install'){
   sh 'mvn package'
   
   }
}
