# Envelope


```text
fontawesome-5/Solid/Envelope
```

```text
include('fontawesome-5/Solid/Envelope')
```



| Illustration | Envelope |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-5/Solid/Envelope.png) | ![illustration for Envelope](../../fontawesome-5/Solid/Envelope.Local.png) |




## Envelope

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-5/bootstrap')

' loads the Item which embeds the element Envelope
include('fontawesome-5/Solid/Envelope')

' renders the element
Envelope('Envelope', 'Envelope', 'an optional tech label')
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
include('fontawesome-5/bootstrap')

' loads the Item which embeds the element Envelope
include('fontawesome-5/Solid/Envelope')

' renders the element
Envelope('Envelope', 'Envelope', 'an optional tech label')
@enduml
```
