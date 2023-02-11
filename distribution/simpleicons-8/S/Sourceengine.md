# Sourceengine


```text
simpleicons-8/S/Sourceengine
```

```text
include('simpleicons-8/S/Sourceengine')
```



| Illustration | Sourceengine |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/S/Sourceengine.png) | ![illustration for Sourceengine](../../simpleicons-8/S/Sourceengine.Local.png) |




## Sourceengine

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Sourceengine
include('simpleicons-8/S/Sourceengine')

' renders the element
Sourceengine('Sourceengine', 'Sourceengine', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Sourceengine
include('simpleicons-8/S/Sourceengine')

' renders the element
Sourceengine('Sourceengine', 'Sourceengine', 'an optional tech label', 'an optional description')
@enduml
```
