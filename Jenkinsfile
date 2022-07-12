pipeline{
	agent any 
	
	stages {
		stage('Deploy') {
			sh "ansible-playbook -i playbooks/playbook-1.yaml"
		}
	}
}
