node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'kasi123') {

        def customImage = sudo docker.build("kasi123/sample-nodejs:v1")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
