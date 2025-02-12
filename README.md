## Helm chart for Simple-Data-Exchanger

This helm chart installs the SDE application which consists of
     
   * [Frontend](https://github.com/eclipse-tractusx/managed-simple-data-exchanger-frontend)
   * [Backend](https://github.com/eclipse-tractusx/managed-simple-data-exchanger-backend) 
    
## Installation

To install the chart with the release name portal:

 ```shell
  helm repo add sde-repo https://eclipse-tractusx.github.io/charts/dev 
  helm search repo sde-repo/sde
  helm install -f your-values.yaml release-name sde/sde-app 
 ``` 
## Requirements

| Repository                                         | Name       | Version  |
|--------------------------------------------------- |------------|--------- |
| `https://charts.bitnami.com/bitnami`               | postgresql | 11.9.13  |                     
	
### Licenses
For used licenses, please see the [NOTICE](https://github.com/eclipse-tractusx/managed-simple-data-exchanger/blob/main/NOTICE.md).

### Documentation
 Docs reference link can be found here [docs](https://github.com/catenax-ng/tx-managed-simple-data-exchanger/blob/main/docs/install.md).

## Notice for Docker image

This application provides container images for demonstration purposes.

DockerHub: https://hub.docker.com/r/tractusx/managed-simple-data-exchanger-backend

DockerHub: https://hub.docker.com/r/tractusx/managed-simple-data-exchanger-frontend 

Eclipse Tractus-X product(s) installed within the image:

- GitHub: https://github.com/eclipse-tractusx/managed-simple-data-exchanger
- Project home: https://projects.eclipse.org/projects/automotive.tractusx
- Project license: [Apache License, Version 2.0] https://github.com/eclipse-tractusx/managed-simple-data-exchanger/blob/main/LICENSE

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.
