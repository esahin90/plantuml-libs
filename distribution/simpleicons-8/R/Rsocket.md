# Rsocket


```text
simpleicons-8/R/Rsocket
```

```text
include('simpleicons-8/R/Rsocket')
```



| Illustration | Rsocket |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Rsocket.png) | ![illustration for Rsocket](../../simpleicons-8/R/Rsocket.Local.png) |




## Rsocket

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Rsocket
include('simpleicons-8/R/Rsocket')

' renders the element
Rsocket('Rsocket', 'Rsocket', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Rsocket
include('simpleicons-8/R/Rsocket')

' renders the element
Rsocket('Rsocket', 'Rsocket', 'an optional tech label', 'an optional description')
@enduml
```
