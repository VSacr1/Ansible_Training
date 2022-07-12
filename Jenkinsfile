pipeline{
	agent any 
	
	stages {
		stage('Deploy') {
			steps {
				sh "ansible-playbook -i playbooks/inventory.yaml playbooks/playbook-1.yaml"
			}
		}
	}
}
