---
name: compactar
description: Resume a conversa inteira para continuar num chat novo. Use quando o usuário escrever "COMPACTAR" (ou /compactar), ou pedir para resumir a conversa para trocar de chat.
---

# COMPACTAR

Quando o usuário escrever **COMPACTAR**, resuma a conversa inteira em um bloco pronto para copiar e colar num chat novo.

## Formato

Responda só com um bloco de código markdown (para facilitar copiar), contendo:

1. **Objetivo** — uma linha com o que estamos fazendo.
2. **5 a 7 pontos** com o contexto crítico:
   - decisões tomadas (e o porquê, em poucas palavras);
   - estado atual: o que já foi feito e o que falta;
   - arquivos, comandos, caminhos e nomes exatos que importam;
   - trechos de código essenciais (curtos, só o que for necessário para continuar);
   - pendências, bugs abertos e próximos passos.
3. **Próxima ação** — uma linha dizendo por onde o novo chat deve começar.

## Regras

- Nada de cumprimentos ou explicações fora do bloco.
- Não invente: inclua só o que realmente aconteceu na conversa.
- Nunca inclua senhas, chaves de API, tokens ou outros segredos — escreva `[segredo omitido]`.
- Prefira nomes e valores exatos a descrições vagas.
