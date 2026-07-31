# Fontes públicas brasileiras

Ponto de partida por categoria. Bases nacionais não substituem fontes estaduais e municipais, levantamentos de campo ou consultas formais.

**Links verificados por requisição HTTP em 30/07/2026.** Verificação de status não é verificação de conteúdo: um portal pode responder e ainda assim ter mudado de estrutura, de base ou de escala.

---

## Regra de uso

Antes de usar qualquer dado, registre:

- instituição produtora;
- nome da base;
- versão ou data;
- escala;
- sistema de referência;
- cobertura territorial;
- limitações;
- forma de acesso;
- link permanente, quando disponível.

Sem esses campos, o dado entra na leitura como **I**, não como **C**.

---

## Legislação e planejamento municipal

Não há link nacional. A fonte é sempre municipal, e é a mais frágil de todas.

Priorize, nesta ordem:

1. portal oficial da prefeitura;
2. secretaria municipal de planejamento ou urbanismo;
3. diário oficial;
4. sistema oficial de mapas;
5. legislação consolidada;
6. atendimento ou consulta formal protocolada.

Procure:

- Plano Diretor;
- lei de uso e ocupação do solo;
- lei de parcelamento do solo;
- código de obras;
- mapas de zoneamento e seus anexos;
- decretos regulamentadores;
- leis complementares e alterações posteriores;
- diretrizes viárias;
- processos e consultas urbanísticas anteriores sobre o imóvel.

**Não confie apenas em compilações de terceiros.** Confirme vigência e alterações. Em boa parte dos municípios brasileiros, a fonte oficial não está onde deveria: falta anexo, o mapa não conversa com o texto, a versão publicada não é a vigente. Isso não autoriza promover fonte secundária a **C**. Autoriza registrar **P** com o caminho de consulta formal ao lado.

---

## Cartografia e dados geoespaciais

### Infraestrutura Nacional de Dados Espaciais · INDE

- Portal: https://inde.gov.br/
- Catálogo de geosserviços: https://inde.gov.br/CatalogoGeoservicos

Cataloga e integra dados geoespaciais produzidos por instituições governamentais. A existência de um dado no catálogo não elimina a necessidade de consultar seus metadados.

### IBGE · Geociências

- Downloads: https://www.ibge.gov.br/geociencias/downloads-geociencias.html
- Bases cartográficas contínuas: https://www.ibge.gov.br/geociencias/cartas-e-mapas/bases-cartograficas-continuas.html

Apoia a leitura de limites, localidades, redes e relevo. **Verifique a escala antes de usar:** base contínua nacional não resolve limite de lote.

> `[REVISÃO NECESSÁRIA]` os dois endereços do IBGE responderam 403 a requisição automatizada em 30/07/2026, o que costuma indicar bloqueio de acesso programático e não link morto. O domínio principal responde normalmente. Confirmar em navegador antes de publicar.

---

## Recursos hídricos

### Sistema Nacional de Informações sobre Recursos Hídricos · SNIRH

- Portal: https://www.snirh.gov.br/
- Hidroweb: https://www.snirh.gov.br/hidroweb/
- Dados abertos da ANA: https://dadosabertos.ana.gov.br/

Apoiam pesquisa hidrológica e hidrometeorológica. **Não utilize base nacional para delimitar, sozinha, área de preservação permanente, faixa marginal, nascente ou qualquer condição local.** A delimitação é local e tem responsável técnico.

---

## Unidades de conservação

### Cadastro Nacional de Unidades de Conservação · CNUC

- Informações: https://www.gov.br/mma/pt-br/assuntos/biodiversidade-e-biomas/areas-protegidas/plataforma-cnuc-1
- Mapa: https://cnuc.mma.gov.br/map

Reúne unidades federais, estaduais, municipais e privadas. Consulte também o órgão gestor e o plano de manejo, porque a zona de amortecimento e as regras de uso não estão no cadastro.

### ICMBio · dados geoespaciais

- Dados: https://www.gov.br/icmbio/pt-br/dados-icmbio/dados_geoespaciais

Unidades de conservação federais e outros temas produzidos pelo Instituto.

---

## Imóveis rurais e dados fundiários

### SIGEF · Incra

- Sistema: https://sigef.incra.gov.br/
- Consulta de parcelas certificadas: https://www.gov.br/pt-br/servicos/consultar-parcelas-certificadas
- Acervo e arquivos: https://www.gov.br/pt-br/servicos/obter-coordenadas-e-baixar-os-arquivos-dos-imoveis-ruras-certificados

Trata da certificação de limites de imóveis rurais. **Parcela certificada não substitui matrícula, cadeia dominial nem análise registral.** Certificação é sobre geometria, não sobre domínio.

---

## Estatística e contexto territorial

### IBGE

- Portal: https://www.ibge.gov.br/
- SIDRA, Sistema IBGE de Recuperação Automática: https://sidra.ibge.gov.br/

Apoia análise populacional, domiciliar, econômica e territorial. Registre ano, unidade geográfica e metodologia. Setor censitário e bairro não são a mesma unidade, e comparar séries de censos diferentes exige declarar a mudança de metodologia.

---

## Fontes estaduais e municipais

Busque, conforme o território:

- instituto ou secretaria estadual de meio ambiente;
- recursos hídricos;
- geologia e mineração;
- infraestrutura e transporte;
- patrimônio cultural;
- saneamento;
- energia;
- defesa civil;
- planejamento metropolitano;
- prefeitura;
- autarquias e concessionárias.

A concessionária é a única fonte que confirma **viabilidade de atendimento**. Rede existente na via, vista em campo ou em mapa, é **I**.

---

## Fontes de mercado

Anúncios, portais imobiliários, relatórios privados e informação de corretor podem apoiar hipótese de mercado. Nenhum deles é prova isolada de preço, liquidez ou demanda. **Preço anunciado não é preço realizado.**

Registre:

- data da coleta;
- preço anunciado;
- condição do imóvel;
- área;
- localização;
- tempo de exposição, quando conhecido;
- fonte;
- diferenças entre os comparáveis.

---

## Hierarquia de evidência

Da mais forte para a mais fraca. Serve para decidir o status quando duas fontes discordam.

1. documento ou dado oficial específico do terreno;
2. legislação vigente e mapa oficial;
3. consulta formal ao órgão competente;
4. levantamento técnico;
5. base pública com metadados adequados;
6. fonte técnica secundária;
7. informação de mercado;
8. relato de terceiro;
9. hipótese produzida durante a análise.

Os itens 1 a 4 podem sustentar **C**. Os itens 5 e 6 sustentam **C** apenas quando os metadados cobrem a escala e a data necessárias. Os itens 7 a 9 nascem **I** e não são promovidos sem uma fonte das quatro primeiras posições.
