# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > arrow-function > async-await-null`

```javascript
Program {
  comments: Array []
  corrupt: false
  diagnostics: Array []
  directives: Array []
  filename: 'input.ts'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'module'
  syntax: Array ['ts']
  loc: Object {
    filename: 'input.ts'
    end: Object {
      column: 0
      index: 27
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  body: Array [
    ExpressionStatement {
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 26
          index: 26
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      expression: ArrowFunctionExpression {
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 25
            index: 25
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        body: AwaitExpression {
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 25
              index: 25
              line: 1
            }
            start: Object {
              column: 15
              index: 15
              line: 1
            }
          }
          argument: NullLiteral {
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 25
                index: 25
                line: 1
              }
              start: Object {
                column: 21
                index: 21
                line: 1
              }
            }
          }
        }
        head: FunctionHead {
          async: true
          hasHoistedVars: false
          params: Array []
          predicate: undefined
          rest: undefined
          returnType: undefined
          thisType: undefined
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 15
              index: 15
              line: 1
            }
            start: Object {
              column: 0
              index: 0
              line: 1
            }
          }
          typeParameters: TSTypeParameterDeclaration {
            loc: Object {
              filename: 'input.ts'
              end: Object {
                column: 9
                index: 9
                line: 1
              }
              start: Object {
                column: 6
                index: 6
                line: 1
              }
            }
            params: Array [
              TSTypeParameter {
                name: 'T'
                constraint: undefined
                default: undefined
                loc: Object {
                  filename: 'input.ts'
                  end: Object {
                    column: 8
                    index: 8
                    line: 1
                  }
                  start: Object {
                    column: 7
                    index: 7
                    line: 1
                  }
                }
              }
            ]
          }
        }
      }
    }
  ]
}
```
