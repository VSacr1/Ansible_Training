pipeline{
	agent any 
	
	stages {
		stage('Deploy') {
			steps {
				sh "ansible-playbook playbooks/playbook-1.yaml"
			}
		}
	}
}
