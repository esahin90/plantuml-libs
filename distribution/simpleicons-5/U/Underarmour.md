# Underarmour


```text
simpleicons-5/U/Underarmour
```

```text
include('simpleicons-5/U/Underarmour')
```



| Illustration | Underarmour |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-5/U/Underarmour.png) | ![illustration for Underarmour](../../simpleicons-5/U/Underarmour.Local.png) |




## Underarmour

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-5/bootstrap')

' loads the Item which embeds the element Underarmour
include('simpleicons-5/U/Underarmour')

' renders the element
Underarmour('Underarmour', 'Underarmour', 'an optional tech label')
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
include('simpleicons-5/bootstrap')

' loads the Item which embeds the element Underarmour
include('simpleicons-5/U/Underarmour')

' renders the element
Underarmour('Underarmour', 'Underarmour', 'an optional tech label')
@enduml
```
