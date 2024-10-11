---
title: Passphrase Generator Documentation
sidebar_label: Passphrase Generator
sidebar_position: 12
hide_title: true
keywords: [inventor.gg, redocs, documentation, Passphrase]
description: Generate a random combination of up to 20 randomly selected words with a specified separator.
---
# Passphrase Generator
Generate a random combination of up to 20 randomly selected words with a specified separator.

## Inputs

- [Number of Words](#number-of-words-input)
- [Separator](#separator-input)

### Number of Words {#number-of-words-input}
The total number of words you would like the passphrase to have. 20 words maximum, and it is inputted as a [number](/inventor-reference/types/number). E.g. `16`
### Separator {#separator-input}
A separator that will go between every word, inputted as a [string](/inventor-reference/types/string). E.g. `, `

## Outputs
- [Passphrase](#passphrase-output)
- [Error](#error-output)

### Passphrase {#passphrase-output}
The unique passphrase that was generated, expressed as a [string](/inventor-reference/types/string). E.g. `recite, shakiness, monthly, deity, nullify, retail, collide, slush, posted, grief, drapery, linoleum, botanist, regress, modified, faculty`

### Error {#error-output}
The Inventor Error ID of an error. You can lookup an error by its ID with the [Get Error Details](/inventor-reference/blocks/utilities/get-error-details) block. E.g. `DoVpjqYs`