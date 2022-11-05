# ServiceAzureChaosStudio


```text
azure-6/Item/Other/ServiceAzureChaosStudio
```

```text
include('azure-6/Item/Other/ServiceAzureChaosStudio')
```



| Illustration | ServiceAzureChaosStudio | ServiceAzureChaosStudioCard | ServiceAzureChaosStudioGroup |
| :---: | :---: | :---: | :---: |
| ![illustration for Illustration](../../../azure-6/Item/Other/ServiceAzureChaosStudio.png) | ![illustration for ServiceAzureChaosStudio](../../../azure-6/Item/Other/ServiceAzureChaosStudio.Local.png) | ![illustration for ServiceAzureChaosStudioCard](../../../azure-6/Item/Other/ServiceAzureChaosStudioCard.Local.png) | ![illustration for ServiceAzureChaosStudioGroup](../../../azure-6/Item/Other/ServiceAzureChaosStudioGroup.Local.png) |




## ServiceAzureChaosStudio

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceAzureChaosStudio
include('azure-6/Item/Other/ServiceAzureChaosStudio')

' renders the element
ServiceAzureChaosStudio('ServiceAzureChaosStudio', 'Service Azure Chaos Studio', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element ServiceAzureChaosStudio
include('azure-6/Item/Other/ServiceAzureChaosStudio')

' renders the element
ServiceAzureChaosStudio('ServiceAzureChaosStudio', 'Service Azure Chaos Studio', 'an optional tech label', 'an optional description')
@enduml
```

## ServiceAzureChaosStudioCard

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceAzureChaosStudioCard
include('azure-6/Item/Other/ServiceAzureChaosStudio')

' renders the element
ServiceAzureChaosStudioCard('ServiceAzureChaosStudioCard', 'Service Azure Chaos Studio Card', 'an optional description')
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

' loads the Item which embeds the element ServiceAzureChaosStudioCard
include('azure-6/Item/Other/ServiceAzureChaosStudio')

' renders the element
ServiceAzureChaosStudioCard('ServiceAzureChaosStudioCard', 'Service Azure Chaos Studio Card', 'an optional description')
@enduml
```

## ServiceAzureChaosStudioGroup

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('azure-6/bootstrap')

' loads the Item which embeds the element ServiceAzureChaosStudioGroup
include('azure-6/Item/Other/ServiceAzureChaosStudio')

' renders the element
ServiceAzureChaosStudioGroup('ServiceAzureChaosStudioGroup', 'Service Azure Chaos Studio Group', 'an optional tech label') {
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

' loads the Item which embeds the element ServiceAzureChaosStudioGroup
include('azure-6/Item/Other/ServiceAzureChaosStudio')

' renders the element
ServiceAzureChaosStudioGroup('ServiceAzureChaosStudioGroup', 'Service Azure Chaos Studio Group', 'an optional tech label') {
    note as note
        the content of the group
    end note
}
@enduml
```
