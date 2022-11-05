# ServiceVirtualMachinesClassic


```text
azure-6/Item/Compute/ServiceVirtualMachinesClassic
```

```text
include('azure-6/Item/Compute/ServiceVirtualMachinesClassic')
```



| Illustration | ServiceVirtualMachinesClassic | ServiceVirtualMachinesClassicCard | ServiceVirtualMachinesClassicGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-6/Item/Compute/ServiceVirtualMachinesClassic.png) | ![illustration for ServiceVirtualMachinesClassic](../../../azure-6/Item/Compute/ServiceVirtualMachinesClassic.Local.png) | ![illustration for ServiceVirtualMachinesClassicCard](../../../azure-6/Item/Compute/ServiceVirtualMachinesClassicCard.Local.png) | ![illustration for ServiceVirtualMachinesClassicGroup](../../../azure-6/Item/Compute/ServiceVirtualMachinesClassicGroup.Local.png) |




## ServiceVirtualMachinesClassic

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceVirtualMachinesClassic
include('azure-6/Item/Compute/ServiceVirtualMachinesClassic')

' renders the element
ServiceVirtualMachinesClassic('ServiceVirtualMachinesClassic', 'Service Virtual Machines Classic', 'an optional tech label', 'an optional description')
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
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceVirtualMachinesClassic
include('azure-6/Item/Compute/ServiceVirtualMachinesClassic')

' renders the element
ServiceVirtualMachinesClassic('ServiceVirtualMachinesClassic', 'Service Virtual Machines Classic', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceVirtualMachinesClassicCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceVirtualMachinesClassicCard
include('azure-6/Item/Compute/ServiceVirtualMachinesClassic')

' renders the element
ServiceVirtualMachinesClassicCard('ServiceVirtualMachinesClassicCard', 'Service Virtual Machines Classic Card', 'an optional description')
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
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceVirtualMachinesClassicCard
include('azure-6/Item/Compute/ServiceVirtualMachinesClassic')

' renders the element
ServiceVirtualMachinesClassicCard('ServiceVirtualMachinesClassicCard', 'Service Virtual Machines Classic Card', 'an optional description')
@enduml
```

## ServiceVirtualMachinesClassicGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceVirtualMachinesClassicGroup
include('azure-6/Item/Compute/ServiceVirtualMachinesClassic')

' renders the element
ServiceVirtualMachinesClassicGroup('ServiceVirtualMachinesClassicGroup', 'Service Virtual Machines Classic Group', 'an optional tech label') {
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
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceVirtualMachinesClassicGroup
include('azure-6/Item/Compute/ServiceVirtualMachinesClassic')

' renders the element
ServiceVirtualMachinesClassicGroup('ServiceVirtualMachinesClassicGroup', 'Service Virtual Machines Classic Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```
