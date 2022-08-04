# Gunicorn


```text
simpleicons-7/G/Gunicorn
```

```text
include('simpleicons-7/G/Gunicorn')
```



| Illustration | Gunicorn |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/G/Gunicorn.png) | ![illustration for Gunicorn](../../simpleicons-7/G/Gunicorn.Local.png) |




## Gunicorn

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Gunicorn
include('simpleicons-7/G/Gunicorn')

' renders the element
Gunicorn('Gunicorn', 'Gunicorn', 'an optional tech label')
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

' loads the Item which embeds the element Gunicorn
include('simpleicons-7/G/Gunicorn')

' renders the element
Gunicorn('Gunicorn', 'Gunicorn', 'an optional tech label')
@enduml
```
