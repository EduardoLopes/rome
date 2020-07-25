# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 242`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	filename: "es2015/uncategorised/242/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/242/input.js"
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
	directives: Array [
		JSDirective {
			value: "use strict"
			loc: Object {
				filename: "es2015/uncategorised/242/input.js"
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
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {
					parts: Array [
						"eval"
						RAW_MARKUP {value: " is a reserved word"}
					]
				}
			}
			location: Object {
				filename: "es2015/uncategorised/242/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 19
					index: 19
					line: 1
				}
				start: Object {
					column: 15
					index: 15
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/242/input.js"
				end: Object {
					column: 31
					index: 31
					line: 1
				}
				start: Object {
					column: 14
					index: 14
					line: 1
				}
			}
			expression: JSArrowFunctionExpression {
				loc: Object {
					filename: "es2015/uncategorised/242/input.js"
					end: Object {
						column: 31
						index: 31
						line: 1
					}
					start: Object {
						column: 14
						index: 14
						line: 1
					}
				}
				body: JSNumericLiteral {
					value: 42
					format: undefined
					loc: Object {
						filename: "es2015/uncategorised/242/input.js"
						end: Object {
							column: 31
							index: 31
							line: 1
						}
						start: Object {
							column: 29
							index: 29
							line: 1
						}
					}
				}
				head: JSFunctionHead {
					async: false
					hasHoistedVars: false
					rest: undefined
					returnType: undefined
					thisType: undefined
					loc: Object {
						filename: "es2015/uncategorised/242/input.js"
						end: Object {
							column: 28
							index: 28
							line: 1
						}
						start: Object {
							column: 14
							index: 14
							line: 1
						}
					}
					params: Array [
						JSBindingAssignmentPattern {
							operator: "="
							loc: Object {
								filename: "es2015/uncategorised/242/input.js"
								end: Object {
									column: 24
									index: 24
									line: 1
								}
								start: Object {
									column: 15
									index: 15
									line: 1
								}
							}
							left: JSBindingIdentifier {
								name: "eval"
								loc: Object {
									filename: "es2015/uncategorised/242/input.js"
									identifierName: "eval"
									end: Object {
										column: 19
										index: 19
										line: 1
									}
									start: Object {
										column: 15
										index: 15
										line: 1
									}
								}
							}
							right: JSNumericLiteral {
								value: 10
								format: undefined
								loc: Object {
									filename: "es2015/uncategorised/242/input.js"
									end: Object {
										column: 24
										index: 24
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
		}
	]
}
```

### `diagnostics`

```

 es2015/uncategorised/242/input.js:1:15 parse/js ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

  ✖ eval is a reserved word

    "use strict"; (eval = 10) => 42
                   ^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```