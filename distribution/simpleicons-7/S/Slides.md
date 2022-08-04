# Slides


```text
simpleicons-7/S/Slides
```

```text
include('simpleicons-7/S/Slides')
```



| Illustration | Slides |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/S/Slides.png) | ![illustration for Slides](../../simpleicons-7/S/Slides.Local.png) |




## Slides

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Slides
include('simpleicons-7/S/Slides')

' renders the element
Slides('Slides', 'Slides', 'an optional tech label')
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
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Slides
include('simpleicons-7/S/Slides')

' renders the element
Slides('Slides', 'Slides', 'an optional tech label')
@enduml
```
