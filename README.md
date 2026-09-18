# Gerador de Jogos — Loterias

Ferramenta simples em HTML/JS (sem backend) para gerar jogos de **Lotofácil**, **Mega-Sena**, **Quina** e **Dupla-Sena** a partir de dezenas escolhidas por você, com opção de:

- Definir quantas dezenas por jogo e quantos jogos gerar
- Buscar automaticamente as dezenas mais sorteadas nos últimos concursos (via API pública) e usá-las como base
- Evitar sequências de números consecutivos (fechamento)
- Imprimir em lista simples ou em formato "estilo volante" (guia de preenchimento)

## Como usar

Abra `index.html` no navegador — não precisa de instalação nem servidor.

Se estiver publicado via GitHub Pages, basta acessar o link do site.

## Fonte de dados das dezenas quentes

A busca de "dezenas mais sorteadas" usa uma API pública de terceiros
(loteriascaixa-api, não oficial da Caixa). Disponibilidade não é garantida —
se ela estiver fora do ar, a ferramenta mostra um aviso e você pode consultar
os resultados em loterias.caixa.gov.br.

## Aviso

Este gerador é uma ferramenta de apoio para organizar dezenas e fechamentos.
Os jogos impressos em "estilo volante" **não substituem** o volante oficial —
a aposta só é válida quando registrada em uma casa lotérica autorizada ou no
site/aplicativo oficial Loterias CAIXA.
