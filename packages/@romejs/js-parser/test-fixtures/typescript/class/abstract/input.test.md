# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romejs/js-parser/index.test.ts --update-snapshots` to update.

## `typescript > class > abstract`

```javascript
Program {
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
      index: 255
      line: 8
    }
    start: Object {
      column: 0
      index: 0
      line: 1
    }
  }
  comments: Array [
    CommentLine {
      id: '0'
      value: ' `export abstract class {}` is not valid TypeScript.'
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 54
          index: 132
          line: 4
        }
        start: Object {
          column: 0
          index: 78
          line: 4
        }
      }
    }
    CommentLine {
      id: '1'
      value: ' `abstract class` is not valid as an expression.'
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 50
          index: 254
          line: 7
        }
        start: Object {
          column: 0
          index: 204
          line: 7
        }
      }
    }
  ]
  body: Array [
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'C1'
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 17
            index: 17
            line: 1
          }
          start: Object {
            column: 15
            index: 15
            line: 1
          }
        }
      }
      abstract: true
      loc: Object {
        filename: 'input.ts'
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
      meta: ClassHead {
        body: Array []
        implements: undefined
        superClass: undefined
        superTypeParameters: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.ts'
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
      }
    }
    ClassDeclaration {
      id: BindingIdentifier {
        name: 'C2'
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 25
            index: 46
            line: 2
          }
          start: Object {
            column: 23
            index: 44
            line: 2
          }
        }
      }
      abstract: true
      declare: true
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 28
          index: 49
          line: 2
        }
        start: Object {
          column: 0
          index: 21
          line: 2
        }
      }
      meta: ClassHead {
        body: Array []
        implements: undefined
        superClass: undefined
        superTypeParameters: undefined
        typeParameters: undefined
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 28
            index: 49
            line: 2
          }
          start: Object {
            column: 0
            index: 21
            line: 2
          }
        }
      }
    }
    ExportLocalDeclaration {
      exportKind: 'value'
      specifiers: undefined
      trailingComments: Array ['0']
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 27
          index: 77
          line: 3
        }
        start: Object {
          column: 0
          index: 50
          line: 3
        }
      }
      declaration: ClassDeclaration {
        id: BindingIdentifier {
          name: 'C3'
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 24
              index: 74
              line: 3
            }
            start: Object {
              column: 22
              index: 72
              line: 3
            }
          }
        }
        abstract: true
        trailingComments: Array ['0']
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 27
            index: 77
            line: 3
          }
          start: Object {
            column: 7
            index: 57
            line: 3
          }
        }
        meta: ClassHead {
          body: Array []
          implements: undefined
          superClass: undefined
          superTypeParameters: undefined
          trailingComments: undefined
          typeParameters: undefined
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 27
              index: 77
              line: 3
            }
            start: Object {
              column: 7
              index: 57
              line: 3
            }
          }
        }
      }
    }
    ExportDefaultDeclaration {
      leadingComments: Array ['0']
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 33
          index: 166
          line: 5
        }
        start: Object {
          column: 0
          index: 133
          line: 5
        }
      }
      declaration: ClassDeclaration {
        id: BindingIdentifier {
          name: '*default*'
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 33
              index: 166
              line: 5
            }
            start: Object {
              column: 15
              index: 148
              line: 5
            }
          }
        }
        abstract: true
        leadingComments: Array ['0']
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 33
            index: 166
            line: 5
          }
          start: Object {
            column: 15
            index: 148
            line: 5
          }
        }
        meta: ClassHead {
          body: Array []
          implements: undefined
          leadingComments: undefined
          superClass: undefined
          superTypeParameters: undefined
          typeParameters: undefined
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 33
              index: 166
              line: 5
            }
            start: Object {
              column: 15
              index: 148
              line: 5
            }
          }
        }
      }
    }
    ExportDefaultDeclaration {
      trailingComments: Array ['1']
      loc: Object {
        filename: 'input.ts'
        end: Object {
          column: 36
          index: 203
          line: 6
        }
        start: Object {
          column: 0
          index: 167
          line: 6
        }
      }
      declaration: ClassDeclaration {
        id: BindingIdentifier {
          name: 'C4'
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 32
              index: 199
              line: 6
            }
            start: Object {
              column: 30
              index: 197
              line: 6
            }
          }
        }
        abstract: true
        trailingComments: Array ['1']
        loc: Object {
          filename: 'input.ts'
          end: Object {
            column: 36
            index: 203
            line: 6
          }
          start: Object {
            column: 15
            index: 182
            line: 6
          }
        }
        meta: ClassHead {
          body: Array []
          implements: undefined
          superClass: undefined
          superTypeParameters: undefined
          trailingComments: undefined
          typeParameters: undefined
          loc: Object {
            filename: 'input.ts'
            end: Object {
              column: 36
              index: 203
              line: 6
            }
            start: Object {
              column: 15
              index: 182
              line: 6
            }
          }
        }
      }
    }
  ]
}
```
