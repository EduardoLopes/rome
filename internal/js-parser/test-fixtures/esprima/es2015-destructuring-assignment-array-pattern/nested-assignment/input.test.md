# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-destructuring-assignment-array-pattern > nested-assignment`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
		end: Object {
			column: 0
			line: 2
		}
		start: Object {
			column: 0
			line: 1
		}
	}
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
				end: Object {
					column: 25
					line: 1
				}
				start: Object {
					column: 0
					line: 1
				}
			}
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
					end: Object {
						column: 24
						line: 1
					}
					start: Object {
						column: 0
						line: 1
					}
				}
				right: JSNumericLiteral {
					value: 0
					format: undefined
					loc: Object {
						filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
						end: Object {
							column: 24
							line: 1
						}
						start: Object {
							column: 23
							line: 1
						}
					}
				}
				left: JSAssignmentArrayPattern {
					rest: undefined
					loc: Object {
						filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
						end: Object {
							column: 22
							line: 1
						}
						start: Object {
							column: 0
							line: 1
						}
					}
					elements: Array [
						JSAssignmentIdentifier {
							name: "a"
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
								identifierName: "a"
								end: Object {
									column: 2
									line: 1
								}
								start: Object {
									column: 1
									line: 1
								}
							}
						}
						JSAssignmentAssignmentPattern {
							operator: "="
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
								end: Object {
									column: 6
									line: 1
								}
								start: Object {
									column: 3
									line: 1
								}
							}
							left: JSAssignmentIdentifier {
								name: "b"
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
									identifierName: "b"
									end: Object {
										column: 4
										line: 1
									}
									start: Object {
										column: 3
										line: 1
									}
								}
							}
							right: JSNumericLiteral {
								value: 0
								format: undefined
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
									end: Object {
										column: 6
										line: 1
									}
									start: Object {
										column: 5
										line: 1
									}
								}
							}
						}
						JSAssignmentAssignmentPattern {
							operator: "="
							loc: Object {
								filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
								end: Object {
									column: 21
									line: 1
								}
								start: Object {
									column: 7
									line: 1
								}
							}
							right: JSObjectExpression {
								properties: Array []
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
									end: Object {
										column: 21
										line: 1
									}
									start: Object {
										column: 19
										line: 1
									}
								}
							}
							left: JSAssignmentArrayPattern {
								loc: Object {
									filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
									end: Object {
										column: 18
										line: 1
									}
									start: Object {
										column: 7
										line: 1
									}
								}
								elements: Array [
									JSAssignmentIdentifier {
										name: "c"
										loc: Object {
											filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
											identifierName: "c"
											end: Object {
												column: 9
												line: 1
											}
											start: Object {
												column: 8
												line: 1
											}
										}
									}
								]
								rest: JSMemberExpression {
									loc: Object {
										filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
										end: Object {
											column: 17
											line: 1
										}
										start: Object {
											column: 13
											line: 1
										}
									}
									object: JSReferenceIdentifier {
										name: "a"
										loc: Object {
											filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
											identifierName: "a"
											end: Object {
												column: 14
												line: 1
											}
											start: Object {
												column: 13
												line: 1
											}
										}
									}
									property: JSComputedMemberProperty {
										value: JSNumericLiteral {
											value: 0
											format: undefined
											loc: Object {
												filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
												end: Object {
													column: 16
													line: 1
												}
												start: Object {
													column: 15
													line: 1
												}
											}
										}
										loc: Object {
											filename: "esprima/es2015-destructuring-assignment-array-pattern/nested-assignment/input.js"
											end: Object {
												column: 17
												line: 1
											}
											start: Object {
												column: 14
												line: 1
											}
										}
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
✔ No known problems!

```