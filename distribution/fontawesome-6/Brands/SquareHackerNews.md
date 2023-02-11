# SquareHackerNews


```text
fontawesome-6/Brands/SquareHackerNews
```

```text
include('fontawesome-6/Brands/SquareHackerNews')
```



| Illustration | SquareHackerNews |
| :---: | :---: |
| ![illustration for Illustration](../../fontawesome-6/Brands/SquareHackerNews.png) | ![illustration for SquareHackerNews](../../fontawesome-6/Brands/SquareHackerNews.Local.png) |




## SquareHackerNews

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://raw.githubusercontent.com/tmorin/plantuml-libs/master/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element SquareHackerNews
include('fontawesome-6/Brands/SquareHackerNews')

' renders the element
SquareHackerNews('SquareHackerNews', 'Square Hacker News', 'an optional tech label', 'an optional description')
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
include('fontawesome-6/bootstrap')

' loads the Item which embeds the element SquareHackerNews
include('fontawesome-6/Brands/SquareHackerNews')

' renders the element
SquareHackerNews('SquareHackerNews', 'Square Hacker News', 'an optional tech label', 'an optional description')
@enduml
```
