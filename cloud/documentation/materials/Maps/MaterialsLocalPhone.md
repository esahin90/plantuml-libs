# MaterialsLocalPhone
```text
elements/materials/Maps/MaterialsLocalPhone
```
| Icon | Element | Card |
| :-: | :-: | --- |
| ![MaterialsLocalPhone icon](../../../icons/materials/Maps/MaterialsLocalPhone.png) | ![MaterialsLocalPhone element](MaterialsLocalPhone.element.png) | ![MaterialsLocalPhone card](MaterialsLocalPhone.card.png) |
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

' loads the MaterialsLocalPhone element
include('elements/materials/Maps/MaterialsLocalPhone')
MaterialsLocalPhone('element', 'Local Phone', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the AWS style
include('styles/aws')

' loads the MaterialsLocalPhone element
include('elements/materials/Maps/MaterialsLocalPhone')
MaterialsLocalPhone('element', 'Local Phone', 'an optional tech field')
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

' loads the MaterialsLocalPhone card
include('elements/materials/Maps/MaterialsLocalPhone')
MaterialsLocalPhoneCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../../../"

' loads the library
!include ../../../library.puml

' loads the GCP style
include('styles/gcp')

' loads the MaterialsLocalPhone card
include('elements/materials/Maps/MaterialsLocalPhone')
MaterialsLocalPhoneCard('card', 'an optional functional name', 'Molestiae praesentium aut natus dolorem. Aut consequatur fugiat a consequatur ut.')
@enduml
```