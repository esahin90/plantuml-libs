# Lyft


```text
simpleicons-8/L/Lyft
```

```text
include('simpleicons-8/L/Lyft')
```



| Illustration | Lyft |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/L/Lyft.png) | ![illustration for Lyft](../../simpleicons-8/L/Lyft.Local.png) |




## Lyft

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Lyft
include('simpleicons-8/L/Lyft')

' renders the element
Lyft('Lyft', 'Lyft', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Lyft
include('simpleicons-8/L/Lyft')

' renders the element
Lyft('Lyft', 'Lyft', 'an optional tech label', 'an optional description')
@enduml
```
