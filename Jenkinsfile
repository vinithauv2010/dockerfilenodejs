node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'DockerHub') {

        def customImage = docker.build("vinithauv2010/docker-webapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
