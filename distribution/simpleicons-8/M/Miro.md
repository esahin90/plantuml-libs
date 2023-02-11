# Miro


```text
simpleicons-8/M/Miro
```

```text
include('simpleicons-8/M/Miro')
```



| Illustration | Miro |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/M/Miro.png) | ![illustration for Miro](../../simpleicons-8/M/Miro.Local.png) |




## Miro

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Miro
include('simpleicons-8/M/Miro')

' renders the element
Miro('Miro', 'Miro', 'an optional tech label', 'an optional description')
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
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Miro
include('simpleicons-8/M/Miro')

' renders the element
Miro('Miro', 'Miro', 'an optional tech label', 'an optional description')
@enduml
```
