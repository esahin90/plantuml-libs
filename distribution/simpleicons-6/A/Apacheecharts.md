# Apacheecharts


```text
simpleicons-6/A/Apacheecharts
```

```text
include('simpleicons-6/A/Apacheecharts')
```



| Illustration | Apacheecharts |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-6/A/Apacheecharts.png) | ![illustration for Apacheecharts](../../simpleicons-6/A/Apacheecharts.Local.png) |




## Apacheecharts

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-6/bootstrap')

' loads the Item which embeds the element Apacheecharts
include('simpleicons-6/A/Apacheecharts')

' renders the element
Apacheecharts('Apacheecharts', 'Apacheecharts', 'an optional tech label')
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
include('simpleicons-6/bootstrap')

' loads the Item which embeds the element Apacheecharts
include('simpleicons-6/A/Apacheecharts')

' renders the element
Apacheecharts('Apacheecharts', 'Apacheecharts', 'an optional tech label')
@enduml
```
