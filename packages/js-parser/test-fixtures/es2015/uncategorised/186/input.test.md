# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `es2015 > uncategorised > 186`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	diagnostics: Array []
	directives: Array []
	filename: "es2015/uncategorised/186/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "es2015/uncategorised/186/input.js"
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
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "es2015/uncategorised/186/input.js"
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
			expression: JSAssignmentExpression {
				operator: "="
				loc: Object {
					filename: "es2015/uncategorised/186/input.js"
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
				right: JSReferenceIdentifier {
					name: "d"
					loc: Object {
						filename: "es2015/uncategorised/186/input.js"
						identifierName: "d"
						end: Object {
							column: 20
							index: 20
							line: 1
						}
						start: Object {
							column: 19
							index: 19
							line: 1
						}
					}
				}
				left: JSAssignmentArrayPattern {
					loc: Object {
						filename: "es2015/uncategorised/186/input.js"
						end: Object {
							column: 16
							index: 16
							line: 1
						}
						start: Object {
							column: 0
							index: 0
							line: 1
						}
					}
					rest: JSAssignmentIdentifier {
						name: "c"
						loc: Object {
							filename: "es2015/uncategorised/186/input.js"
							identifierName: "c"
							end: Object {
								column: 15
								index: 15
								line: 1
							}
							start: Object {
								column: 14
								index: 14
								line: 1
							}
						}
					}
					elements: Array [
						JSAssignmentObjectPattern {
							rest: undefined
							loc: Object {
								filename: "es2015/uncategorised/186/input.js"
								end: Object {
									column: 9
									index: 9
									line: 1
								}
								start: Object {
									column: 1
									index: 1
									line: 1
								}
							}
							properties: Array [
								JSAssignmentObjectPatternProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "a"
											loc: Object {
												filename: "es2015/uncategorised/186/input.js"
												identifierName: "a"
												end: Object {
													column: 4
													index: 4
													line: 1
												}
												start: Object {
													column: 3
													index: 3
													line: 1
												}
											}
										}
										loc: Object {
											filename: "es2015/uncategorised/186/input.js"
											end: Object {
												column: 4
												index: 4
												line: 1
											}
											start: Object {
												column: 3
												index: 3
												line: 1
											}
										}
									}
									value: JSAssignmentIdentifier {
										name: "a"
										loc: Object {
											filename: "es2015/uncategorised/186/input.js"
											identifierName: "a"
											end: Object {
												column: 4
												index: 4
												line: 1
											}
											start: Object {
												column: 3
												index: 3
												line: 1
											}
										}
									}
									loc: Object {
										filename: "es2015/uncategorised/186/input.js"
										end: Object {
											column: 4
											index: 4
											line: 1
										}
										start: Object {
											column: 3
											index: 3
											line: 1
										}
									}
								}
								JSAssignmentObjectPatternProperty {
									key: JSStaticPropertyKey {
										value: JSIdentifier {
											name: "b"
											loc: Object {
												filename: "es2015/uncategorised/186/input.js"
												identifierName: "b"
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
											filename: "es2015/uncategorised/186/input.js"
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
									value: JSAssignmentIdentifier {
										name: "b"
										loc: Object {
											filename: "es2015/uncategorised/186/input.js"
											identifierName: "b"
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
										filename: "es2015/uncategorised/186/input.js"
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
							]
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