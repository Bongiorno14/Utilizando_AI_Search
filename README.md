# UTILIZANDO AZURE AI SEARCH 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Bongiorno14/Utilizando_AI_Search/blob/main/LICENSE) 

# Sobre o projeto

Dando continuidade aos estudos de ferramentas IA, segue uma breve descriçao da utilização do Azure AI Search para indexação e consulta de dados.

O Azure AI Search oferece um conjunto robusto de recursos para indexação e consulta de dados, permitindo que organizações e desenvolvedores criem experiências de pesquisa personalizadas e inteligentes. 

o entender como aproveitar ao máximo as capacidades do Azure AI Search, é possível otimizar a descoberta de informações, melhorar a experiência do usuário em aplicativos e sites, além de obter insights valiosos a partir da análise dos padrões de pesquisa e comportamento dos usuários.

# Tecnologias utilizadas
## Azure
- Azure AI Search
- Azure Resource Groups
- Azure Storage Accounts

# Passo a Passo
1. Criação do Resource Group:
- Criação de um novo grupo de recursos no Azure para organizar todos os recursos relacionados ao projeto de pesquisa.
2. Criação do Serviço Azure AI Search:
- Criação de um novo serviço Azure AI Search dentro do grupo de recursos criado anteriormente.
3. Criação do Armazenamento (Storage):
- Criação de  um armazenamento no Azure para armazenar os dados que serão indexados pelo Azure AI Search.
4. Definição e Configuração do Índice de Dados:
- No serviço Azure AI Search, define-se e configura-se um índice para especificar como os dados serão estruturados e indexados.
5. Inserção dos Dados no Índice:
- Carrega-se os dados do armazenamento para o índice configurado no Azure AI Search para que eles possam ser consultados.
6. Configuração e Execução das Consultas:
- Configura-se as consultas de pesquisa conforme necessário, considerando os campos do índice e os requisitos de busca.

# Insights e Possibilidades
- O Azure AI Search oferece recursos avançados de personalização da experiência de pesquisa, como realces de texto para destacar termos de pesquisa nos resultados, sugestões de consulta para correção automática de erros ortográficos e aprimoramento da relevância dos resultados aplicando filtros dinamicos par refinar os resultados em diferentes categorias especificas do seu conjunto.
- A ferramenta se integra facilmente com outras ferramentas de desenvolvimento e análise de dados, como o Azure Cognitive Services para análise de sentimentos em textos, extração de entidades nomeadas (NER) e análise de imagem para enriquecer os metadados indexados, juntamente com plataformas de BI.
- Utilizando os insights gerados a partir das consultas realizadas no Azure AI Search, é possivel analisar padrões de pesquisa, tendências de conteúdo mais acessado, termos mais buscados e comportamento do usuário ao interagir com os resultados da pesquisa; podendo estas serem utilizadas para otimizar a relevância dos resultados, identificar lacunas de informação, entre outras possibilidades.
- O Azure AI Search oferece escalabilidade automática para lidar com volumes crescentes de dados e consultas simultâneas, garantindo um desempenho otimizado mesmo em ambientes de alta demanda.
- Além de buscar informações conhecidas, o Azure AI Search pode ser utilizado para explorar dados em busca de insights ocultos e padrões não perceptíveis à primeira vista, contribuindo para a tomada de decisões estratégicas e descoberta de novas oportunidades de negócio.

# Aprendizado
- A importância da modelagem adequada do índice para garantir resultados precisos.
- Como otimizar consultas para obter resultados relevantes e rápidos.
- Estratégias para lidar com grandes volumes de dados e manter a performance da pesquisa.
