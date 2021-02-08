node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhubid') {

        def customImage = docker.build("kasi123/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
