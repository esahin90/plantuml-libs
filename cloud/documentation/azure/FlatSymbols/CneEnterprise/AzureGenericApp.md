# AzureGenericApp
```text
elements/azure/FlatSymbols/CneEnterprise/AzureGenericApp
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![AzureGenericApp icon](../../../../icons/azure/FlatSymbols/CneEnterprise/AzureGenericApp.png) | ![AzureGenericApp element](AzureGenericApp.element.png) | ![AzureGenericApp card](AzureGenericApp.card.png) |
## Element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the AWS style
include('styles/aws')

' loads the AzureGenericApp element
include('elements/azure/FlatSymbols/CneEnterprise/AzureGenericApp')
AzureGenericApp('element', 'Generic App', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the AWS style
include('styles/aws')

' loads the AzureGenericApp element
include('elements/azure/FlatSymbols/CneEnterprise/AzureGenericApp')
AzureGenericApp('element', 'Generic App', 'an optional tech field')
@enduml
```
## Card
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BRANCH="master"
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/" + $LIB_BRANCH + "/cloud"

' loads the library
!includeurl $LIB_BASE_LOCATION/library.puml

' loads the AWS style
include('styles/gcp')

' loads the AzureGenericApp card
include('elements/azure/FlatSymbols/CneEnterprise/AzureGenericApp')
AzureGenericAppCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../../"

' loads the library
!include ../../../../library.puml

' loads the GCP style
include('styles/gcp')

' loads the AzureGenericApp card
include('elements/azure/FlatSymbols/CneEnterprise/AzureGenericApp')
AzureGenericAppCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```