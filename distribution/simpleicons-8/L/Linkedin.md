# Linkedin


```text
simpleicons-8/L/Linkedin
```

```text
include('simpleicons-8/L/Linkedin')
```



| Illustration | Linkedin |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-8/L/Linkedin.png) | ![illustration for Linkedin](../../simpleicons-8/L/Linkedin.Local.png) |




## Linkedin

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-8/bootstrap')

' loads the Item which embeds the element Linkedin
include('simpleicons-8/L/Linkedin')

' renders the element
Linkedin('Linkedin', 'Linkedin', 'an optional tech label', 'an optional description')
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

' loads the Item which embeds the element Linkedin
include('simpleicons-8/L/Linkedin')

' renders the element
Linkedin('Linkedin', 'Linkedin', 'an optional tech label', 'an optional description')
@enduml
```
