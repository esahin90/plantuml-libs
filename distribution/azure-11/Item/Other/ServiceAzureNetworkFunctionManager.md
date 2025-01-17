# ServiceAzureNetworkFunctionManager


```text
azure-11/Item/Other/ServiceAzureNetworkFunctionManager
```

```text
include('azure-11/Item/Other/ServiceAzureNetworkFunctionManager')
```



| Illustration | ServiceAzureNetworkFunctionManager | ServiceAzureNetworkFunctionManagerCard | ServiceAzureNetworkFunctionManagerGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-11/Item/Other/ServiceAzureNetworkFunctionManager.png) | ![illustration for ServiceAzureNetworkFunctionManager](../../../azure-11/Item/Other/ServiceAzureNetworkFunctionManager.Local.png) | ![illustration for ServiceAzureNetworkFunctionManagerCard](../../../azure-11/Item/Other/ServiceAzureNetworkFunctionManagerCard.Local.png) | ![illustration for ServiceAzureNetworkFunctionManagerGroup](../../../azure-11/Item/Other/ServiceAzureNetworkFunctionManagerGroup.Local.png) |



## Sprites
The item provides the following sriptes:

- `<$ServiceAzureNetworkFunctionManagerXs>`
- `<$ServiceAzureNetworkFunctionManagerSm>`
- `<$ServiceAzureNetworkFunctionManagerMd>`
- `<$ServiceAzureNetworkFunctionManagerLg>`





## ServiceAzureNetworkFunctionManager

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceAzureNetworkFunctionManager
include('azure-11/Item/Other/ServiceAzureNetworkFunctionManager')

' renders the element
ServiceAzureNetworkFunctionManager('ServiceAzureNetworkFunctionManager', 'Service Azure Network Function Manager', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceAzureNetworkFunctionManager
include('azure-11/Item/Other/ServiceAzureNetworkFunctionManager')

' renders the element
ServiceAzureNetworkFunctionManager('ServiceAzureNetworkFunctionManager', 'Service Azure Network Function Manager', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceAzureNetworkFunctionManagerCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceAzureNetworkFunctionManagerCard
include('azure-11/Item/Other/ServiceAzureNetworkFunctionManager')

' renders the element
ServiceAzureNetworkFunctionManagerCard('ServiceAzureNetworkFunctionManagerCard', 'Service Azure Network Function Manager Card', 'an optional description')
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

' loads the Item which embeds the element ServiceAzureNetworkFunctionManagerCard
include('azure-11/Item/Other/ServiceAzureNetworkFunctionManager')

' renders the element
ServiceAzureNetworkFunctionManagerCard('ServiceAzureNetworkFunctionManagerCard', 'Service Azure Network Function Manager Card', 'an optional description')
@enduml
```

## ServiceAzureNetworkFunctionManagerGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-11/bootstrap')

' loads the Item which embeds the element ServiceAzureNetworkFunctionManagerGroup
include('azure-11/Item/Other/ServiceAzureNetworkFunctionManager')

' renders the element
ServiceAzureNetworkFunctionManagerGroup('ServiceAzureNetworkFunctionManagerGroup', 'Service Azure Network Function Manager Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceAzureNetworkFunctionManagerGroup
include('azure-11/Item/Other/ServiceAzureNetworkFunctionManager')

' renders the element
ServiceAzureNetworkFunctionManagerGroup('ServiceAzureNetworkFunctionManagerGroup', 'Service Azure Network Function Manager Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```

