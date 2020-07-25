# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test packages/@romefrontend/js-parser/index.test.ts --update-snapshots` to update.

## `esprima > es2015-object-initialiser > invalid-proto-getter-literal-identifier`

### `ast`

```javascript
JSRoot {
	comments: Array []
	corrupt: false
	directives: Array []
	filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
	hasHoistedVars: false
	interpreter: undefined
	mtime: undefined
	sourceType: "script"
	syntax: Array []
	loc: Object {
		filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
		end: Object {
			column: 0
			index: 59
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
			origins: Array [Object {category: "parse/js"}]
			description: Object {
				advice: Array []
				category: "parse/js"
				message: MARKUP {parts: Array [RAW_MARKUP {value: "Redefinition of __proto__ property"}]}
			}
			location: Object {
				filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
				mtime: undefined
				sourceText: undefined
				end: Object {
					column: 48
					index: 48
					line: 1
				}
				start: Object {
					column: 39
					index: 39
					line: 1
				}
			}
		}
	]
	body: Array [
		JSExpressionStatement {
			loc: Object {
				filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
				end: Object {
					column: 58
					index: 58
					line: 1
				}
				start: Object {
					column: 0
					index: 0
					line: 1
				}
			}
			expression: JSObjectExpression {
				loc: Object {
					filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
					end: Object {
						column: 57
						index: 57
						line: 1
					}
					start: Object {
						column: 1
						index: 1
						line: 1
					}
				}
				properties: Array [
					JSObjectMethod {
						kind: "get"
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "__proto"
								loc: Object {
									filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
									identifierName: "__proto"
									end: Object {
										column: 14
										index: 14
										line: 1
									}
									start: Object {
										column: 7
										index: 7
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
								end: Object {
									column: 14
									index: 14
									line: 1
								}
								start: Object {
									column: 7
									index: 7
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
							end: Object {
								column: 18
								index: 18
								line: 1
							}
							start: Object {
								column: 3
								index: 3
								line: 1
							}
						}
						body: JSBlockStatement {
							body: Array []
							directives: Array []
							loc: Object {
								filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
								end: Object {
									column: 18
									index: 18
									line: 1
								}
								start: Object {
									column: 16
									index: 16
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
								filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
								end: Object {
									column: 16
									index: 16
									line: 1
								}
								start: Object {
									column: 14
									index: 14
									line: 1
								}
							}
						}
					}
					JSObjectProperty {
						key: JSStaticPropertyKey {
							value: JSStringLiteral {
								value: "__proto__"
								loc: Object {
									filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
									end: Object {
										column: 31
										index: 31
										line: 1
									}
									start: Object {
										column: 20
										index: 20
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
								end: Object {
									column: 31
									index: 31
									line: 1
								}
								start: Object {
									column: 20
									index: 20
									line: 1
								}
							}
						}
						value: JSNullLiteral {
							loc: Object {
								filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
								end: Object {
									column: 37
									index: 37
									line: 1
								}
								start: Object {
									column: 33
									index: 33
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
							end: Object {
								column: 37
								index: 37
								line: 1
							}
							start: Object {
								column: 20
								index: 20
								line: 1
							}
						}
					}
					JSObjectProperty {
						key: JSStaticPropertyKey {
							value: JSIdentifier {
								name: "__proto__"
								loc: Object {
									filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
									identifierName: "__proto__"
									end: Object {
										column: 48
										index: 48
										line: 1
									}
									start: Object {
										column: 39
										index: 39
										line: 1
									}
								}
							}
							loc: Object {
								filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
								end: Object {
									column: 48
									index: 48
									line: 1
								}
								start: Object {
									column: 39
									index: 39
									line: 1
								}
							}
						}
						value: JSNullLiteral {
							loc: Object {
								filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
								end: Object {
									column: 54
									index: 54
									line: 1
								}
								start: Object {
									column: 50
									index: 50
									line: 1
								}
							}
						}
						loc: Object {
							filename: "esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js"
							end: Object {
								column: 54
								index: 54
								line: 1
							}
							start: Object {
								column: 39
								index: 39
								line: 1
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

 esprima/es2015-object-initialiser/invalid-proto-getter-literal-identifier/input.js:1:39 parse/js ━━

  ✖ Redefinition of __proto__ property

    ({ get __proto(){}, "__proto__": null, __proto__: null, })
                                           ^^^^^^^^^

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```