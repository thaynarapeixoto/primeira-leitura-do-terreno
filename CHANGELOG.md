# Changelog

Todas as mudanças relevantes deste repositório.

## [0.5] · 30/07/2026

### As oito dimensões passam a seguir as dez etapas

Até a 0.4, cada dimensão tinha três blocos, e o terceiro variava entre "como registrar", "próxima validação" e "limite". O protocolo editorial do projeto exige dez etapas fixas, na mesma ordem, e a repetição é o que torna o método consultável. **Sete das dez etapas faltavam.**

Agora as oito dimensões trazem, todas, na mesma ordem: o que investigar · por que interfere na decisão · documentos e informações · fontes · perguntas de investigação · como a IA pode apoiar e onde ela para · validação obrigatória · sinais de alerta · como registrar · resultado esperado.

O que isso mudou na prática:

- **documentos passam a ser nomeados.** Certidão de ônus reais, certidão de ações reipersecutórias, ART ou RRT de levantamento, cadeia dominial, viabilidade técnica de concessionária, manifestação do órgão ambiental, certidão de uso do solo;
- **cada dimensão ganhou perguntas de investigação**, redigidas para serem feitas com essas palavras;
- **a IA passa a ter limite declarado dentro de cada dimensão**, e não apenas em um capítulo geral. Leitura de imagem de satélite por IA é sempre I de origem `IA`; a IA não declara existência nem inexistência de restrição ambiental;
- **a validação obrigatória diz quem assina**, dimensão por dimensão;
- nota sobre potencial construtivo onerado, e a advertência de que as faixas de APP estão no art. 4º da Lei 12.651/2012 e devem ser lidas no dispositivo, nunca de memória;
- o modo gleba passa a aparecer dentro das dimensões 4, 6 e 7, no mesmo lugar em cada leitura.

### Atribuição

- **Blocos "De onde vem" no ponto de uso**, nomeando Flávio Villaça, Jane Jacobs, Jan Gehl, Kevin Lynch e Philippe Panerai, e a legislação federal que incide em cada dimensão.
- **Nova seção "Referências e atribuição"**, com as obras completas, a tabela de dez normas federais por dimensão, e a declaração explícita do que é construção deste projeto.
- **Declaração de interesse** no README e no guia.
- `LICENSE` com o código legal da CC BY-NC 4.0.

## [0.4] · 30/07/2026

Primeira versão sob o projeto **Contexto Primeiro**. Reescrita a partir do material anterior, que circulava como *Do Lote à Cidade, Starter Kit*.

### Método

- **Protocolo C / I / P reescrito.** `I` passa a significar indício ou inferência, e não mais "informado por terceiro". A procedência saiu do status e virou um campo próprio, `origem`, com cinco valores. Informação de terceiro passa a carregar o peso de prova que tem, que é zero.
- **Cinco regras de acoplamento**, entre elas a de que origem `terceiro` ou `IA` tem status máximo `I`.
- **Todo P passa a carregar três campos obrigatórios:** por que importa, quem valida, qual decisão depende dele.
- **Campo em branco é P, nunca N/A.**
- **Nível de confiança passa a ter critério.** Três níveis por regra, com a regra dura de que confiança baixa não autoriza prosseguir.
- **Espinha de oito dimensões**, com ambiente separado de infraestrutura, acessos e mobilidade dentro de infraestrutura, e mercado, riscos e encaminhamento reunidos na oitava.
- **Três dimensões críticas declaradas:** 2, 4 e 5.
- **Estados de saída revistos**, cinco sobre o terreno mais *insuficiente*, que é sobre o material recebido.
- **Gleba deixa de ser escala e vira modo.** Cinco escalas fixas mais o modo gleba, acionado quando o imóvel não é lote urbano consolidado.

### Fronteira

- Saíram deste repositório a matriz de risco completa, com probabilidade, impacto, responsável e prazo, e o template de diagnóstico em dezoito seções. O método permanece inteiramente aberto; o instrumental que economiza tempo passa a integrar o Kit Profissional.

### Fontes

- Todos os links de `fontes/fontes-publicas-brasil.md` verificados por requisição HTTP em 30/07/2026.

### Pendente antes de publicar

- verificação em navegador das duas páginas do IBGE que respondem 403 a requisição automatizada;
- canal privado de contato em `SECURITY.md`;
- renomeação do handle do GitHub;
- checklist de confidencialidade;
- autorização expressa de publicação.

## [0.1] · anterior

Versão *Do Lote à Cidade, Starter Kit*. Preservada, íntegra, fora deste repositório.
