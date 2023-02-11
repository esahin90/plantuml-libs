# GroupPublicSubnet


```text
aws-q1-2023/Group/GroupPublicSubnet
```

```text
include('aws-q1-2023/Group/GroupPublicSubnet')
```



| Illustration | GroupPublicSubnet |
| :---: | :---: |
| ![illustration for Illustration](../../aws-q1-2023/Resource/GroupIcons/VpcSubnetPublic.png) | ![illustration for GroupPublicSubnet](../../aws-q1-2023/Group/GroupPublicSubnet.Local.png) |




## GroupPublicSubnet

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2023/bootstrap')

' loads the Item which embeds the element GroupPublicSubnet
include('aws-q1-2023/Group/GroupPublicSubnet')

GroupPublicSubnet('GroupPublicSubnet', 'Group Public Subnet', 'an optional tech label') {
  note as note
  the content of the boundary
  end note
}
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q1-2023/bootstrap')

' loads the Item which embeds the element GroupPublicSubnet
include('aws-q1-2023/Group/GroupPublicSubnet')

GroupPublicSubnet('GroupPublicSubnet', 'Group Public Subnet', 'an optional tech label') {
  note as note
  the content of the boundary
  end note
}
@enduml
```
