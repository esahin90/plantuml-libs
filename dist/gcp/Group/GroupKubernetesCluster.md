# Group Kubernetes Cluster

```text
gcp/Group/GroupKubernetesCluster
```

```text
include('gcp/Group/GroupKubernetesCluster')
```

|group|
|---|
|![](GroupKubernetesCluster.group.local.png)|



## group
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the GroupKubernetesCluster element
include('gcp/Group/GroupKubernetesCluster')
GroupKubernetesCluster('group_kubernetes_cluster', 'Group Kubernetes Cluster', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the gcp bootstrap
include('gcp/bootstrap')
' loads the GroupKubernetesCluster element
include('gcp/Group/GroupKubernetesCluster')
GroupKubernetesCluster('group_kubernetes_cluster', 'Group Kubernetes Cluster', 'an optional tech field')
@enduml
```
