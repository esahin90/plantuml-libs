# CorporateDataCenter


```text
aws-q3-2021/Resource/GroupIcons/CorporateDataCenter
```

```text
include('aws-q3-2021/Resource/GroupIcons/CorporateDataCenter')
```



| Illustration | CorporateDataCenter | CorporateDataCenterCard | CorporateDataCenterGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../aws-q3-2021/Resource/GroupIcons/CorporateDataCenter.png) | ![illustration for CorporateDataCenter](../../../aws-q3-2021/Resource/GroupIcons/CorporateDataCenter.Local.png) | ![illustration for CorporateDataCenterCard](../../../aws-q3-2021/Resource/GroupIcons/CorporateDataCenterCard.Local.png) | ![illustration for CorporateDataCenterGroup](../../../aws-q3-2021/Resource/GroupIcons/CorporateDataCenterGroup.Local.png) |




## CorporateDataCenter

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q3-2021/bootstrap')

' loads the Item which embeds the element CorporateDataCenter
include('aws-q3-2021/Resource/GroupIcons/CorporateDataCenter')

' renders the element
CorporateDataCenter('CorporateDataCenter', 'Corporate Data Center', 'an optional tech label')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q3-2021/bootstrap')

' loads the Item which embeds the element CorporateDataCenter
include('aws-q3-2021/Resource/GroupIcons/CorporateDataCenter')

' renders the element
CorporateDataCenter('CorporateDataCenter', 'Corporate Data Center', 'an optional tech label')
@enduml
```

## CorporateDataCenterCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q3-2021/bootstrap')

' loads the Item which embeds the element CorporateDataCenterCard
include('aws-q3-2021/Resource/GroupIcons/CorporateDataCenter')

' renders the element
CorporateDataCenterCard('CorporateDataCenterCard', 'Corporate Data Center Card', 'an optional description')
@enduml
```

### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../.."

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q3-2021/bootstrap')

' loads the Item which embeds the element CorporateDataCenterCard
include('aws-q3-2021/Resource/GroupIcons/CorporateDataCenter')

' renders the element
CorporateDataCenterCard('CorporateDataCenterCard', 'Corporate Data Center Card', 'an optional description')
@enduml
```

## CorporateDataCenterGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q3-2021/bootstrap')

' loads the Item which embeds the element CorporateDataCenterGroup
include('aws-q3-2021/Resource/GroupIcons/CorporateDataCenter')

' renders the element
CorporateDataCenterGroup('CorporateDataCenterGroup', 'Corporate Data Center Group', 'an optional tech label') {
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

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('aws-q3-2021/bootstrap')

' loads the Item which embeds the element CorporateDataCenterGroup
include('aws-q3-2021/Resource/GroupIcons/CorporateDataCenter')

' renders the element
CorporateDataCenterGroup('CorporateDataCenterGroup', 'Corporate Data Center Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```
