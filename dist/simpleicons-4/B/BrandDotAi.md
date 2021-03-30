# Brand Dot Ai

```text
simpleicons-4/B/BrandDotAi
```

```text
include('simpleicons-4/B/BrandDotAi')
```

|icon|element|
|---|---|
|![](BrandDotAi.png)|![](BrandDotAi.element.png)|



## element
### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/dist"
' loads the library
!include $LIB_BASE_LOCATION/bootstrap.puml
' loads the simpleicons-4 bootstrap
include('simpleicons-4/bootstrap')
' loads the BrandDotAi element
include('simpleicons-4/B/BrandDotAi')
BrandDotAi('brand_dot_ai', 'Brand Dot Ai', 'an optional tech field')
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
' loads the simpleicons-4 bootstrap
include('simpleicons-4/bootstrap')
' loads the BrandDotAi element
include('simpleicons-4/B/BrandDotAi')
BrandDotAi('brand_dot_ai', 'Brand Dot Ai', 'an optional tech field')
@enduml
```
