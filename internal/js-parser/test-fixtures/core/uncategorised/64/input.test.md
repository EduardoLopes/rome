# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `core > uncategorised > 64`

### `ast`

```javascript
JSRoot {
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "core/uncategorised/64/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "core/uncategorised/64/input.js"
		end: Object {
			column: 11
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	comments: Array [
		CommentLine {
			id: "0"
			value: " Some comment"
			loc: Object {
				filename: "core/uncategorised/64/input.js"
				end: Object {
					column: 24
					line: 1
				}
				start: Object {
					column: 9
					line: 1
				}
			}
		}
	]
	body: Array [
		JSIfStatement {
			alternate: undefined
			loc: Object {
				filename: "core/uncategorised/64/input.js"
				end: Object {
					column: 11
					line: 2
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			test: JSReferenceIdentifier {
				name: "x"
				loc: Object {
					filename: "core/uncategorised/64/input.js"
					identifierName: "x"
					end: Object {
						column: 5
						line: 1
					}
					start: Object {
						column: 4
						line: 1
					}
				}
			}
			consequent: JSBlockStatement {
				directives: Array []
				loc: Object {
					filename: "core/uncategorised/64/input.js"
					end: Object {
						column: 11
						line: 2
					}
					start: Object {
						column: 7
						line: 1
					}
				}
				body: Array [
					JSExpressionStatement {
						leadingComments: Array ["0"]
						loc: Object {
							filename: "core/uncategorised/64/input.js"
							end: Object {
								column: 9
								line: 2
							}
							start: Object {
								column: 0
								line: 2
							}
						}
						expression: JSCallExpression {
							arguments: Array []
							leadingComments: undefined
							loc: Object {
								filename: "core/uncategorised/64/input.js"
								end: Object {
									column: 8
									line: 2
								}
								start: Object {
									column: 0
									line: 2
								}
							}
							callee: JSReferenceIdentifier {
								name: "doThat"
								leadingComments: undefined
								loc: Object {
									filename: "core/uncategorised/64/input.js"
									identifierName: "doThat"
									end: Object {
										column: 6
										line: 2
									}
									start: Object {
										column: 0
										line: 2
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

### `diagnostics`

```
✔ No known problems!

```