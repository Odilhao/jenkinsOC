
node {

 stage('Criando o projeto') {
sh '''ansible-playbook -i "localhost," -c local --extra-vars \'{"projeto":'${JOB_NAME}'}\'  /var/lib/jenkins/ansibles/create-project.yaml 
'''


}
}
