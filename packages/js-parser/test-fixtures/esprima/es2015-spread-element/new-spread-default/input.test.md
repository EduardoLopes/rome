# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-spread-element > new-spread-default`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-spread-element/new-spread-default/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-spread-element/new-spread-default/input.js"
		end: Object {
			column: 0
			index: 20
			line: 2
		}
		start: Object {
			column: 0
			index: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-spread-element/new-spread-default/input.js"
				end: Object {
					column: 19
					index: 19
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSNewExpression {
				optional: undefined
				typeArguments: undefined
				loc: Object {
					filename: "esprima/es2015-spread-element/new-spread-default/input.js"
					end: Object {
						column: 18
						index: 18
						line: 1
					}
					start: Object {
						column: 0
						index: 0
						line: 1
					}
				}
				callee: JSReferenceIdentifier {
					name: "f"
					loc: Object {
						filename: "esprima/es2015-spread-element/new-spread-default/input.js"
						identifierName: "f"
						end: Object {
							column: 5
							index: 5
							line: 1
						}
						start: Object {
							column: 4
							index: 4
							line: 1
						}
					}
				}
				arguments: Array [
					JSReferenceIdentifier {
						name: "g"
						loc: Object {
							filename: "esprima/es2015-spread-element/new-spread-default/input.js"
							identifierName: "g"
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
					JSSpreadElement {
						loc: Object {
							filename: "esprima/es2015-spread-element/new-spread-default/input.js"
							end: Object {
								column: 17
								index: 17
								line: 1
							}
							start: Object {
								column: 9
								index: 9
								line: 1
							}
						}
						argument: JSAssignmentExpression {
							operator: "="
							loc: Object {
								filename: "esprima/es2015-spread-element/new-spread-default/input.js"
								end: Object {
									column: 17
									index: 17
									line: 1
								}
								start: Object {
									column: 12
									index: 12
									line: 1
								}
							}
							left: JSAssignmentIdentifier {
								name: "h"
								loc: Object {
									filename: "esprima/es2015-spread-element/new-spread-default/input.js"
									identifierName: "h"
									end: Object {
										column: 13
										index: 13
										line: 1
									}
									start: Object {
										column: 12
										index: 12
										line: 1
									}
								}
							}
							right: JSReferenceIdentifier {
								name: "i"
								loc: Object {
									filename: "esprima/es2015-spread-element/new-spread-default/input.js"
									identifierName: "i"
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