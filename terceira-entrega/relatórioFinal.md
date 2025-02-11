# Análise de Princípios de Bom Projeto de Código e Code Smells

## 1. Definição dos Princípios e sua Relação com Code Smells

### 1.1 Simplicidade

**Definição:** Um código simples é fácil de entender, direto e sem complexidades desnecessárias. Ele deve evitar sobrecarga de lógica e estruturas complicadas.

#### Code Smells Relacionados:

**Shotgun Surgery:** Código espalhado em vários lugares, tornando difícil modificar algo sem alterar diversas partes.

**Divergent Change:** Uma única classe sofre alterações frequentes por razões diferentes.

### 1.2 Elegância

**Definição:** Código elegante resolve problemas de forma concisa e eficiente, utilizando boas práticas de design.

**Code Smells Relacionados:**

**Long Method:** Métodos excessivamente longos que dificultam a compreensão.

**Large Class:** Classes que acumulam muitas responsabilidades.

### 1.3 Modularidade

**Definição:** Código modular divide-se em componentes independentes e reutilizáveis, facilitando manutenção e escalabilidade.

**Code Smells Relacionados:**

**God Class:** Uma única classe centraliza várias responsabilidades.

**Feature Envy:** Um método acessa mais atributos de outra classe do que da própria.

### 1.4 Boas Interfaces

**Definição:** Interfaces devem ser bem projetadas, intuitivas e fornecer apenas os métodos necessários para interação entre módulos.

**Code Smells Relacionados:**

**Inappropriate Intimacy:** Classes conhecem detalhes internos umas das outras.

**Message Chains:** Chamadas excessivas de métodos encadeados.

### 1.5 Extensibilidade

**Definição:** Um código bem projetado pode ser facilmente modificado ou expandido sem grandes retrabalhos.

**Code Smells Relacionados:**

**Rigid Hierarchy:** Estruturas de herança que dificultam mudanças.

**Refused Bequest:** Uma subclasse não utiliza métodos herdados da superclasse.

### 1.6 Evitar Duplicação

**Definição:** Código duplicado aumenta esforço de manutenção e risco de inconsistências.

**Code Smells Relacionados:**

**Duplicated Code:** Mesma lógica repetida em vários locais.

**Speculative Generality:** Código genérico sem necessidade real.

### 1.7 Portabilidade

**Definição:** Código portátil funciona em diferentes ambientes sem precisar de grandes adaptações.

**Code Smells Relacionados:**

**Hardcoded Values:** Uso de valores fixos em vez de configurações dinâmicas.

**Platform Dependencies:** Código acoplado a um ambiente específico.

### 1.8 Código Idiomático

**Definição:** Código que segue as convenções e práticas recomendadas da linguagem utilizada.

**Code Smells Relacionados:**

**Switch Statements:** Uso de estruturas switch em vez de polimorfismo.

**Alternative Classes with Different Interfaces:** Classes que fazem o mesmo, mas de maneiras distintas.

### 1.9 Código Bem Documentado

**Definição:** Código deve ter comentários claros, documentando propósito e funcionamento sem redundâncias.

**Code Smells Relacionados:**

**Comments:** Uso de comentários para explicar código mal escrito.

**Obsolete Comments:** Comentários que não refletem mais o código atual.

## 2. Análise dos Code Smells no Trabalho Prático 2




**Referência:**
 - Livros:

    1. FOWLER, Martin. Refactoring: Improving the Design of Existing Code. 2. ed. Boston: Addison-Wesley, 2018.

    2. GAMMA, Erich; HELM, Richard; JOHNSON, Ralph; VLISSIDES, John. Padrões de Projeto: Soluções Reutilizáveis de Software Orientado a Objetos. Porto Alegre: Bookman, 2000.

    3. BLOCH, Joshua. Effective Java. 2. ed. Boston: Addison-Wesley, 2008.

    4. MARTIN, Robert C. Código Limpo: Habilidades Práticas do Agile Software. Rio de Janeiro: Alta Books, 2009.

    5. MARTIN, Robert C. Agile Software Development: Principles, Patterns, and Practices. Upper Saddle River: Prentice Hall, 2002.

    6. SOMMERVILLE, Ian. Engenharia de Software. 10. ed. São Paulo: Pearson, 2019.

 - Artigos e Sites:

    1. ENGENHARIA de Software Moderna. Cap. 9: Refactoring. Disponível em: https://engsoftmoderna.info/cap9.html. Acesso em: 11 fev. 2025.

    2. SAMMAN Coaching. Divergent Change. Disponível em: https://sammancoaching.org/code_smells/divergent_change.html. Acesso em: 11 fev. 2025.

    3. SAMMAN Coaching. Message Chains. Disponível em: https://sammancoaching.org/code_smells/message_chains.html. Acesso em: 11 fev. 2025.

    4. LUZKAN. Insider Trading. Disponível em: https://luzkan.github.io/smells/insider-trading. Acesso em: 11 fev. 2025.

    5. C2 WIKI. Switch Statements Smell. Disponível em: https://wiki.c2.com/?SwitchStatementsSmell. Acesso em: 11 fev. 2025.

    6. BITO.AI. Eliminating Shotgun Surgery: Examples and Refactoring Guide. Disponível em: https://bito.ai/blog/eliminating-shotgun-surgery/. Acesso em: 11 fev. 2025.

    7. CELESTINO, André. Feature Envy. Disponível em: https://www.andrecelestino.com/feature-envy/. Acesso em: 11 fev. 2025.