# Group External Infrastructure3 Rd Party

```text
gcp/Group/GroupExternalInfrastructure3RdParty
```

```text
include('gcp/Group/GroupExternalInfrastructure3RdParty')
```

|group|
|---|
|![](GroupExternalInfrastructure3RdParty.group.local.png)|



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
' loads the GroupExternalInfrastructure3RdParty element
include('gcp/Group/GroupExternalInfrastructure3RdParty')
GroupExternalInfrastructure3RdParty('group_external_infrastructure_3_rd_party', 'Group External Infrastructure3 Rd Party', 'an optional tech field')
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
' loads the GroupExternalInfrastructure3RdParty element
include('gcp/Group/GroupExternalInfrastructure3RdParty')
GroupExternalInfrastructure3RdParty('group_external_infrastructure_3_rd_party', 'Group External Infrastructure3 Rd Party', 'an optional tech field')
@enduml
```
