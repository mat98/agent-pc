---
name: tradutor-erros
description: Explica uma mensagem de erro em português simples e diz como resolver.
argument-hint: [mensagem de erro]
disable-model-invocation: true
context: fork
agent: tradutor-erros
background: false
---

Explique o erro abaixo e diga como resolver. Se nenhum erro foi informado, peça para o usuário colar a mensagem ou mandar um print.

Erro informado pelo usuário: $ARGUMENTS
