# Traefikmesh


```text
simpleicons-8/T/Traefikmesh
```

```text
include('simpleicons-8/T/Traefikmesh')
```



| Illustration | Traefikmesh |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/T/Traefikmesh.png) | ![illustration for Traefikmesh](../../simpleicons-8/T/Traefikmesh.Local.png) |




## Traefikmesh

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Traefikmesh
include('simpleicons-8/T/Traefikmesh')

' renders the element
Traefikmesh('Traefikmesh', 'Traefikmesh', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Traefikmesh
include('simpleicons-8/T/Traefikmesh')

' renders the element
Traefikmesh('Traefikmesh', 'Traefikmesh', 'an optional tech label', 'an optional description')
@enduml
```
