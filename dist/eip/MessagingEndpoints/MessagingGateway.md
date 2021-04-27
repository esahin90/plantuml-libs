# Messaging Gateway

```text
eip/MessagingEndpoints/MessagingGateway
```

```text
include('eip/MessagingEndpoints/MessagingGateway')
```

|icon|element|
|---|---|
|![](MessagingGateway.png)|![](MessagingGateway.element.png)|



## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the eip bootstrap
include('eip/bootstrap')
' loads the MessagingGateway element
include('eip/MessagingEndpoints/MessagingGateway')
MessagingGateway('messaging_gateway', 'Messaging Gateway', 'an optional tech field')
@enduml
```
### Load locally
```plantuml
@startuml
' configures the library
!global $INCLUSION_MODE="local"
!global $LIB_BASE_LOCATION="../.."
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the eip bootstrap
include('eip/bootstrap')
' loads the MessagingGateway element
include('eip/MessagingEndpoints/MessagingGateway')
MessagingGateway('messaging_gateway', 'Messaging Gateway', 'an optional tech field')
@enduml
```
