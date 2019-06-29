---
title: ConfigAware.valueOrNull - detekt-api
---

[detekt-api](../../index.html) / [io.gitlab.arturbosch.detekt.api](../index.html) / [ConfigAware](index.html) / [valueOrNull](./value-or-null.html)

# valueOrNull

`open fun <T : `[`Any`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-any/index.html)`> valueOrNull(key: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`T`](value-or-null.html#T)`?`

Overrides [Config.valueOrNull](../-config/value-or-null.html)

Retrieves a sub configuration or value based on given key.
If the configuration property cannot be found, null is returned.
