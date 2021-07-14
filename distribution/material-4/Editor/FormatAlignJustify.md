# FormatAlignJustify


```text
material-4/Editor/FormatAlignJustify
```

```text
include('material-4/Editor/FormatAlignJustify')
```



| Illustration | FormatAlignJustify |
| :---: | :---: |
| ![illustration for Illustration](../../material-4/Editor/FormatAlignJustify.png) | ![illustration for FormatAlignJustify](../../material-4/Editor/FormatAlignJustify.Local.png) |




## FormatAlignJustify

### Load remotely
```plantuml
@startuml
' configures the library
!global $LIB_BASE_LOCATION="https://github.com/tmorin/plantuml-libs/distribution"

' loads the library's bootstrap
!include $LIB_BASE_LOCATION/bootstrap.puml

' loads the package bootstrap
include('material-4/bootstrap')

' loads the Item which embeds the element FormatAlignJustify
include('material-4/Editor/FormatAlignJustify')

' renders the element
FormatAlignJustify('FormatAlignJustify', 'Format Align Justify', 'an optional tech label')
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
include('material-4/bootstrap')

' loads the Item which embeds the element FormatAlignJustify
include('material-4/Editor/FormatAlignJustify')

' renders the element
FormatAlignJustify('FormatAlignJustify', 'Format Align Justify', 'an optional tech label')
@enduml
```
