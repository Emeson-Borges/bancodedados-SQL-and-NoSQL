# Engenharia de Dados: Bancos de Dados Relacionais (SQL) e Não Relacionais (NoSQL)

Na área de engenharia de dados, é fundamental entender os conceitos de bancos de dados relacionais (SQL) e não relacionais (NoSQL), pois desempenham papéis distintos no armazenamento, processamento e recuperação de dados.

## Bancos de Dados Relacionais (SQL):

- **Tabelas e Esquemas:** Os bancos de dados relacionais organizam os dados em tabelas com esquemas predefinidos. Cada tabela contém registros com campos específicos.

- **Esquema Rígido:** Os bancos de dados relacionais têm um esquema rígido, o que significa que a estrutura das tabelas e os tipos de dados são definidos antes de inserir dados. Mudanças no esquema podem ser complicadas.

- **SQL:** A consulta é realizada usando a linguagem SQL (Structured Query Language), que é poderosa para consultar e manipular dados de maneira estruturada.

- **Integridade de Dados:** Os bancos de dados relacionais têm suporte embutido para garantir a integridade dos dados, como chaves primárias, chaves estrangeiras e restrições de integridade.

- **ACID:** A maioria dos bancos de dados relacionais segue o modelo ACID (Atomicidade, Consistência, Isolamento e Durabilidade), o que garante transações confiáveis.

- **Escalabilidade Vertical:** A escalabilidade de bancos de dados relacionais é tipicamente vertical, o que significa que é necessário aumentar a capacidade de hardware para lidar com cargas de trabalho maiores.

## Bancos de Dados Não Relacionais (NoSQL):

- **Modelos Flexíveis:** Os bancos de dados NoSQL não impõem uma estrutura de tabela rígida. Eles permitem que os dados sejam armazenados em formatos flexíveis, como documentos, pares chave-valor, gráficos e colunas.

- **Esquema Dinâmico:** Os bancos de dados NoSQL têm esquemas dinâmicos, o que significa que você pode adicionar campos sem modificar o esquema global.

- **Query Language:** Alguns bancos de dados NoSQL têm suas próprias linguagens de consulta, enquanto outros usam abordagens de consulta flexíveis.

- **Escalabilidade Horizontal:** Os bancos de dados NoSQL são frequentemente projetados para escalabilidade horizontal, o que permite distribuir dados em vários servidores para lidar com cargas de trabalho maiores.

- **Tipos de NoSQL:** Existem várias categorias de bancos de dados NoSQL, incluindo bancos de dados de documentos (como MongoDB), bancos de dados chave-valor (como Redis), bancos de dados de colunas (como Cassandra) e bancos de dados de grafo (como Neo4j).

- **Consistência Flexível:** Em alguns bancos de dados NoSQL, a consistência é flexível e pode ser eventual, o que significa que os dados podem não ser imediatamente consistentes em todos os nós do banco de dados.

A escolha entre bancos de dados relacionais e não relacionais na engenharia de dados depende dos requisitos do projeto, da natureza dos dados e do desempenho desejado. Em muitos cenários, uma combinação de ambos os tipos de banco de dados é usada para atender a diferentes necessidades dentro de uma arquitetura de engenharia de dados.
