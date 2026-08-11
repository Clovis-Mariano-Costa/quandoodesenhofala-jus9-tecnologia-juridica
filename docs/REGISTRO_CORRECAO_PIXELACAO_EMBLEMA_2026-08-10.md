# Correção de pixelização — Emblema da Universidade do Futuro

**Data:** 10/08/2026
**Página:** `/universidade-do-futuro`
**Estado:** CORRIGIDO E PUBLICADO

## Causa

A página interpretativa carregava `logo-universidade-do-futuro-oficial.svg` a partir do site da Universidade do Futuro. A resposta visual efetiva tinha 256 × 256 px, causando pixelização quando exibida em área ampliada.

## Correção

A página passou a carregar localmente a matriz PNG preservada:

`assets/images/emblema-universidade-do-futuro-1254.png`

- Dimensões: 1254 × 1254 px.
- SHA-256: `44D4812A8B6FED95C834310CEC3E19CDC0CE67AD6D72AE2954F3C2F806C41031`.
- Atributos de carregamento: largura e altura explícitas, `loading="eager"` e `decoding="async"`.

## Limites

O arquivo é identidade visual simbólico-institucional interna da Universidade do Futuro. A correção de resolução não cria reconhecimento estatal, credenciamento educacional externo, diploma, título ou habilitação profissional.
