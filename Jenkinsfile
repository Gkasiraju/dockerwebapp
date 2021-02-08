node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhubid') {

        def customImage = sudo docker.build("kasi123/sample-ngnix:v1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
