# Bamboo


```text
simpleicons-7/B/Bamboo
```

```text
include('simpleicons-7/B/Bamboo')
```



| Illustration | Bamboo |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/B/Bamboo.png) | ![illustration for Bamboo](../../simpleicons-7/B/Bamboo.Local.png) |




## Bamboo

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Bamboo
include('simpleicons-7/B/Bamboo')

' renders the element
Bamboo('Bamboo', 'Bamboo', 'an optional tech label')
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

' loads the Item which embeds the element Bamboo
include('simpleicons-7/B/Bamboo')

' renders the element
Bamboo('Bamboo', 'Bamboo', 'an optional tech label')
@enduml
```
