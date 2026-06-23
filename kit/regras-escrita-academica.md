# regras-escrita-academica.md

Regras para usar o Claude em escrita acadêmica sem produzir o que parece ciência e
não é. Anexe na conversa em que você escreve um texto com literatura, ou adicione
ao conhecimento de um Projeto de pesquisa, para a regra estar sempre à mão.

A regra de fundo: a IA executa a leitura e o cruzamento dentro do que você
autorizou, e quem responde pelo texto é você. Se um dado sai trocado num material
com seu nome, o erro é seu.

---

## Referência não se inventa

O Claude nunca deve apresentar referência, DOI, autor, ano, periódico ou tamanho
de efeito que ele não tenha como confirmar. Sem certeza, a resposta correta é "não
consta na fonte", não um chute plausível. O perigo é a referência fantasma:
sobrenome crível, periódico crível, DOI que não resolve. Tem a mesma cara de um
acerto e passa numa leitura apressada.

## Conferir cada DOI (leva trinta segundos)

1. Resolva o DOI: abra `https://doi.org/<o-DOI>`. Tem que cair no artigo, não numa
   página de erro.
2. Confira os metadados contra a fonte canônica
   (`https://api.crossref.org/works/<o-DOI>`): título, primeiro autor, ano, periódico.
3. Confirme o conteúdo: a fonte precisa dizer o que você afirmou, não só existir.

Classifique cada citação em três:
- SUSTENTADA: resolve, os metadados batem, e a fonte diz aquilo.
- NÃO SUSTENTADA: a fonte existe, mas não afirma o que você disse.
- NÃO RESOLVÍVEL: o DOI não abre ou o autor não bate.

Só a primeira classe entra no texto. Vale igual para a referência que o Claude
trouxe da busca na web: ligar a busca reduz a invenção, mas não dispensa a
conferência.

## Hierarquia de evidência

Quando houver mais de uma fonte para o mesmo ponto, cite a mais forte: meta-análise,
depois revisão sistemática, depois ensaio randomizado, depois estudo observacional,
e assim por diante até opinião de especialista e livro didático. Se citar fonte
fraca, justifique.

## Calibração: o verbo casa com o dado

- "Sugere" ou "há evidência preliminar" para indício fraco ou estudo isolado.
- "Indica" para evidência moderada.
- "Demonstra" ou "está bem estabelecido" só para coisa replicada, com meta-análise
  ou replicações independentes.

Um estudo só, mesmo com muitos autores, continua sendo um estudo só. Não escreva
"estudos mostram" a partir de um.

## Detalhes que não podem sair errados

- N amostral, tipo de estudo e tamanho de efeito corretos, ou "não consta".
- Diferencie peer-reviewed de preprint sempre.
- Amostra WEIRD (ocidental, escolarizada, industrializada, rica, democrática):
  sinalize quando o ponto depender de generalizar para outras populações.

## Citação no seu formato

Peça as referências na norma que você usa (por exemplo APA 7) e confira a
formatação contra o manual. O Claude erra detalhe de formatação com confiança.

## Declarar o uso de IA

As normas brasileiras passaram a exigir que você declare onde a IA entrou no
trabalho, da concepção à submissão (CNPq, Portaria 2.664/2026; orientações da
CAPES alinhadas). Confira a versão vigente na sua instituição e registre o uso.
Supervisão humana e uso declarado deixaram de ser recomendação e viraram norma.
