pipeline {
  agent any

   stages {
     
     stage('Fetch Scripts') {
           git branch: 'main', url: 'https://github.com/srikanth458hk/InfraRepo.git'
            terraform init 
            terraform apply --auto-approve
            }
        }
}
