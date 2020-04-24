# swaggerhub-custom-rules-library
 Public Custom Rules libary for SwaggerHub API Standardization

 Add rules to this repository that can be used in SwaggerHub's API standardiztion

 YAML Format:
 
```yaml
 Rule Name:
  description: User Friendly description, this will be the error message the user sees in the editor
  oas: [all|OAS2|OAS3] 
  severity: [Critical|Warning]
  enabled: [true|false]
  rule:
    path: $.path.in.yaml
    type: [pattern|match]
    options:
      match: matching regular expression
```
 