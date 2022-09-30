# github-actions-update-scs-repo-image-tag

Writes a value (i.e. a docker image tag) into ``values.yml``

````
===============                                               ===================
= xyz-service =  =github-actions-update-scs-repo-image-tag => = scs-xyz-service =
===============                                               ===================
````

## Inputs
| Name          | Required      | Description   | 
| ------------- | ------------- | ------------- |
| short-sha     | yes           | Image tag of the docker container to write to values.yml |
| scs-name      | yes           | Folder name where the values.yml resides |
| service-name  | yes           | Root node name in the values.yml |


