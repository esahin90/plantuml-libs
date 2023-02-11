# Deliveroo


```text
simpleicons-8/D/Deliveroo
```

```text
include('simpleicons-8/D/Deliveroo')
```



| Illustration | Deliveroo |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/D/Deliveroo.png) | ![illustration for Deliveroo](../../simpleicons-8/D/Deliveroo.Local.png) |




## Deliveroo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Deliveroo
include('simpleicons-8/D/Deliveroo')

' renders the element
Deliveroo('Deliveroo', 'Deliveroo', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Deliveroo
include('simpleicons-8/D/Deliveroo')

' renders the element
Deliveroo('Deliveroo', 'Deliveroo', 'an optional tech label', 'an optional description')
@enduml
```
