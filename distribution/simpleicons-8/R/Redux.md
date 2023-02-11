# Redux


```text
simpleicons-8/R/Redux
```

```text
include('simpleicons-8/R/Redux')
```



| Illustration | Redux |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/R/Redux.png) | ![illustration for Redux](../../simpleicons-8/R/Redux.Local.png) |




## Redux

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Redux
include('simpleicons-8/R/Redux')

' renders the element
Redux('Redux', 'Redux', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Redux
include('simpleicons-8/R/Redux')

' renders the element
Redux('Redux', 'Redux', 'an optional tech label', 'an optional description')
@enduml
```
