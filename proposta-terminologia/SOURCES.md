# Fontes lidas para TERMINOLOGIA_PROPOSTA.md

Claude (Claude Opus 5.5 at effort high), 19 de novembro de 2026. Toda fonte citada na proposta foi lida por script, página
a página (texto extraído do PDF, uma página por quebra de página), e cada citação dá a página em que o termo aparece.
Nenhuma proposta vem de memória.

## O que já está fixado

- `TERMINOLOGIA.md` no ramo `codex/pt-br-terminologia` de KokunoYumeto/OpenLogic-pt (vocabulário configurável, títulos,
  rótulos e as seis chaves em aberto), e `TITULOS_EN_PT.tsv` no mesmo ramo.
- A configuração de Pedro Lima: `open-logic-config.sty` em OpenLogicProject/OpenLogic-pt, main 51c2271
  (66 `\settexttoken`).
- Os arquivos traduzidos por Pedro Lima no mesmo main (os 250 arquivos com texto em português, os da tabela de proveniência) e as traduções
  por IA dos 19 ramos `codex/pt-br-*` de KokunoYumeto/OpenLogic-pt (442 arquivos).
- O texto inglês: OpenLogicProject/OpenLogic, commit 3aacf4af (722 arquivos de conteúdo; `open-logic-config.sty`
  com 76 `\settexttoken`).

## Literatura brasileira (acesso livre)

O corpus de literatura em disco (índice `Papors/Chatnotes/Zeta-Function-Foundation`, consultado com `query_corpus.py`
para “lógica matemática”, “lógica de primeira ordem”, “computabilidade”, “teoria dos conjuntos introdução” e
“decidibilidade”) não tem nenhum texto de lógica em português. As fontes abaixo foram baixadas dos sites das
universidades:

| Fonte | Páginas | URL |
|---|---|---|
| Arthur Buchsbaum, *Lógica Geral*, material didático (UFSC, Departamento de Informática e Estatística) | 67 | https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf |
| Apostila de Lógica Matemática da disciplina do CIn-UFPE (João Victor) | 70 | https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf |
| Jefferson Elder da Mota Nascimento, TCC sobre o cálculo de sequentes (UFPE, repositório Attena) | 32 | https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf |
| Hélder Paixão Felix Filho, trabalho de graduação sobre lógica modal (CIn-UFPE, 2018) | 42 | https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf |
| Hélder Paixão Felix Filho, dissertação de mestrado sobre lógica modal (UFPE, repositório Attena) | 131 | https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf |

Busca: cada forma candidata, sem acentos e sem distinguir maiúsculas, como palavra inteira; a primeira página em que
aparece em cada fonte é a citada.

## Wikipédia em português

- Busca por frase exata na API do MediaWiki (`pt.wikipedia.org/w/api.php`, `list=search`, a forma entre aspas): o
  título do primeiro artigo que contém a frase é o citado.
- O artigo inglês correspondente ao termo (`en.wikipedia.org`, busca “<termo> logic mathematics”) e o seu link para a
  Wikipédia em português (`prop=langlinks`): o título português entra como forma candidata.
- Um resultado da Wikipédia só é citado quando o título do artigo é a própria forma, ou quando o artigo que contém a
  frase é de lógica ou matemática (pelo título); os demais resultados da busca (artigos fora do assunto) foram descartados.
- O título português de um artigo inglês só entra como candidato quando o artigo inglês tem todas as palavras do termo.

## Arquivos de Pedro Lima citados

Onde a proposta cita um arquivo de Pedro Lima, a forma foi lida no main 51c2271 e a citação dá o número da linha
(`first-order-logic/syntax-and-semantics/free-vars-sentences.tex`, l. 15, para *livre / livres*).

## O que não foi usado

Nenhum livro sob direitos que não esteja em acesso livre, nenhum modelo pago e nenhuma tradução de memória.
