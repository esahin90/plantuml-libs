# ServiceHosts


```text
azure-11/Item/Compute/ServiceHosts
```

```text
include('azure-11/Item/Compute/ServiceHosts')
```



| Illustration | ServiceHosts | ServiceHostsCard | ServiceHostsGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-11/Item/Compute/ServiceHosts.png) | ![illustration for ServiceHosts](../../../azure-11/Item/Compute/ServiceHosts.Local.png) | ![illustration for ServiceHostsCard](../../../azure-11/Item/Compute/ServiceHostsCard.Local.png) | ![illustration for ServiceHostsGroup](../../../azure-11/Item/Compute/ServiceHostsGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceHostsXs>`
- `<$ServiceHostsSm>`
- `<$ServiceHostsMd>`
- `<$ServiceHostsLg>`





## ServiceHosts

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceHosts
include('azure-11/Item/Compute/ServiceHosts')

' renders the element
ServiceHosts('ServiceHosts', 'Service Hosts', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceHosts
include('azure-11/Item/Compute/ServiceHosts')

' renders the element
ServiceHosts('ServiceHosts', 'Service Hosts', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceHostsCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceHostsCard
include('azure-11/Item/Compute/ServiceHosts')

' renders the element
ServiceHostsCard('ServiceHostsCard', 'Service Hosts Card', 'an optional description')
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

' loads the Item which embeds the element ServiceHostsCard
include('azure-11/Item/Compute/ServiceHosts')

' renders the element
ServiceHostsCard('ServiceHostsCard', 'Service Hosts Card', 'an optional description')
@enduml
```

## ServiceHostsGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceHostsGroup
include('azure-11/Item/Compute/ServiceHosts')

' renders the element
ServiceHostsGroup('ServiceHostsGroup', 'Service Hosts Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceHostsGroup
include('azure-11/Item/Compute/ServiceHosts')

' renders the element
ServiceHostsGroup('ServiceHostsGroup', 'Service Hosts Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

