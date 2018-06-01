node {
    def app

    stage('Checkout') {
	echo 'Checkout'
	checkout scm
    }

    stage('Build') {
	echo 'Build'
        app = docker.build("mingchou/MyWeather")
    }

    stage('Deploy') {
	echo 'Deploy'
    }
}
