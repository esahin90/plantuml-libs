# Gerrit


```text
simpleicons-8/G/Gerrit
```

```text
include('simpleicons-8/G/Gerrit')
```



| Illustration | Gerrit |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/G/Gerrit.png) | ![illustration for Gerrit](../../simpleicons-8/G/Gerrit.Local.png) |




## Gerrit

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Gerrit
include('simpleicons-8/G/Gerrit')

' renders the element
Gerrit('Gerrit', 'Gerrit', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Gerrit
include('simpleicons-8/G/Gerrit')

' renders the element
Gerrit('Gerrit', 'Gerrit', 'an optional tech label', 'an optional description')
@enduml
```
