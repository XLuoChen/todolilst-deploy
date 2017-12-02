pipeline{
  agent any

  stages{
    stage('Deploy'){
      steps{
        sh 'ansible-playbook /var/lib/jenkins/workspace/todolist-deploy/deploy.yml --extra-vars="ansible_become_pass=remote"'
      }
    }
  }
}