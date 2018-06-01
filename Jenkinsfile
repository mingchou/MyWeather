node {
    def app

    stage('Checkout') {
	echo 'Checkout'
	checkout scm
    }

    stage('Build') {
	echo 'Build'
	echo $PWD
        /* app = docker.build("mingchou/my_weather") */
    }

    stage('Deploy') {
	echo 'Deploy'
    }
}
