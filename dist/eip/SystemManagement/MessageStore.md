# Message Store

```text
eip/SystemManagement/MessageStore
```

```text
include('eip/SystemManagement/MessageStore')
```

|icon|element|
|---|---|
|![](MessageStore.png)|![](MessageStore.element.png)|



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
' loads the MessageStore element
include('eip/SystemManagement/MessageStore')
MessageStore('message_store', 'Message Store', 'an optional tech field')
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
' loads the MessageStore element
include('eip/SystemManagement/MessageStore')
MessageStore('message_store', 'Message Store', 'an optional tech field')
@enduml
```
