# Apacheopenoffice


```text
simpleicons-7/A/Apacheopenoffice
```

```text
include('simpleicons-7/A/Apacheopenoffice')
```



| Illustration | Apacheopenoffice |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-7/A/Apacheopenoffice.png) | ![illustration for Apacheopenoffice](../../simpleicons-7/A/Apacheopenoffice.Local.png) |




## Apacheopenoffice

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-7/bootstrap')

' loads the Item which embeds the element Apacheopenoffice
include('simpleicons-7/A/Apacheopenoffice')

' renders the element
Apacheopenoffice('Apacheopenoffice', 'Apacheopenoffice', 'an optional tech label')
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

' loads the Item which embeds the element Apacheopenoffice
include('simpleicons-7/A/Apacheopenoffice')

' renders the element
Apacheopenoffice('Apacheopenoffice', 'Apacheopenoffice', 'an optional tech label')
@enduml
```
