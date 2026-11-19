# Terminologia: proposta para os termos ainda não fixados

**O que é.** Uma proposta de termo em português brasileiro para cada termo técnico do Open Logic Project que o
[TERMINOLOGIA.md](https://github.com/KokunoYumeto/OpenLogic-pt/blob/codex/pt-br-terminologia/TERMINOLOGIA.md) ainda não
fixa: as seis chaves de vocabulário deixadas em aberto e os termos definidos (os termos em itálico dentro dos ambientes
de definição) cuja tradução falta ou varia entre os seus arquivos, Pedro, e as traduções por IA dos 19 ramos por parte.
Cada linha é só uma sugestão, para aceitar (marque ☐ → ☑) ou substituir. Nada foi alterado nos seus arquivos nem nos
pull requests.

**Como foi feita.** Por Claude (Claude Opus 5.5 at effort high), um modelo de IA da Anthropic, em 19 de novembro de
2026, sem chamadas pagas a modelos. Um script inventariou os termos do texto inglês (upstream 3aacf4af: 722 arquivos,
os itálicos das definições e as chaves `!!{…}`) e alinhou cada ocorrência com a mesma definição nos seus arquivos (main
51c2271: os 250 arquivos com texto em português, os mesmos da sua tabela de proveniência) e nos ramos `codex/pt-br-*` (442 arquivos). A lista completa, com contagens
e formas atuais, está em `INVENTORY.tsv`; as fontes lidas, em `SOURCES.md`.

**Regra da proposta, em ordem.**
1. Onde você já tem uma forma nos seus arquivos, ela é a proposta (a mais frequente), e as outras formas vão para
   *Alternativas*. As suas escolhas indicam um padrão que a proposta segue também nos termos novos: advérbio em
   *-mente* sobre o adjetivo português (*maximamente consistente*, não *maximalmente*), variável como prefixo com hífen
   (*$x$-variante*), e as chaves de vocabulário da sua configuração (*sentença*, *derivação*, *fórmula*) dentro dos
   compostos.
2. Sem forma sua: a tradução dos ramos que aparece na literatura brasileira lida (apostilas, TCC, dissertação e livro
   de UFSC e UFPE, com página), e depois a que aparece na Wikipédia em português.
3. Sem fonte: a tradução dos ramos, marcada *decidir*.

Uma citação da literatura mostra que a forma aparece naquela página; o sentido ali não foi conferido linha a linha
(por exemplo, *aberto* pode estar em *fórmula aberta* ou em *conjunto aberto*), então vale olhar a página antes de
marcar. As formas são do português brasileiro; as formas europeias não foram comparadas. A coluna *Onde aparece* dá as partes do livro e o número de arquivos ingleses
que definem o termo.


## Chaves de vocabulário sem entrada na configuração brasileira

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | height | **altura / alturas** | — | — | 48 ocorrências | altura de uma derivação; o ramo de teoria da prova já escreve “preservação de !!{height}”; sem ocorrência na literatura lida: decidir |
| ☐ | elimination | **eliminação / eliminações** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 36](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 13](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | 29 ocorrências | “regras de eliminação” na literatura lida; a chave inglesa tem o mesmo plural (elimination) |
| ☐ | introduction | **introdução / introduções** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 36](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 30](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf); [Buchsbaum, *Lógica Geral* (UFSC), p. 44](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf) | 24 ocorrências | “regras de introdução” na literatura lida |
| ☐ | hp | **pa** | hp (sigla inglesa mantida); por extenso: “com preservação de altura” | — | 2 ocorrências | sigla de *height-preserving*; nenhuma fonte brasileira lida usa uma sigla: decisão de Pedro (sigla nova, sigla inglesa ou forma por extenso) |
| ☐ | depth | **profundidade / profundidades** | grau (de uma fórmula) | [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 28](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | 1 ocorrência | feminino (a profundidade); “profundidade lógica” no TCC citado, no mesmo uso (complexidade de fórmulas na eliminação do corte) |
| ☐ | sentences | **sentenças** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 9](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | 1 ocorrência | segue a entrada de Pedro *sentence* = sentença / sentenças; a configuração inglesa não define a chave *sentences* (só *sentence*), então a ocorrência é provavelmente um erro da fonte inglesa |

## Conjuntos, relações e funções

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | preserved under | **preservada por** | — | — | Conjuntos, relações e funções; 1 arquivo | sem fonte encontrada: decidir |

## Lógica de primeira ordem

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | derivable from | **derivável de** | derivável a partir de; derivável de $\Sigma$ | — | Lógica de primeira ordem, Lógicas multivaloradas, Lógica modal normal; 6 arquivos | escolha de Pedro Lima nos seus arquivos |
| ☐ | entails | **consequência** | acarreta; implica | [Buchsbaum, *Lógica Geral* (UFSC), p. 9](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 12](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica de primeira ordem, Lógica intuicionista, Lógica modal normal, Lógica de segunda ordem; 4 arquivos | escolha de Pedro Lima nos seus arquivos |
| ☐ | axioms | **axiomas** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 8](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 45](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica de primeira ordem, Lógica intuicionista; 3 arquivos | atestado na literatura brasileira lida |
| ☐ | maximally consistent | **maximamente consistente** | maximalmente consistente | — | Lógica de primeira ordem, Lógica proposicional; 2 arquivos | escolha de Pedro Lima nos seus arquivos |
| ☐ | free | **livre / livres** | — | [Pedro Lima, syntax-and-semantics/free-vars-sentences.tex, l. 15](https://github.com/OpenLogicProject/OpenLogic-pt/blob/51c227190f56bae45d19a85747fc031de430bd3c/content/first-order-logic/syntax-and-semantics/free-vars-sentences.tex#L15) | Lógica de primeira ordem, Cálculo lambda; 2 arquivos | escolha de Pedro Lima nos seus arquivos (ele escreve o plural, *ocorrências livres*; o ramo traz o singular da mesma palavra) |
| ☐ | -variant | **$x$-variante** | variante em $x$ | — | Lógica de primeira ordem, Lógica de segunda ordem; 2 arquivos | escolha de Pedro Lima nos seus arquivos |
| ☐ | rule of inference | **regra de inferência** | — | [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 15](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Lógica de primeira ordem; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | open | **aberto** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 31](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 59](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica de primeira ordem; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | closed tableau | **tableau fechado** | — | [Wikipédia: Método dos Tableaux](https://pt.wikipedia.org/wiki/Método_dos_Tableaux) | Lógica de primeira ordem; 1 arquivo | atestado na Wikipédia em português |

## Lógica proposicional

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | contingent | **contingente** | — | [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 13](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf) | Lógica proposicional; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | satisfaction of formula~ by valuation~ | **satisfação de fórmula $!A$ por valoração $\pAssign{v}$** | — | — | Lógica proposicional; 1 arquivo | sem fonte encontrada: decidir |

## Teoria dos modelos

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | normal | **normal** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 26](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 4](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria dos modelos, Lógica modal normal; 3 arquivos | atestado na literatura brasileira lida |
| ☐ | standard | **padrão** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 7](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 71](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria dos modelos; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | -equivalent | **$R$-equivalentes** | $n$-equivalentes | — | Teoria dos modelos, Conjuntos, relações e funções; 2 arquivos | escolha de Pedro Lima nos seus arquivos |
| ☐ | dense linear ordering without endpoints | **ordem linear densa sem extremos** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | elementarily equivalent to | **elementarmente equivalente a** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | isomorphic to | **isomorfa a** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | automorphism | **automorfismo** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | standard model | **modelo padrão** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | partial isomorphism | **isomorfismo parcial** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | partially isomorphic | **parcialmente isomorfas** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | back-and-forth | **ida e volta** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | forth | **ida** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | back | **volta** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 122](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf); [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 16](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf) | Teoria dos modelos; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | quantifier rank | **posto de quantificadores** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | concatenation | **concatenação** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 6](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf) | Teoria dos modelos; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | reduct | **reduto** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 57](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria dos modelos; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | expansion | **expansão** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 5](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 14](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Teoria dos modelos; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | substructure | **subestrutura** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | extension | **extensão** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 42](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 4](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria dos modelos; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | explicitly defines | **define explicitamente** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | implicitly defines | **define implicitamente** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | separates | **separa** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 45](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria dos modelos; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | inseparable | **inseparáveis** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | abstract logic | **lógica abstrata** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | elementarily equivalent in | **elementarmente equivalentes em** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | -monotonicity | **monotonicidade de $L$** | — | [Wikipédia: Lógica clássica](https://pt.wikipedia.org/wiki/Lógica_clássica) | Teoria dos modelos; 1 arquivo | atestado na Wikipédia em português |
| ☐ | expansion property | **propriedade da expansão** | — | [Wikipédia: Função característica (probabilidade)](https://pt.wikipedia.org/wiki/Função_característica_(probabilidade)) | Teoria dos modelos; 1 arquivo | atestado na Wikipédia em português |
| ☐ | isomorphism property | **propriedade do isomorfismo** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | renaming property | **propriedade da renomeação** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | boolean property | **propriedade booleana** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | quantifier property | **propriedade dos quantificadores** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | relativization property | **propriedade da relativização** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | relativization | **relativização** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | at least as expressive | **ao menos tão expressiva** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | equivalent | **equivalentes** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 12](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 27](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria dos modelos; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | compactness property | **propriedade da compacidade** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | downward l\"owenheim--skolem property | **propriedade descendente de L\"owenheim--Skolem** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | non-standard | **não padrão** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | standard numbers | **números padrão** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | non-standard numbers | **números não padrão** | — | — | Teoria dos modelos; 1 arquivo | sem fonte encontrada: decidir |

## Computabilidade

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | regular | **regular** | regulares | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 14](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Computabilidade, Teoria da prova; 3 arquivos | atestado na literatura brasileira lida |
| ☐ | computable | **computável** | — | [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 41](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf) | Computabilidade, Teoria dos modelos; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | complete computably enumerable set | **conjunto computavelmente enumerável completo** | — | — | Computabilidade; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | many-one reduction | **redução muitos-para-um** | — | — | Computabilidade; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | many-one reducible | **redutível muitos-para-um** | — | — | Computabilidade; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | many-one equivalent | **equivalentes muitos-para-um** | — | — | Computabilidade; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | general recursive functions | **funções recursivas gerais** | — | [Wikipédia: Jacques Herbrand](https://pt.wikipedia.org/wiki/Jacques_Herbrand) | Computabilidade; 1 arquivo | atestado na Wikipédia em português |
| ☐ | partial recursive functions | **funções recursivas parciais** | — | — | Computabilidade; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | recursive functions | **funções recursivas** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 3](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 115](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Computabilidade; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | primitive recursion from and | **recursão primitiva a partir de $f$ e $g$** | — | — | Computabilidade; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | composition from and , ,~ | **composição a partir de $f$ e de $g_0$, , $g_{k-1}$** | — | — | Computabilidade; 1 arquivo | sem fonte encontrada: decidir |

## Incompletude

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | definable | **definível** | — | — | Incompletude, Lógica de segunda ordem; 2 arquivos | sem fonte encontrada: decidir |
| ☐ | theory | **teoria** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 6](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 19](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Incompletude, Teoria dos modelos; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | true arithmetic | **aritmética verdadeira** | — | — | Incompletude, Teoria dos modelos; 2 arquivos | sem fonte encontrada: decidir |
| ☐ | symbol code | **código do símbolo** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | g\"odel number | **número de G\"odel** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | -consistent | **$\omega$-consistente** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | standard model of arithmetic | **modelo padrão da aritmética** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | induction schema | **esquema de indução** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | peano arithmetic | **aritmética de Peano** | — | [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 18](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf) | Incompletude; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | relatively prime | **primos entre si** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | congruent modulo~ | **congruentes módulo $c$** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | bounded existential formula | **fórmula existencial limitada** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | bounded universal formula | **fórmula universal limitada** | — | — | Incompletude; 1 arquivo | sem fonte encontrada: decidir |

## Lógica de segunda ordem

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | -codes | **$x$ $R$-codifica** | — | — | Lógica de segunda ordem; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | second-order terms | **termos de segunda ordem** | — | [Wikipédia: Lógica de segunda ordem](https://pt.wikipedia.org/wiki/Lógica_de_segunda_ordem) | Lógica de segunda ordem; 1 arquivo | atestado na Wikipédia em português |
| ☐ | second-order formulas | **fórmulas de segunda ordem** | — | — | Lógica de segunda ordem; 1 arquivo | sem fonte encontrada: decidir |

## Cálculo lambda

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | -complete development | **desenvolvimento $\beta\eta$-completo** | desenvolvimento $\beta$-completo | — | Cálculo lambda; 2 arquivos | sem fonte encontrada: decidir |
| ☐ | church numeral | **numeral de Church** | — | — | Cálculo lambda; 2 arquivos | sem fonte encontrada: decidir |
| ☐ | -reduction | **redução $\beta$** | redução $\beta\eta$ | [Buchsbaum, *Lógica Geral* (UFSC), p. 14](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 41](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Cálculo lambda; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | free variables | **variáveis livres** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 32](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 5](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Cálculo lambda; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | substitution | **substituição** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 2](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 5](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Cálculo lambda; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | church--rosser property | **propriedade de Church--Rosser** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | parallel -reduction | **$\beta\eta$-redução paralela** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | y-combinator | **combinador Y** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | change of bound variable | **mudança de variável ligada** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | compatible | **compatível** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | -conversion | **conversão $\alpha$** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | the -contraction | **contração $\beta$** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 45](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 16](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Cálculo lambda; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | -contracted | **contraído por $\beta$** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | redex | **redex** | — | [Wikipédia: Reescrita de grafos](https://pt.wikipedia.org/wiki/Reescrita_de_grafos) | Cálculo lambda; 1 arquivo | atestado na Wikipédia em português |
| ☐ | -normal | **normal por $\beta$** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | -equivalence | **equivalência $\beta$** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 2](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 27](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Cálculo lambda; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | -contraction | **contração $\eta$** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 45](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 16](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Cálculo lambda; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | combinator | **combinador** | — | — | Cálculo lambda; 1 arquivo | sem fonte encontrada: decidir |

## Lógicas multivaloradas

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | tautology | **tautologia** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 29](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 15](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf); [Wikipédia: Tautologia](https://pt.wikipedia.org/wiki/Tautologia) | Lógicas multivaloradas, Lógica proposicional; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | -sided sequent | **sequente de $n$ lados** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | -sided initial sequent | **sequente inicial de $n$ lados** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | propositional language | **linguagem proposicional** | — | [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 14](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Lógicas multivaloradas; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | connectives | **conectivos** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 3](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 4](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógicas multivaloradas; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | arity | **aridade** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 11](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 18](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógicas multivaloradas; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | -place | **$n$-ário** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | constants | **constantes** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 6](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 17](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógicas multivaloradas; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | unary | **unários** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 25](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógicas multivaloradas; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | binary | **binários** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 25](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf); [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 28](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Lógicas multivaloradas; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | matrix | **matriz** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 70](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógicas multivaloradas; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | satisfied | **satisfeita** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 56](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógicas multivaloradas; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | -valued g\"odel logic | **lógica $3$-valorada de G\"odel** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | strong kleene logic | **lógica forte de Kleene** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | weak kleene logic | **lógica fraca de Kleene** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | logic of paradox | **lógica do paradoxo** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | logic of nonsense | **lógica do absurdo** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | 3-valued r-mingle | **R-Mingle trivalorada** | — | — | Lógicas multivaloradas; 1 arquivo | sem fonte encontrada: decidir |

## Lógica modal normal

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | modus ponens | **modus ponens** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 2](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 21](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Lógica modal normal; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | necessitation | **necessitação** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 63](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf); [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 34](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf); [Wikipédia: Lógica modal normal](https://pt.wikipedia.org/wiki/Lógica_modal_normal) | Lógica modal normal; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | modal logic | **lógica modal** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 3](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf); [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 1](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf); [Wikipédia: Lógica modal](https://pt.wikipedia.org/wiki/Lógica_modal) | Lógica modal normal; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | dual | **dual** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 21](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 129](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | follows from | **segue de** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 77](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | modal system | **sistema modal** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 15](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf); [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 18](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | deductively closed | **dedutivamente fechado** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | complete -consistent | **$\Sigma$-consistente completo** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | determines | **determina** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 53](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | finite model property | **propriedade do modelo finito** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | finest | **mais fina** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | coarsest | **mais grossa** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | both | **ambas** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 12](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 11](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | filtration of through | **filtração de $\mModel{M}$ por $\Gamma$** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | closed under subformulas | **fechado sob subfórmulas** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 122](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | modally closed | **modalmente fechado** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | defines | **define** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 9](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 30](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | universal | **universal** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 27](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 9](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | first-order definable | **definível em primeira ordem** | — | [Wikipédia: Semânticas de Kripke](https://pt.wikipedia.org/wiki/Semânticas_de_Kripke) | Lógica modal normal; 1 arquivo | atestado na Wikipédia em português |
| ☐ | frame | **frame** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 10](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf); [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 28](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | based on | **baseado em** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 12](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | valid in | **válida em $\mModel{F}$** | válida em $\mClass{F}$ | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | standard translation | **tradução padrão** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | second-order definable | **definível em segunda ordem** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | all | **todos** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 2](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 12](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | accessible from | **acessível a partir de** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 37](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf); [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 28](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | schema | **esquema** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 10](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 38](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | characteristic | **característica** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 18](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 20](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | instance | **instância** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 29](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 25](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | true | **verdadeiro** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 4](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 10](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica modal normal; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | substitution instance | **instância de substituição** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | tautological instance | **instância tautológica** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | true in a model | **verdadeira em um modelo** | — | — | Lógica modal normal; 1 arquivo | sem fonte encontrada: decidir |

## Lógica modal aplicada

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | truth of formula~ at~ | **verdade de fórmula $!A$ em $w$** | verdade de fórmula $!A$ em $t$; verdade de fórmula $!A$ em $t, \sigma$ | — | Lógica modal aplicada, Lógica modal normal; 6 arquivos | sem fonte encontrada: decidir |
| ☐ | true at | **verdadeira em** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 16](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf) | Lógica modal aplicada, Lógica modal normal; 4 arquivos | atestado na literatura brasileira lida |
| ☐ | model | **modelo** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 5](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 10](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica modal aplicada, Lógica modal normal; 3 arquivos | atestado na literatura brasileira lida |
| ☐ | bisimulation | **bissimulação** | — | [Felix Filho, dissertação sobre lógica modal (UFPE), p. 110](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica modal aplicada; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | bisimilar | **bissimilares** | — | — | Lógica modal aplicada; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | accessible by a from | **acessível a partir de $w$ para o agente a** | — | — | Lógica modal aplicada; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | possible histories model | **modelo de histórias possíveis** | — | — | Lógica modal aplicada; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | possible histories | **histórias possíveis** | — | — | Lógica modal aplicada; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | precedes | **precede** | — | — | Lógica modal aplicada; 1 arquivo | sem fonte encontrada: decidir |

## Lógica intuicionista

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | canonical model | **modelo canônico** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 5](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Felix Filho, TG sobre lógica modal (CIn-UFPE, 2018), p. 12](https://www.cin.ufpe.br/~tg/2018-1/hpff-tg.pdf) | Lógica intuicionista, Lógica modal normal; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | interpretation of | **interpretação de** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 54](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 34](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Lógica intuicionista, Lógica modal normal; 2 arquivos | atestado na literatura brasileira lida |
| ☐ | being true at in | **ser verdadeira em $w$ em $\mModel{M}$** | — | — | Lógica intuicionista; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | true in the model | **verdadeira no modelo $\mModel{M} = \tuple{W,R,V}$** | — | — | Lógica intuicionista; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | topology on~ | **topologia sobre $X$** | — | [Wikipédia: Análise funcional](https://pt.wikipedia.org/wiki/Análise_funcional) | Lógica intuicionista; 1 arquivo | atestado na Wikipédia em português |
| ☐ | open sets | **conjuntos abertos** | — | [Wikipédia: Espaço topológico](https://pt.wikipedia.org/wiki/Espaço_topológico) | Lógica intuicionista; 1 arquivo | atestado na Wikipédia em português |
| ☐ | topological space | **espaço topológico** | — | [Wikipédia: Espaço topológico](https://pt.wikipedia.org/wiki/Espaço_topológico) | Lógica intuicionista; 1 arquivo | atestado na Wikipédia em português |
| ☐ | topological model | **modelo topológico** | — | — | Lógica intuicionista; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | interior | **interior** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 7](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf) | Lógica intuicionista; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | prime | **primo** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 39](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 80](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Lógica intuicionista; 1 arquivo | atestado na literatura brasileira lida |

## Contrafactuais

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | sphere model | **modelo de esferas** | — | — | Contrafactuais; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | system of spheres | **sistema de esferas** | — | — | Contrafactuais; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | centered | **centrado** | — | — | Contrafactuais; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | nested | **aninhado** | — | — | Contrafactuais; 1 arquivo | sem fonte encontrada: decidir |

## Teoria da prova

| ✓ | Inglês | Proposta | Alternativas | Fontes | Onde aparece | Nota |
|---|---|---|---|---|---|---|
| ☐ | cut rank | **posto de corte** | — | — | Teoria da prova; 2 arquivos | sem fonte encontrada: decidir |
| ☐ | cut height | **altura de corte** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | open assumptions | **hipóteses abertas** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | segment | **segmento** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | length | **comprimento** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | rank | **posto** | — | [Apostila de Lógica Matemática (CIn-UFPE), p. 21](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria da prova; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | maximal | **máximo** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 38](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 22](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria da prova; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | cut length | **comprimento de corte** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | context | **contexto** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 4](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Felix Filho, dissertação sobre lógica modal (UFPE), p. 6](https://attena.ufpe.br/bitstream/123456789/45914/1/DISSERTA%c3%87%c3%83O%20H%c3%a9lder%20Paix%c3%a3o%20Felix%20Filho.pdf) | Teoria da prova; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | type | **tipo** | — | [Buchsbaum, *Lógica Geral* (UFSC), p. 6](https://www.inf.ufsc.br/~arthur.buchsbaum/material_didatico/LogicaGeral.pdf); [Apostila de Lógica Matemática (CIn-UFPE), p. 10](https://www.cin.ufpe.br/~mlogica/livros/Apostila_joao_victor.pdf) | Teoria da prova; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | admissible | **admissível** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | height-preserving admissible | **admissível com preservação de altura** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | hp-admissible | **hp-admissível** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | invertible | **invertível** | — | [Nascimento, TCC sobre o cálculo de sequentes (UFPE, 2023), p. 29](https://attena.ufpe.br/bitstream/123456789/53197/1/TCC%20Jefferson%20Elder%20da%20Mota%20Nascimento.pdf) | Teoria da prova; 1 arquivo | atestado na literatura brasileira lida |
| ☐ | height-preserving invertible | **invertível com preservação de altura** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
| ☐ | hp-invertible | **hp-invertível** | — | — | Teoria da prova; 1 arquivo | sem fonte encontrada: decidir |
