node {
    checkout scm
    
    docker.withRegistry('https://registry.hub.docker.com/', 'dockerhub-aigerim') {
    
    def customImage = docker.build("aigelya/node.js-app")
    
    /*Push the container to the custom Registry */
    custom.push()
    }
 }
