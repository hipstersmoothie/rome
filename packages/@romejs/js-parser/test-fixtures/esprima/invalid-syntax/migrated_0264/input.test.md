# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > invalid-syntax > migrated_0264`

```javascript
Program {
  comments: Array []
  corrupt: false
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
      index: 25
      line: 2
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  diagnostics: Array [
    Object {
      origins: Array [Object {category: 'js-parser'}]
      description: Object {
        advice: Array []
        category: 'parse/js'
        message: PARTIAL_BLESSED_DIAGNOSTIC_MESSAGE {value: 'Unexpected token, expected {'}
      }
      location: Object {
        filename: 'input.js'
        mtime: undefined
        sourceType: 'script'
        end: Object {
          column: 19
          index: 19
          line: 1
        }
        start: Object {
          column: 18
          index: 18
          line: 1
        }
      }
    }
  ]
  body: Array [
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'A'
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 7
            index: 7
            line: 1
          }
          start: Object {
            column: 6
            index: 6
            line: 1
          }
        }
      }
      loc: Object {
        filename: 'input.js'
        end: Object {
          column: 24
          index: 24
          line: 1
        }
        start: Object {
          column: 0
          index: 0
          line: 1
        }
      }
      meta: ClassHead {
        implements: undefined
        superTypeParameters: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.js'
          end: Object {
            column: 24
            index: 24
            line: 1
          }
          start: Object {
            column: 0
            index: 0
            line: 1
          }
        }
        superClass: ReferenceIdentifier {
          name: 'a'
          loc: Object {
            filename: 'input.js'
            end: Object {
              column: 17
              index: 17
              line: 1
            }
            start: Object {
              column: 16
              index: 16
              line: 1
            }
          }
        }
        body: Array [
          ClassProperty {
            key: StaticPropertyKey {
              value: Identifier {
                name: ''
                loc: Object {
                  filename: 'input.js'
                  end: Object {
                    column: 23
                    index: 23
                    line: 1
                  }
                  start: Object {
                    column: 22
                    index: 22
                    line: 1
                  }
                }
              }
              variance: undefined
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 23
                  index: 23
                  line: 1
                }
                start: Object {
                  column: 22
                  index: 22
                  line: 1
                }
              }
            }
            value: undefined
            definite: undefined
            typeAnnotation: undefined
            loc: Object {
              filename: 'input.js'
              end: Object {
                column: 23
                index: 23
                line: 1
              }
              start: Object {
                column: 22
                index: 22
                line: 1
              }
            }
            meta: ClassPropertyMeta {
              abstract: false
              accessibility: undefined
              optional: false
              readonly: false
              static: false
              typeAnnotation: undefined
              start: Object {
                column: 22
                index: 22
                line: 1
              }
              loc: Object {
                filename: 'input.js'
                end: Object {
                  column: 23
                  index: 23
                  line: 1
                }
                start: Object {
                  column: 22
                  index: 22
                  line: 1
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
