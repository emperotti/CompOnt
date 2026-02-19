# Nome da Ontologia: CompOnt

![Ontology Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![BFO Version](https://img.shields.io/badge/BFO-2020-blue)
![License](https://img.shields.io/badge/License-CC--BY%204.0-green)

## 1. Visão Geral e Propósito

Esta ontologia é um módulo de domínio que estende o **Basic Formal Ontology (BFO)**, em conformidade com a norma **ISO/IEC 21838-2:2021**. Seu propósito é fornecer uma estrutura formal para o domínio de **Mapeamento de Competências Educacionais**, servindo como base para a interoperabilidade semântica entre sistemas de informação heterogêneos.

## 2. Conformidade com a ISO/IEC 21838

A ontologia estabelece conformidade através de **extensão direta**. Todas as classes de domínio são especializações de categorias de alto nível do BFO, garantindo que o resultado seja uma ontologia consistente e logicamente rigorosa.

### Hierarquia de Topo (Baseada no BFO 2020)

A estrutura segue a distinção fundamental da BFO:

* **Continuants**: Entidades que persistem no tempo e mantêm sua identidade mesmo sofrendo mudanças (ex: objetos, qualidades, funções).
* **Occurrents**: Entidades que ocorrem no tempo e têm partes temporais (ex: processos, eventos, intervalos temporais).

## 3. Demonstração de Abrangência (Breadth of Coverage)

Seguindo os requisitos da **ISO/IEC 21838-1:2021, 4.4.6**, as seguintes dimensões da realidade são cobertas por esta ontologia:

### 3.1 Espaço e Tempo (Space and Time)
* **Abordagem**: A ontologia utiliza relações de ocupação (*occupies*) entre *independent continuants* e *spatial regions*.
* **Regiões**: Reconhece regiões espaciais de 0 a 3 dimensões e regiões temporais (instantes e intervalos).

### 3.2 Objetos e Mudança (Time and Change)
* **Identidade**: Objetos materiais preservam sua identidade enquanto mudam suas qualidades ou localização ao longo do tempo.
* **Processos**: Mudanças são tratadas como processos (*occurrents*) que não ganham ou perdem partes, mas ocorrem em fases temporais.

### 3.3 Qualidades e Atributos (Qualities and Attributes)
* **Dependência Específica**: Atributos como temperatura ou cor são tratados como qualidades que dependem especificamente de seus portadores (*bearers*).
* **Disposições**: Capacidades ou tendências (ex: fragilidade, condutividade) são tratadas como entidades realizáveis (*realizable entities*) que podem ou não ser manifestadas por processos[cite: 380].

### 3.4 Partes e Todos (Parts, Wholes, and Boundaries)
* **Mereologia**: Define relações de *parthood* distintas para continuantes (que podem mudar de partes) e ocorrentes (que têm partes fixas no tempo).
* **Unidade**: Distingue entre objetos únicos com unidade causal (ex: um motor) e agregados de objetos (ex: uma frota).

### 3.5 Informação e Artefatos (Information and Artefacts)
* **Entidades de Informação**: Artefatos de informação (manuais, designs, especificações) são tratados como *generically dependent continuants.
* **Referência**: Utiliza a relação de *aboutness* (sobreidade) para conectar entidades de informação à porção da realidade que elas descrevem ou prescrevem.

## 4. Gestão e Governança da Ontologia

Em conformidade com a **ISO/IEC 21838-1, 4.4.8**:

* **Licença**:  CC-BY 4.0
* **Manutenção**: Gerida conforme os princípios do **OBO Foundry**.
* **Versionamento**: Utiliza versionamento semântico via GitHub Releases.
* **IRIs**: Identificadores persistentes seguindo os padrões W3C.

---
*Autores:*
