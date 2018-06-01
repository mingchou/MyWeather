node {
    def app

    stage('Checkout') {
	echo 'Checkout'
	checkout scm
    }

    stage('Build') {
	echo 'Build'
        app = docker.build("my_weather_${env.BUILD_ID}")
    }

    stage('Deploy') {
	echo 'Deploy'
    }
}
