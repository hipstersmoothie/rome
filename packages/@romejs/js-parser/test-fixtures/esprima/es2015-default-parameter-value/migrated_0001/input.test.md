# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-default-parameter-value > migrated_0001`

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
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 0
      index: 21
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'f'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 10
            index: 10
            line: 1
          }
          start: Object {
            column: 9
            index: 9
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 20
          index: 20
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      body: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 20
            index: 20
            line: 1
          }
          start: Object {
            column: 18
            index: 18
            line: 1
          }
        }
      }
      head: FunctionHead {
        async: false
        generator: false
        hasHoistedVars: false
        predicate: undefined
        rest: undefined
        returnType: undefined
        thisType: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 18
            index: 18
            line: 1
          }
          start: Object {
            column: 10
            index: 10
            line: 1
          }
        }
        params: Array [
          BindingAssignmentPattern {
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 16
                index: 16
                line: 1
              }
              start: Object {
                column: 11
                index: 11
                line: 1
              }
            }
            right: NumericLiteral {
              value: 1
              format: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 16
                  index: 16
                  line: 1
                }
                start: Object {
                  column: 15
                  index: 15
                  line: 1
                }
              }
            }
            left: BindingIdentifier {
              name: 'a'
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 12
                  index: 12
                  line: 1
                }
                start: Object {
                  column: 11
                  index: 11
                  line: 1
                }
              }
              meta: PatternMeta {
                optional: undefined
                typeAnnotation: undefined
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 12
                    index: 12
                    line: 1
                  }
                  start: Object {
                    column: 11
                    index: 11
                    line: 1
                  }
                }
              }
            }
          }
        ]
      }
    }
  ]
}
```
