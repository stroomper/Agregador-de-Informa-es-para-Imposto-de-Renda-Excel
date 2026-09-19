# 📊 Agregador de Informações para Imposto de Renda — Excel

## 📌 Sobre o projeto

Este projeto consiste no desenvolvimento de uma **ferramenta em Excel para organização e consolidação de informações necessárias à declaração do Imposto de Renda Pessoa Física (IRPF)**.

A proposta é criar um **agregador de dados**, permitindo que o usuário registre, organize e consulte informações financeiras e cadastrais de forma estruturada, reduzindo a dispersão de documentos e facilitando a preparação das informações para a declaração.

A solução é desenvolvida **inteiramente no Microsoft Excel**, utilizando recursos nativos da ferramenta para criar uma experiência organizada, validada e de fácil utilização.

---

## 🎯 Objetivo

Criar uma ferramenta que permita ao usuário:

* Centralizar informações importantes para o Imposto de Renda;
* Organizar dados cadastrais e financeiros;
* Registrar informes de rendimentos;
* Controlar entradas financeiras ao longo do ano;
* Associar documentos e comprovantes às informações registradas;
* Reduzir erros de preenchimento por meio de validações;
* Facilitar a conferência das informações antes da declaração;
* Ter acesso rápido às principais áreas da ferramenta;
* Criar uma estrutura que possa ser expandida para novas categorias de informações.

---

## 🧩 Estrutura atual

A ferramenta está organizada em diferentes abas, cada uma com uma finalidade específica.

### 👤 Titular

Área destinada ao cadastro das informações pessoais do contribuinte.

Entre os dados contemplados estão:

* Nome;
* CPF;
* Data de nascimento;
* Título de eleitor;
* Cônjuge;
* Endereço;
* Informações complementares.

A centralização dessas informações facilita o acesso aos dados básicos necessários durante o processo de declaração.

---

### 🏦 Informes

Área destinada ao registro dos **informes de rendimentos bancários e informações relacionadas às instituições financeiras**.

O usuário pode registrar informações como:

* Instituição financeira;
* Código do banco;
* Valor informado;
* Documento ou informe correspondente;
* Anexo relacionado à informação.

A ferramenta também possui mecanismos para **consolidação dos valores registrados**, permitindo uma visualização geral das informações inseridas.

---

### 💰 Notas

Área destinada ao registro das **entradas financeiras**, como valores provenientes de receitas, notas ou informações extraídas de documentos financeiros.

Os registros possuem campos como:

* Data;
* Categoria;
* Valor.

Essa estrutura permite organizar as entradas cronologicamente e criar uma base de dados que poderá ser utilizada posteriormente para análises e conferências.

---

### 📚 TABELAS

A aba **TABELAS** funciona como uma base auxiliar para alimentar recursos da planilha, principalmente listas utilizadas em validações e menus suspensos.

Um exemplo é a relação de instituições financeiras e seus respectivos códigos.

Essa separação permite manter as informações auxiliares organizadas sem interferir diretamente na interface utilizada pelo usuário.

---

## ⚙️ Recursos utilizados

O projeto utiliza recursos nativos do Excel para transformar uma planilha convencional em uma ferramenta estruturada.

Entre eles:

* ✅ Validação de dados;
* ✅ Listas suspensas;
* ✅ Fórmulas automáticas;
* ✅ Soma e consolidação de informações;
* ✅ Organização por categorias;
* ✅ Campos padronizados;
* ✅ Links e referências para documentos;
* ✅ Abas auxiliares;
* ✅ Estrutura preparada para expansão;
* ✅ Interface orientada à navegação do usuário.

---

## 🔗 Organização de documentos

Um dos objetivos do projeto é permitir que as informações registradas possam ser relacionadas aos seus respectivos documentos.

Por exemplo:

> **Banco → Valor informado → Documento/Informe correspondente**

Dessa forma, o usuário pode manter a informação registrada na planilha juntamente com uma referência ao documento que comprova aquele dado.

Isso contribui para uma organização mais eficiente durante a preparação da declaração.

---

## 🛡️ Validação e confiabilidade

A ferramenta busca reduzir erros comuns de preenchimento por meio de **padronização e validação dos dados**.

As validações podem ser utilizadas para:

* Evitar categorias inconsistentes;
* Padronizar nomes de instituições;
* Reduzir erros de digitação;
* Controlar formatos de data;
* Garantir o preenchimento de determinados campos;
* Facilitar a conferência das informações.

A proposta não é substituir a conferência do contribuinte ou de um profissional contábil, mas **melhorar a qualidade e a organização dos dados utilizados no processo**.

---

## 🧭 Experiência de utilização

A ferramenta foi pensada para que o usuário não precise dominar fórmulas ou conhecimentos avançados de Excel.

A experiência proposta segue o fluxo:

**1. Cadastro do titular**
↓
**2. Registro dos informes**
↓
**3. Registro das entradas e demais informações**
↓
**4. Associação dos documentos**
↓
**5. Conferência dos dados**
↓
**6. Preparação das informações para a declaração**

A ideia é transformar uma tarefa potencialmente desorganizada em um processo mais estruturado e rastreável.

---

## 🚀 Possíveis evoluções

O projeto possui potencial para receber novas funcionalidades, como:

* 📈 Dashboard com indicadores financeiros;
* 📊 Resumo anual das movimentações;
* 🗂️ Controle de documentos pendentes;
* 🔎 Pesquisa e filtros de registros;
* ⚠️ Alertas para informações incompletas;
* 📅 Controle por ano-calendário;
* 🧾 Novas categorias de rendimentos e despesas;
* 🔗 Sistema de navegação entre as abas;
* 📎 Controle mais avançado de anexos;
* 📝 Checklist para preparação da declaração;
* 📤 Geração de relatórios para conferência;
* 🔄 Estrutura para reutilização em diferentes anos.

---

## 💻 Tecnologias

O projeto foi desenvolvido utilizando:

**Microsoft Excel**

Recursos utilizados:

* Fórmulas;
* Validação de dados;
* Listas suspensas;
* Referências entre células;
* Tabelas auxiliares;
* Hiperlinks;
* Organização de planilhas;
* Formatação condicional;
* Recursos de automação disponíveis no Excel.

---

## 📁 Estrutura do projeto

```text
📊 Planilha de Impostos.xlsx
│
├── 👤 Titular
│   └── Dados cadastrais do contribuinte
│
├── 🏦 Informes
│   └── Informações e informes bancários
│
├── 💰 Notas
│   └── Registro de entradas financeiras
│
└── 📚 TABELAS
    └── Bases auxiliares e listas de validação
```

---

## ⚠️ Aviso

Esta ferramenta possui finalidade **organizacional e de apoio à preparação das informações** para a declaração do Imposto de Renda.

Ela não substitui a declaração oficial da Receita Federal, a análise da legislação vigente ou a orientação de um profissional habilitado.

O usuário é responsável por conferir a exatidão das informações inseridas e verificar quais dados e documentos são efetivamente necessários para sua declaração.

---

## 📌 Status do projeto

**🟡 Em desenvolvimento**

A estrutura inicial da ferramenta já está definida e novas funcionalidades poderão ser incorporadas conforme a evolução do projeto.

---

## 👨‍💻 Projeto

Desenvolvido como um projeto de **organização de dados, automação e aplicação prática do Excel**, buscando transformar uma planilha tradicional em uma ferramenta mais estruturada, intuitiva e funcional.

> **Organizar os dados hoje para simplificar a declaração amanhã.**
