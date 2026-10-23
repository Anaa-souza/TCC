<div align="center">

# 🩸 HEMUNI

### Conectando pessoas, instituições e informação para transformar a doação de sangue.

<br>

[![Sprint](https://img.shields.io/badge/SPRINT-01%20%7C%2002-970000?style=for-the-badge)](.)
[![Status](https://img.shields.io/badge/STATUS-Em%20desenvolvimento-AE0202?style=for-the-badge)](.)
[![TCC](https://img.shields.io/badge/PROJETO-TCC%20SENAI-2E2E2E?style=for-the-badge)](.)
[![UX/UI](https://img.shields.io/badge/UX%2FUI-Figma-970000?style=for-the-badge&logo=figma&logoColor=white)](.)

</div>

---

## 🩸 Sobre o HEMUNI

O **HEMUNI** é uma solução digital desenvolvida como projeto de **Trabalho de Conclusão de Curso (TCC)**, com o objetivo de centralizar informações e funcionalidades relacionadas à **doação de sangue**.

A proposta busca aproximar diferentes participantes desse processo:

🩸 **Doadores** • 👤 **Não doadores** • 🏥 **Hospitais** • 🧑‍⚕️ **Pacientes** • 🏢 **Hemocentros** • ⚙️ **Administradores**

O sistema está sendo planejado para possuir uma versão **Web**, reunindo funcionalidades como informações sobre doação, hemocentros, agendamentos, histórico, solicitações de sangue, campanhas e controle de estoque.

---

<div align="center">

### 🔴 Conectando para transformar.

</div>

---

# 🚀 Sprint 01 — Planejamento e Prototipação

A **Sprint 01** representa a etapa inicial de planejamento e estruturação do HEMUNI.

O foco desta etapa está na definição da **identidade do projeto**, levantamento dos **requisitos**, construção da **modelagem inicial do banco de dados** e criação dos primeiros **wireframes da interface**.

### 🎯 Objetivo

> Transformar a ideia inicial do HEMUNI em uma estrutura organizada, definindo sua identidade, funcionalidades, dados e experiência inicial do usuário.

---

# 📌 Entregáveis da Sprint 01

| 🧩 Etapa | 📄 Entregável | Status |
|:---:|:---|:---:|
| 🎨 | Identidade da Marca e Branding | ✅ Concluído |
| 📋 | Documento de Requisitos | ✅ Concluído |
| 🗄️ | MER — Modelo Entidade-Relacionamento | ✅ Concluído |
| 🗃️ | DER — Diagrama Entidade-Relacionamento | ✅ Concluído |
| 🖥️ | Wireframes / Mockups | 🚧 Em desenvolvimento |

---

# 🎨 01. Identidade da Marca

O nome **HEMUNI** foi criado a partir da combinação de:

> **HEM** → Hemocentro  
> **UNI** → União

A ideia representa a proposta central do projeto: **unir pessoas e instituições por meio da tecnologia para facilitar o processo relacionado à doação de sangue.**

## ❤️ Identidade Visual

A identidade visual do HEMUNI utiliza principalmente tons de vermelho, acompanhados por cores neutras e auxiliares.

### 🎨 Cores Primárias

| Nome | Hexadecimal |
|:---:|:---:|
| 🔴 Primário -1 | `#970000` |
| 🔴 Primário | `#AE0202` |
| 🔴 Primário +1 | `#D50000` |

### 🎨 Cores Secundárias

| Nome | Hexadecimal |
|:---:|:---:|
| 🔴 Secundária -1 | `#B7251A` |
| 🔴 Secundária | `#8C1A11` |
| 🔴 Secundária +1 | `#731A13` |

### ⚫ Dark

| Nome | Hexadecimal |
|:---:|:---:|
| Dark -1 | `#2E2E2E` |
| Dark | `#141414` |
| Dark +1 | `#000000` |

### ⚪ Light

| Nome | Hexadecimal |
|:---:|:---:|
| Light -1 | `#819EB1` |
| Light | `#FFFFFF` |
| Light +1 | `#849AA8` |

### 🟢 Success

| Nome | Hexadecimal |
|:---:|:---:|
| Success -1 | `#5AD866` |
| Success | `#52D65F` |
| Success +1 | `#27A533` |

### 🔴 Danger

| Nome | Hexadecimal |
|:---:|:---:|
| Danger -1 | `#FF4E33` |
| Danger | `#CC1B00` |

## 🔤 Tipografia

A identidade visual utiliza duas famílias tipográficas principais:

### **Inter**
Utilizada em títulos, cabeçalhos e elementos de destaque.

### **Poppins**
Utilizada em textos, parágrafos, botões e demais elementos da interface.

### 📐 Escala Tipográfica

| Elemento | Tamanho |
|:---:|:---:|
| Small | 14px |
| Parágrafo | 16px |
| H5 | 18px |
| H4 | 24px |
| H3 | 28px |
| H2 | 34px |
| H1 | 40px |

---

# 📋 02. Documento de Requisitos

Os requisitos do HEMUNI foram organizados em três categorias principais.

## ⚙️ Requisitos Funcionais

Definem **o que o sistema deverá fazer**.

- Cadastro de usuários;
- Login;
- Gerenciamento de dados;
- Diferentes perfis de acesso;
- Informações sobre doação de sangue;
- Consulta de hemocentros;
- Agendamento;
- Histórico;
- Solicitações de sangue;
- Controle de estoque;
- Gerenciamento de campanhas;
- Consulta de campanhas;
- Gerenciamento de informações institucionais.

## 🛡️ Requisitos Não Funcionais

Definem características de qualidade do sistema:

- Responsividade;
- Facilidade de navegação;
- Segurança;
- Controle de acesso;
- Proteção de dados;
- Organização do banco de dados;
- Mensagens de validação;
- Padronização visual;
- Privacidade.

## 📌 Regras de Negócio

Definem condições específicas do funcionamento do HEMUNI:

- Cada usuário possui um perfil de acesso;
- As funcionalidades disponíveis dependem das permissões do perfil;
- Agendamentos devem estar vinculados a um usuário e a um hemocentro;
- O estoque deve ser gerenciado por usuários autorizados;
- Solicitações de sangue devem conter informações sobre o tipo sanguíneo e a necessidade;
- Campanhas devem possuir informações como nome, descrição, período e local.

---

# 🗄️ 03. Modelagem do Sistema

A modelagem inicial foi desenvolvida para representar como as principais informações do HEMUNI serão organizadas.

## 🔷 MER — Modelo Entidade-Relacionamento

O MER representa a estrutura conceitual inicial do sistema.

### Entidades

🩸 **Tipo Sanguíneo**  
👤 **Doador**  
💉 **Doação**  
🏥 **Hemocentro**  
📢 **Campanha**

### Relacionamentos

    TIPO_SANGUÍNEO
           │
           │ possui
           ▼
        DOADOR
           │
           │ realiza
           ▼
         DOAÇÃO
           │
           │ acontece em
           ▼
      HEMOCENTRO
           │
           │ promove
           ▼
       CAMPANHA

---

## 🗃️ DER — Diagrama Entidade-Relacionamento

O DER detalha a estrutura das entidades, apresentando:

- 🔑 Chaves Primárias (PK);
- 🔗 Chaves Estrangeiras (FK);
- 📝 Atributos;
- 💾 Tipos de dados;
- 🔄 Relacionamentos.

---

# 🖥️ 04. Wireframes & Mockups

Os wireframes representam a primeira estrutura visual das interfaces do HEMUNI.

O objetivo desta etapa é definir:

> **Como o usuário irá visualizar, entender e navegar pelo sistema?**

Os primeiros protótipos foram desenvolvidos no **Figma**, considerando a experiência da versão Web.

## 🔐 Tela de Login

A tela de Login foi planejada para permitir o acesso dos usuários cadastrados.

**Elementos principais:**

- Logo HEMUNI;
- Campo de e-mail;
- Campo de senha;
- Botão de entrada;
- Acesso ao cadastro;
- Recuperação de senha.

## 📝 Tela de Cadastro

A tela de Cadastro permite que um novo usuário crie sua conta na plataforma.

**Elementos principais:**

- Nome;
- E-mail;
- CPF;
- Data de nascimento;
- Senha;
- Tipo sanguíneo;
- Botão de cadastro.

## 🏠 Dashboard

O Dashboard será o principal ponto de navegação após o Login.

Dependendo do perfil do usuário, diferentes funcionalidades poderão ser apresentadas.

**Funcionalidades:**

🩸 Doação  
🏥 Hemocentros  
📅 Agendamentos  
📋 Histórico  
📢 Campanhas  
👤 Perfil  
🩸 Solicitações  
📦 Estoque

---

# 🚀 Sprint 02 — Desenvolvimento do Sistema

A **Sprint 02** dá continuidade ao planejamento e à prototipação realizados na primeira etapa. Seu foco é iniciar a implementação do HEMUNI, transformando os requisitos e as interfaces planejadas em funcionalidades para a versão Web.

Nesta etapa, a equipe trabalha na estruturação do Front-End, no desenvolvimento do Back-End e na implementação do banco de dados, buscando integrar as partes necessárias para o funcionamento do sistema.

### 🎯 Objetivo

> Iniciar o desenvolvimento do HEMUNI Web, utilizando os requisitos, a modelagem e os protótipos definidos na Sprint 01 como referência para a implementação das funcionalidades.

---

# 📌 Entregáveis da Sprint 02

| 🧩 Etapa | 📄 Entregável | Status |
|:---:|:---|:---:|
| 🖥️ | Estrutura inicial do Front-End | 🚧 Em desenvolvimento |
| ⚙️ | Estrutura inicial do Back-End | 🚧 Em desenvolvimento |
| 🗄️ | Implementação do banco de dados | 🚧 Em desenvolvimento |
| 🔗 | Integração entre as partes do sistema | 📌 Planejado |
| 🔐 | Implementação dos mecanismos de segurança | 📌 Planejado |
| 🧪 | Testes das funcionalidades | 📌 Planejado |
| 📝 | Atualização da documentação técnica | 🚧 Em desenvolvimento |

---

# ⚙️ Atividades da Sprint 02

## 🖥️ Desenvolvimento do Front-End

Implementação das interfaces da versão Web com base nos wireframes e mockups desenvolvidos na Sprint 01, mantendo a identidade visual e buscando oferecer uma navegação clara e intuitiva.

## ⚙️ Desenvolvimento do Back-End

Estruturação da lógica do sistema e implementação dos recursos necessários para processar informações, gerenciar usuários e atender às funcionalidades definidas nos requisitos.

## 🗄️ Implementação do Banco de Dados

Organização das tabelas, atributos, chaves e relacionamentos com base na modelagem elaborada na Sprint 01, preparando a estrutura para armazenar e consultar as informações do sistema.

## 🔗 Integração do Sistema

Integração entre as interfaces, a lógica do sistema e o banco de dados, permitindo a comunicação entre as partes conforme as funcionalidades forem implementadas.

## 🔐 Segurança e Privacidade

Consideração de mecanismos de proteção de dados, controle de acesso e permissões de usuários, levando em conta a importância da privacidade das informações tratadas pelo sistema.

## 🧪 Testes e Correções

Realização de testes das funcionalidades implementadas, identificação de problemas e correção de erros durante o desenvolvimento.

---

# 🛠️ Ferramentas

| Ferramenta | Utilização |
|:---:|:---|
| 🎨 **Figma** | Prototipação e interfaces |
| 🧠 **Miro** | Organização de ideias e planejamento |
| 🎨 **Canva** | Materiais visuais e apresentações |
| 📝 **Microsoft Word** | Documentação |
| 🗄️ **Draw.io / ferramenta de modelagem** | Modelagem inicial |
| 💻 **GitHub** | Versionamento e documentação |

---

# 📈 Evolução do Projeto

O HEMUNI será desenvolvido em **3 Sprints**, acompanhando a evolução do projeto desde o planejamento até a implementação e validação da solução.

                            🩸 HEMUNI
                               │
                 ┌─────────────┼─────────────┐
                 ▼             ▼             ▼
            🔴 SPRINT 01   🟠 SPRINT 02   🔴 SPRINT 03
              PLANEJAR      DESENVOLVER     FINALIZAR
                 │             │             │
                 ▼             ▼             ▼
            Identidade     Front-End       Testes
            Requisitos     Back-End        Correções
            MER / DER      Banco           Segurança
            Wireframes     Integração      Resultados

---

# 🎯 Próximos Passos

Após a etapa inicial de desenvolvimento da Sprint 02, o projeto seguirá para a continuidade da implementação, integração e validação das funcionalidades, conforme o planejamento da equipe.

> **Transformar os modelos e protótipos definidos na Sprint 01 em funcionalidades reais e avançar na construção do HEMUNI Web.**

### 🚧 Sprint 03

- 🖥️ Finalização das interfaces;
- ⚙️ Conclusão das funcionalidades do Back-End;
- 🗄️ Revisão e integração do banco de dados;
- 🔗 Integração dos componentes do sistema;
- 🔐 Revisão dos mecanismos de segurança;
- 🧪 Testes e correções;
- 📋 Validação das funcionalidades;
- 📝 Finalização da documentação técnica.

---

# 👥 Equipe

<div align="center">

## 🩸 HEMUNI — TCC

**Técnico em Desenvolvimento de Sistemas — SENAI**

<br>

| Integrante | Função |
|:---:|:---:|
| Ana | Scrum Master |
| Gabrielly | P.O |
| Giovanna | Desenvolvedora |
| João Pedro | Desenvolvedor |
| Júlia | Desenvolvedora |

</div>

---

# ❤️ Por que HEMUNI?

A tecnologia pode facilitar o acesso à informação e aproximar pessoas e instituições.

O HEMUNI nasce com a proposta de utilizar a tecnologia como uma ferramenta de conexão dentro do processo de doação de sangue.

<div align="center">

## 🩸 Informação conecta.
## 🤝 Pessoas colaboram.
## ❤️ Doações ajudam a salvar vidas.

<br>

# HEMUNI

### Conectando para transformar.

<br>

[![GitHub](https://img.shields.io/badge/GitHub-HEMUNI-141414?style=for-the-badge&logo=github)](.)
[![Sprint 01](https://img.shields.io/badge/Sprint%2001-970000?style=for-the-badge)](.)
[![Sprint 02](https://img.shields.io/badge/Sprint%2002-AE0202?style=for-the-badge)](.)
[![TCC SENAI](https://img.shields.io/badge/TCC-SENAI-AE0202?style=for-the-badge)](.)

<br>

<sub>Projeto acadêmico desenvolvido como Trabalho de Conclusão de Curso • 2026</sub>

<br>

**Protótipo no Figma/Drive:** [Acessar protótipo](https://drive.google.com/file/d/10H4seZaWsp8mk5QeaPwFCCczM-OAYFzU/view?usp=drive_link)

</div>
