# Prompts iniciais

Anexo instrumental. Os prompts apoiam a investigação; eles não produzem a leitura.

**Regra que vale para todos:** a IA opera sobre documento que você forneceu, não sobre conhecimento próprio. Toda saída nasce **I** ou **P**. Nenhuma vira **C** sem que você abra a fonte original.

## Antes de usar

Substitua os campos entre colchetes. Não envie dados pessoais, documentos sigilosos ou informações de clientes sem autorização e tratamento. Ver [SECURITY.md](../SECURITY.md).

Peça sempre que a IA:

- diferencie fato, inferência e pendência;
- não preencha lacuna por suposição;
- cite o trecho exato do documento fornecido;
- informe quando não puder confirmar algo;
- produza perguntas de validação;
- mantenha rastreabilidade das fontes.

---

## Prompt-base

Vale como cabeçalho de qualquer um dos outros.

```text
Atue como assistente de pesquisa. Não trate sua memória como fonte. Trabalhe
apenas com os documentos e links fornecidos. Para cada afirmação, indique o
documento, artigo, anexo ou página correspondente. Separe fatos, inferências e
pendências. Preserve exceções e remissões. Se houver conflito, ausência ou
dúvida, não conclua: registre a divergência e formule a validação necessária.
```

---

## 1 · Organizar o dossiê

```text
Atue como assistente de organização de uma análise preliminar de terreno.

Vou fornecer informações e documentos sobre um terreno em [MUNICÍPIO/UF].

Sua tarefa é:
1. organizar os dados nas oito dimensões: enquadramento da decisão, identidade
   e documentos, condições físicas, regras urbanísticas, ambiente,
   infraestrutura e acessibilidade, território e escalas, mercado e riscos;
2. atribuir a cada afirmação um status, C confirmado, I indício, P pendente, e
   uma origem, própria, oficial, técnica secundária, terceiro ou IA;
3. não completar informação ausente;
4. apontar incompatibilidades entre os dados;
5. produzir lista priorizada do que ainda deve ser solicitado.

Nenhuma afirmação produzida por você pode receber status C.
Não conclua viabilidade.

Dados disponíveis:
[INSERIR]
```

## 2 · Criar um plano de pesquisa

```text
Com base no dossiê abaixo, crie um plano de pesquisa para a primeira leitura.

Para cada pendência, apresente:
- pergunta;
- por que importa para a decisão;
- possível fonte primária;
- órgão responsável;
- documento ou camada esperada;
- risco de não obter a informação;
- profissional indicado para a validação.

Ordene por impacto na decisão, não por facilidade de resolver.

Dossiê:
[INSERIR]
```

## 3 · Ler um documento urbanístico fornecido

```text
Analise somente o documento fornecido. Não use memória geral para completar
o conteúdo.

Extraia:
- nome e identificação do documento;
- data;
- órgão responsável;
- indicação de vigência encontrada no próprio arquivo;
- área territorial abrangida;
- artigos e anexos potencialmente relacionados ao terreno;
- parâmetros encontrados;
- definições importantes;
- exceções;
- remissões a outras normas;
- dúvidas que exigem consulta oficial.

Para cada informação, cite artigo, página, tabela ou anexo.

Se o documento não permitir confirmar vigência ou incidência sobre o terreno,
declare isso.
```

## 4 · Montar uma tabela de parâmetros

```text
Transforme os trechos fornecidos em tabela preliminar de parâmetros
urbanísticos.

Colunas: parâmetro, valor ou regra, unidade, condição de aplicação, artigo ou
anexo, página, status, observação, consulta necessária.

Não calcule potencial construtivo quando faltarem dados. Não escolha entre
regras conflitantes: destaque a divergência.
```

## 5 · Estruturar a triagem ambiental

```text
Crie um roteiro de triagem ambiental preliminar para o terreno descrito abaixo.

Considere apenas categorias de investigação. Não declare presença nem ausência
de restrição.

Para cada categoria, indique:
- o que investigar;
- fonte primária provável;
- escala e limitação do dado;
- documento necessário;
- especialista ou órgão responsável;
- possível impacto na decisão.

Terreno:
[INSERIR LOCALIZAÇÃO E DADOS NÃO SIGILOSOS]
```

## 6 · Analisar o entorno em escalas

```text
Estruture a análise do entorno nas escalas rua e quadra, bairro, cidade e
região.

Em cada escala, indique variáveis, dados necessários, observação de campo,
fontes possíveis, relações a testar e limitações.

Não transforme proximidade em causalidade. Não conclua valorização sem
evidência. O que o entorno é hoje pode ser verificado; para onde ele está indo
é sempre inferência.
```

## 7 · Preparar perguntas para consulta oficial

```text
Transforme as pendências abaixo em perguntas objetivas para consulta ao órgão
competente.

Para cada pergunta:
- indique o tema;
- apresente o contexto mínimo necessário;
- evite induzir a resposta;
- solicite a base legal ou técnica;
- peça identificação do documento, artigo, mapa ou processo aplicável.

Pendências:
[INSERIR]
```

## 8 · Revisar rastreabilidade

```text
Revise a leitura abaixo como auditor de rastreabilidade.

Para cada afirmação, verifique se ela tem status e origem, e se o status é
compatível com a origem. Origem terceiro ou IA não pode ter status C.

Aponte: afirmação sem fonte, status incompatível com a origem, data
desatualizada, conflito não declarado, ausência de informação tratada como
ausência de restrição, e conclusão que ultrapassa a evidência.
```

---

## O que não está aqui

Dois prompts do material anterior foram retirados deste anexo: o que monta a **matriz de riscos completa**, com probabilidade, impacto, responsável e prazo, e o que estrutura o **relatório em dezesseis seções**. Os dois produzem o instrumental que economiza tempo de escritório, não o método, e por isso pertencem ao Kit Profissional.

O método permanece inteiramente aberto neste repositório.
