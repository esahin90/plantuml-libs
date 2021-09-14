# Edotleclerc


```text
simpleicons-5/E/Edotleclerc
```

```text
include('simpleicons-5/E/Edotleclerc')
```



| Illustration | Edotleclerc |
| :---: | :---: |
| ![illustration for Illustration](../../simpleicons-5/E/Edotleclerc.png) | ![illustration for Edotleclerc](../../simpleicons-5/E/Edotleclerc.Local.png) |




## Edotleclerc

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('simpleicons-5/bootstrap')

' loads the Item which embeds the element Edotleclerc
include('simpleicons-5/E/Edotleclerc')

' renders the element
Edotleclerc('Edotleclerc', 'Edotleclerc', 'an optional tech label')
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
include('simpleicons-5/bootstrap')

' loads the Item which embeds the element Edotleclerc
include('simpleicons-5/E/Edotleclerc')

' renders the element
Edotleclerc('Edotleclerc', 'Edotleclerc', 'an optional tech label')
@enduml
```
