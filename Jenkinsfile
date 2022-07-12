pipeline{
	agent any 
	
	stages {
		stage('Deploy') {
			steps {
				sh "ansible-playbook -i playbooks/playbook-1.yaml"
			}
		}
	}
}
