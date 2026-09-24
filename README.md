# 🏎️ OMNIS — Porsche Sales Intelligence

Dashboard interativo de análise de vendas desenvolvido com auxílio de Inteligência Artificial a partir de uma base estruturada de dados da Porsche.

O projeto explora o uso de IA na construção de soluções analíticas, partindo da definição de perguntas de negócio, KPIs, filtros e requisitos de interface para gerar uma dashboard interativa em HTML.

> 🤖 O HTML, CSS e JavaScript deste projeto foram gerados com auxílio de Inteligência Artificial a partir das especificações e iterações realizadas durante o desenvolvimento.

---

## 🚀 Dashboard Interativo

### 👉 [Acessar Porsche Sales Intelligence](https://imperiusomnis.github.io/omnis-dashboard-porsche-sales/)

O dashboard está publicado através do GitHub Pages e pode ser utilizado diretamente pelo navegador.

Os filtros atualizam dinamicamente os indicadores, gráficos, rankings, insights e tabelas de acordo com o recorte selecionado.

---

## 🎯 Objetivo do Projeto

Transformar uma base de vendas de veículos Porsche em uma experiência analítica interativa capaz de responder perguntas de negócio relacionadas a:

- desempenho de vendas;
- receita;
- ticket médio;
- modelos mais vendidos;
- distribuição geográfica das vendas;
- ano dos modelos;
- métodos de pagamento;
- comportamento dos modelos por cidade.

Além da análise dos dados, o projeto teve como objetivo experimentar o uso de Inteligência Artificial para transformar requisitos analíticos em uma aplicação web funcional.

---

## ❓ Perguntas de Negócio

A dashboard foi construída para responder às seguintes perguntas:

1. Quais são os principais modelos de carros vendidos por cidade?
2. Qual ano de modelo apresenta o maior volume de vendas?
3. Quais carros apresentam maior popularidade de vendas em cada cidade?
4. Qual foi o método de pagamento mais utilizado?
5. Qual foi a receita total de vendas?
6. Qual foi o valor médio de venda por veículo?

As três primeiras perguntas fizeram parte da proposta original do desafio.

As três últimas foram adicionadas durante o desenvolvimento para ampliar a análise da base com indicadores financeiros e informações sobre os meios de pagamento.

---

## 📊 Principais KPIs

A visão executiva apresenta indicadores recalculados de acordo com os filtros selecionados:

- **Vendas:** quantidade de veículos no recorte atual;
- **Receita:** soma dos valores das vendas;
- **Ticket médio:** receita dividida pela quantidade de veículos vendidos;
- **Ano de modelo líder:** ano com maior frequência de vendas no recorte.

---

## 🔎 Filtros Interativos

O dashboard permite explorar os dados através dos seguintes filtros:

- **Modelo da Porsche**
- **Model Year**
- **City**
- **Pay Method**

Ao alterar qualquer filtro, as análises são recalculadas automaticamente.

Também está disponível a opção **Limpar filtros**, permitindo retornar à visualização completa da base.

---

## 📈 Análises Disponíveis

### 🏙️ Principais cidades por volume

Compara as cidades considerando:

- quantidade de vendas;
- receita gerada.

A visualização permite analisar tanto o volume comercial quanto o valor financeiro movimentado em cada localidade.

### 📅 Ano de modelo

Apresenta a distribuição dos veículos vendidos de acordo com o ano do modelo e permite identificar o ano com maior participação no recorte selecionado.

### 🚘 Modelos mais populares

Apresenta um ranking dos modelos Porsche de acordo com a quantidade de vendas.

### 💳 Mix de pagamento

Compara os métodos de pagamento utilizados, apresentando volume de vendas e participação percentual de cada método.

### 🧠 Insight executivo

O dashboard gera automaticamente uma leitura descritiva do recorte selecionado, destacando informações como:

- modelo líder;
- participação do modelo;
- ano de modelo predominante;
- cidade com maior volume;
- modelo de maior presença na cidade em destaque;
- receita do recorte.

Os insights representam padrões observados nos dados e não devem ser interpretados como relações de causa e efeito.

### 🌎 Modelos líderes por cidade

Uma tabela analítica complementa as visualizações apresentando:

- cidade;
- modelo(s) líder(es);
- vendas do modelo líder;
- total de vendas da cidade;
- participação;
- receita.

Essa análise permite identificar quais modelos apresentam maior presença em cada praça.

---

## 🧹 Qualidade dos Dados

Durante o processamento da base foram identificados **23 registros com data de venda inválida**.

Para manter transparência sobre o tratamento dessas informações:

- os indicadores de volume e receita consideram todos os registros;
- o período apresentado no dashboard considera somente datas válidas;
- a existência dos registros com datas inválidas é informada diretamente na interface.

Essa abordagem permite preservar os registros disponíveis sem ocultar uma limitação existente na qualidade da base.

---

## 🤖 Uso de Inteligência Artificial

A Inteligência Artificial foi utilizada como ferramenta de desenvolvimento da solução.

O processo partiu da definição de requisitos, incluindo:

- perguntas de negócio;
- KPIs;
- filtros;
- comportamento esperado do dashboard;
- direcionamento de UI/UX;
- ajustes realizados durante as iterações.

A IA foi responsável pela geração do código HTML, CSS e JavaScript, enquanto as instruções e ajustes realizados durante o projeto direcionaram a solução até a versão final.

O objetivo deste projeto não é demonstrar domínio de desenvolvimento web, mas explorar como a IA pode ser utilizada para transformar requisitos de negócio e análise de dados em uma aplicação funcional.

---

## 🎨 UI/UX

A interface foi orientada por uma proposta visual elegante e refinada, inspirada na identidade visual da Porsche Brasil.

Foram utilizados:

- contraste entre preto, branco e tons neutros;
- vermelho como cor de destaque;
- cards para indicadores;
- hierarquia visual;
- filtros organizados em painel;
- visualizações responsivas;
- organização voltada à leitura executiva.

---

## 🛠️ Tecnologias e Recursos

- Inteligência Artificial
- Prompt Engineering
- HTML
- CSS
- JavaScript
- GitHub
- GitHub Pages
- Análise de Dados
- Visualização de Dados

> HTML, CSS e JavaScript foram utilizados na solução gerada com auxílio de IA e não representam, por si só, domínio manual dessas tecnologias.

---

## 🧠 Principais Aprendizados

Durante o desenvolvimento deste projeto, pratiquei principalmente:

- transformar perguntas de negócio em requisitos analíticos;
- definir KPIs e dimensões relevantes para análise;
- estruturar instruções para uma IA;
- avaliar resultados produzidos por IA;
- realizar ajustes por meio de novas instruções;
- validar se as visualizações respondem às perguntas propostas;
- considerar qualidade e limitações dos dados;
- utilizar IA como ferramenta de apoio à construção de soluções analíticas;
- diferenciar geração automática de código de conhecimento técnico sobre programação.

O projeto reforçou que o uso de IA em análise de dados não elimina a necessidade de compreender o problema, os dados e as métricas utilizadas.

---

## 💬 Prompt Utilizado

O dashboard foi desenvolvido a partir de um prompt contendo os filtros, perguntas de negócio e direcionamento visual desejados:

```text
Utilizando o recurso de canvas, renderize uma dashboard em html ao lado.

#Filtros
-> Modelo da Porsche
-> Model Year
-> City
-> Pay Method

#Perguntas de negócios e KPIs
-> Quais os principais modelos de carros vendido por cidade.
-> Qual o ano de modelo de carro que mais saiu em um período.
-> Quero insight de carros populares de vendas com base nos dados em cada cidade.
-> Qual foi o método de pagamento mais usado.
-> Receita de vendas.
-> Qual valor médio de vendas por veículo.

Sobre ui/ux, se baseie no site oficial da porsche brasil.

Tenha um ar de elegante e refinado.
```

Após a geração inicial, foram realizadas novas interações com a IA para ajustar elementos da dashboard e chegar à versão final.

---

## 📁 Estrutura do Repositório

```text
omnis-dashboard-porsche-sales/
│
├── index.html
└── README.md
```

O arquivo `index.html` contém a aplicação interativa, incluindo os dados utilizados pelo dashboard, estilos e lógica de interação.

---

## ▶️ Como Visualizar

### 🌐 Online

A forma mais simples é acessar a versão publicada no GitHub Pages:

👉 **[Abrir Dashboard Interativo](https://imperiusomnis.github.io/omnis-dashboard-porsche-sales/)**

### 💻 Localmente

1. Faça o download do arquivo `index.html`;
2. abra o arquivo em um navegador;
3. utilize os filtros para explorar os dados.

Não é necessária instalação adicional para executar o dashboard.

---

## 📚 Origem do Projeto

Projeto desenvolvido como parte da formação **Análise de Dados com Excel e IA**, da **DIO**.

A atividade prática propôs o uso de Inteligência Artificial para transformar uma base de dados em um dashboard interativo.

As três primeiras perguntas de negócio foram definidas durante o desafio.

Como expansão da análise, foram adicionadas outras três perguntas relacionadas a:

- método de pagamento;
- receita de vendas;
- valor médio de venda por veículo.

Também foram realizadas iterações próprias sobre o resultado gerado pela IA para ajustar a solução final.

---

## ⚠️ Observação

Este projeto possui finalidade educacional e de portfólio.

Os dados utilizados pertencem à base fornecida para realização do desafio e as análises apresentadas devem ser interpretadas dentro desse contexto.

---

## 👤 Autor

**Adelson Sá Nobre**

Estudante de Ciência de Dados, desenvolvendo conhecimentos em Excel, Power Query, SQL, Power BI e análise de dados.

🔗 GitHub: [ImperiusOmnis](https://github.com/ImperiusOmnis)

---

⭐ Se este projeto foi útil ou interessante, fique à vontade para explorar o dashboard e o código disponível neste repositório.
