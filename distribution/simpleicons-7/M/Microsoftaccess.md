# Microsoftaccess


```text
simpleicons-7/M/Microsoftaccess
```

```text
include('simpleicons-7/M/Microsoftaccess')
```



| Illustration | Microsoftaccess |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/M/Microsoftaccess.png) | ![illustration for Microsoftaccess](../../simpleicons-7/M/Microsoftaccess.Local.png) |




## Microsoftaccess

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Microsoftaccess
include('simpleicons-7/M/Microsoftaccess')

' renders the element
Microsoftaccess('Microsoftaccess', 'Microsoftaccess', 'an optional tech label')
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

' loads the Item which embeds the element Microsoftaccess
include('simpleicons-7/M/Microsoftaccess')

' renders the element
Microsoftaccess('Microsoftaccess', 'Microsoftaccess', 'an optional tech label')
@enduml
```
