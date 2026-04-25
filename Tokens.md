## Introduction

This document explains tokens in the context of Artificial Intelligence (AI).


## What are tokens?

Tokens are the chunks of text that are exchanged during every AI interaction. An AI model processes user inputs numerically. Depending on the tokenization rules, the model breaks each piece of text into tokens.

**Tokens Standards**: For English texts, 1 token = 0.75 words or 1 word = 1.3 tokens.

| **Note** |
--- |
| Different AI models follow different tokenization rules. |


## An Example

_The following is an illustrative example of how models break down words into tokens._

Statement: Betelguese is a dying star. 

Token break-down (illustrative):

| Text | Token |
--- | --- |
| Betel | Token 1 |
| guese | Token 2 |
| is | Token 3 |
| a | Token 4 |
| dying | Token 5 |
| star | Token 6 |

| Note |
--- |
Texts such as _Betelguese_ are often treated as two separate tokens.

## Why tokens matter?

Every AI model processes a limited number of tokens per interaction. The higher the number of tokens used and generated, the higher the usage cost and latency. Longer or irrelevant inputs may dilute the context or increase hallucinations. The key is to use relevant and concise tokens to generate the desired responses.
