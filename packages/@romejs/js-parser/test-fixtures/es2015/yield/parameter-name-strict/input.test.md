# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > yield > parameter-name-strict`

```javascript
Program {
  comments: Array []
  corrupt: false
  filename: 'input.js'
  hasHoistedVars: false
  interpreter: undefined
  mtime: undefined
  sourceType: 'script'
  syntax: Array []
  loc: Object {
    filename: 'input.js'
    end: Object {
      column: 21
      index: 35
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  directives: Array [
    Directive {
      value: 'use strict'
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 13
          index: 13
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
    }
  ]
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'yield is a reserved word'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 17
          index: 31
          line: 2
        }
        start: Object {
          column: 12
          index: 26
          line: 2
        }
      }
    }
  ]
  body: Array [
    FunctionDeclaration {
      id: BindingIdentifier {
        name: 'fn'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 11
            index: 25
            line: 2
          }
          start: Object {
            column: 9
            index: 23
            line: 2
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 21
          index: 35
          line: 2
        }
        start: Object {
          column: 0
          index: 14
          line: 2
        }
      }
      body: BlockStatement {
        body: Array []
        directives: Array []
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 21
            index: 35
            line: 2
          }
          start: Object {
            column: 19
            index: 33
            line: 2
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
            column: 19
            index: 33
            line: 2
          }
          start: Object {
            column: 11
            index: 25
            line: 2
          }
        }
        params: Array [
          BindingIdentifier {
            name: 'yield'
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 17
                index: 31
                line: 2
              }
              start: Object {
                column: 12
                index: 26
                line: 2
              }
            }
            meta: PatternMeta {
              optional: undefined
              typeAnnotation: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 17
                  index: 31
                  line: 2
                }
                start: Object {
                  column: 12
                  index: 26
                  line: 2
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
