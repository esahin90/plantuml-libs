# ServiceSecurityCenter


```text
azure-11/Item/Security/ServiceSecurityCenter
```

```text
include('azure-11/Item/Security/ServiceSecurityCenter')
```



| Illustration | ServiceSecurityCenter | ServiceSecurityCenterCard | ServiceSecurityCenterGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-11/Item/Security/ServiceSecurityCenter.png) | ![illustration for ServiceSecurityCenter](../../../azure-11/Item/Security/ServiceSecurityCenter.Local.png) | ![illustration for ServiceSecurityCenterCard](../../../azure-11/Item/Security/ServiceSecurityCenterCard.Local.png) | ![illustration for ServiceSecurityCenterGroup](../../../azure-11/Item/Security/ServiceSecurityCenterGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceSecurityCenterXs>`
- `<$ServiceSecurityCenterSm>`
- `<$ServiceSecurityCenterMd>`
- `<$ServiceSecurityCenterLg>`





## ServiceSecurityCenter

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceSecurityCenter
include('azure-11/Item/Security/ServiceSecurityCenter')

' renders the element
ServiceSecurityCenter('ServiceSecurityCenter', 'Service Security Center', 'an optional tech label', 'an optional description')
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
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceSecurityCenter
include('azure-11/Item/Security/ServiceSecurityCenter')

' renders the element
ServiceSecurityCenter('ServiceSecurityCenter', 'Service Security Center', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceSecurityCenterCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceSecurityCenterCard
include('azure-11/Item/Security/ServiceSecurityCenter')

' renders the element
ServiceSecurityCenterCard('ServiceSecurityCenterCard', 'Service Security Center Card', 'an optional description')
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
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceSecurityCenterCard
include('azure-11/Item/Security/ServiceSecurityCenter')

' renders the element
ServiceSecurityCenterCard('ServiceSecurityCenterCard', 'Service Security Center Card', 'an optional description')
@enduml
```

## ServiceSecurityCenterGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceSecurityCenterGroup
include('azure-11/Item/Security/ServiceSecurityCenter')

' renders the element
ServiceSecurityCenterGroup('ServiceSecurityCenterGroup', 'Service Security Center Group', 'an optional tech label') {
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
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceSecurityCenterGroup
include('azure-11/Item/Security/ServiceSecurityCenter')

' renders the element
ServiceSecurityCenterGroup('ServiceSecurityCenterGroup', 'Service Security Center Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

