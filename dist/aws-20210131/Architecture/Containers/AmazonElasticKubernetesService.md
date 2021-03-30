# Amazon Elastic Kubernetes Service

```text
aws-20210131/Architecture/Containers/AmazonElasticKubernetesService
```

```text
include('aws-20210131/Architecture/Containers/AmazonElasticKubernetesService')
```

|icon|card|element|group|
|---|---|---|---|
|![](AmazonElasticKubernetesService.png)|![](AmazonElasticKubernetesService.card.png)|![](AmazonElasticKubernetesService.element.png)|![](AmazonElasticKubernetesService.group.png)|



## card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AmazonElasticKubernetesService element
include('aws-20210131/Architecture/Containers/AmazonElasticKubernetesService')
AmazonElasticKubernetesServiceCard('amazon_elastic_kubernetes_service', 'Amazon Elastic Kubernetes Service', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AmazonElasticKubernetesService element
include('aws-20210131/Architecture/Containers/AmazonElasticKubernetesService')
AmazonElasticKubernetesServiceCard('amazon_elastic_kubernetes_service', 'Amazon Elastic Kubernetes Service', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```


## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AmazonElasticKubernetesService element
include('aws-20210131/Architecture/Containers/AmazonElasticKubernetesService')
AmazonElasticKubernetesService('amazon_elastic_kubernetes_service', 'Amazon Elastic Kubernetes Service', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AmazonElasticKubernetesService element
include('aws-20210131/Architecture/Containers/AmazonElasticKubernetesService')
AmazonElasticKubernetesService('amazon_elastic_kubernetes_service', 'Amazon Elastic Kubernetes Service', 'an optional tech field')
@enduml
```


## group
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AmazonElasticKubernetesService element
include('aws-20210131/Architecture/Containers/AmazonElasticKubernetesService')
AmazonElasticKubernetesServiceGroup('amazon_elastic_kubernetes_service', 'Amazon Elastic Kubernetes Service', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the aws-20210131 bootstrap
include('aws-20210131/bootstrap')
' loads the AmazonElasticKubernetesService element
include('aws-20210131/Architecture/Containers/AmazonElasticKubernetesService')
AmazonElasticKubernetesServiceGroup('amazon_elastic_kubernetes_service', 'Amazon Elastic Kubernetes Service', 'an optional tech field'){
note as note
the content of the group
end note
}
@enduml
```
