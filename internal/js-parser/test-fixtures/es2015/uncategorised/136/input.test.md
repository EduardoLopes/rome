# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 136`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/136/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/136/input.js"
		end: Object {
			column: 29
			line: 1
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSClassDeclaration {
			id: JSBindingIdentifier {
				name: "A"
				loc: Object {
					filename: "es2015/uncategorised/136/input.js"
					identifierName: "A"
					end: Object {
						column: 7
						line: 1
					}
					start: Object {
						column: 6
						line: 1
					}
				}
			}
			loc: Object {
				filename: "es2015/uncategorised/136/input.js"
				end: Object {
					column: 29
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			meta: JSClassHead {
				implements: undefined
				superClass: undefined
				superTypeParameters: undefined
				typeParameters: undefined
				loc: Object {
					filename: "es2015/uncategorised/136/input.js"
					end: Object {
						column: 29
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				body: Array [
					JSClassMethod {
						kind: "method"
						key: JSComputedPropertyKey {
							value: JSReferenceIdentifier {
								name: "foo"
								loc: Object {
									filename: "es2015/uncategorised/136/input.js"
									identifierName: "foo"
									end: Object {
										column: 21
										line: 1
									}
									start: Object {
										column: 18
										line: 1
									}
								}
							}
							loc: Object {
								filename: "es2015/uncategorised/136/input.js"
								end: Object {
									column: 22
									line: 1
								}
								start: Object {
									column: 17
									line: 1
								}
							}
						}
						loc: Object {
							filename: "es2015/uncategorised/136/input.js"
							end: Object {
								column: 27
								line: 1
							}
							start: Object {
								column: 10
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "es2015/uncategorised/136/input.js"
								end: Object {
									column: 27
									line: 1
								}
								start: Object {
									column: 25
									line: 1
								}
							}
						}
						head: JSFunctionHead {
							async: false
							generator: false
							hasHoistedVars: false
							params: Array []
							rest: undefined
							returnType: undefined
							thisType: undefined
							typeParameters: undefined
							loc: Object {
								filename: "es2015/uncategorised/136/input.js"
								end: Object {
									column: 24
									line: 1
								}
								start: Object {
									column: 22
									line: 1
								}
							}
						}
						meta: JSClassPropertyMeta {
							abstract: false
							accessibility: undefined
							optional: false
							readonly: false
							static: true
							typeAnnotation: undefined
							start: Object {
								column: 10
								line: 1
							}
							loc: Object {
								filename: "es2015/uncategorised/136/input.js"
								end: Object {
									column: 22
									line: 1
								}
								start: Object {
									column: 10
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

### `diagnostics`

```
✔ No known problems!

```