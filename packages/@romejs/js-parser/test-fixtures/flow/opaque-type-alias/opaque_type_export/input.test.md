# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `flow > opaque-type-alias > opaque_type_export`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array [
    'jsx'
    'flow'
  ]
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 32
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExportLocalDeclaration {
      exportKind: 'type'
      specifiers: undefined
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 31
          index: 31
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      declaration: FlowOpaqueType {
        id: BindingIdentifier {
          name: 'ID'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 21
              index: 21
              line: 1
            }
            start: Object {
              column: 19
              index: 19
              line: 1
            }
          }
        }
        supertype: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 31
            index: 31
            line: 1
          }
          start: Object {
            column: 7
            index: 7
            line: 1
          }
        }
        impltype: NumberKeywordTypeAnnotation {
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 30
              index: 30
              line: 1
            }
            start: Object {
              column: 24
              index: 24
              line: 1
            }
          }
        }
      }
    }
  ]
}
```
