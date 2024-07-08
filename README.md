<h1 align="center">🏦 Aplicativo de Gestão de Finanças Pessoais</h1>

## 📝 Visão Geral do Projeto
> Este projeto visa desenvolver um aplicativo de gestão de finanças pessoais amigável que permite aos usuários ter um controle sobre suas despesas e ganhos mensais. O aplicativo pretende ser simples, mas robusto, oferecendo recursos como registro de usuário e resumos financeiros.
## 🛠️ Funcionalidades

#### **🔒 1. Registro e Autenticação de Usuário**
>  - Permite aos usuários se registrarem e se autenticarem usando o seu CPF e uma senha segura.
#### **💰 3. Registro de Despesas e Ganhos**
>  - Permite aos usuários registrar e categorizar suas despesas e ganhos mensais.
#### **📊 4. Painel Financeiro**
>  - Oferece uma visão abrangente da situação financeira do usuário através de um painel com informações consolidadas, gráficos e tabelas.

## 🎯 Escopo

#### 📊 1.  Coleta e Uso de Dados de Aplicações Externas

> - Dados do usuário, incluindo e-mail, nome e CPF são coletados durante o processo de registro e login. A autenticação é gerenciada via inscrição e login baseados em seu CPF.

#### 🔍 2. Processamento e Análise
> - O backend processa os dados coletados dos usuários. Ele valida a entrada, e salva em um banco relacional todas as informações solicitadas.

#### 🎨 3. Design de Interface
> - O frontend utiliza React, TypeScript, Tailwind CSS e Ant Design para implementar este design.

#### 👨‍💻 4. Desenvolvimento
> - O backend é alimentado por C# com SQL Server para persistência de dados, oferecendo gerenciamento de dados robusto. A API e o SQL são hospedados pela AWS.

> - O frontend é desenvolvido em React e TypeScript com Tailwind CSS para estilização. Ele fornece uma interface amigável para gerenciar finanças e está implantado no Vercel.

#### 🧪 5. Garantia de Qualidade
> - A garantia de qualidade é gerenciada através da implementação de testes unitários no backend utilizando xUnit para testes. O Codacy também é integrado para garantir a qualidade do código.

#### 🔄 6. CI/CD
> - O pipeline de CI/CD para o backend é gerenciado através do GitHub Actions, com testes e implantações automatizadas. O frontend usa Vercel e GitHub para integração e implantação contínuas.

#### 👀 7. Observabilidade
> - O monitoramento e a observabilidade são gerenciados através do Cloud Watch na AWS, que fornece insights em tempo real sobre o desempenho e a saúde do aplicativo.

## 🚫 Restrições
> - O aplicativo não suporta sincronização automática de dados financeiros com nenhum banco digital. Isso significa que você precisará inserir manualmente todas as suas transações, incluindo receitas e despesas, no aplicativo para usar seus recursos de gestão financeira.

> - Para manter o Aplicativo de Gestão de Finanças Pessoais operacional, o projeto usa AWS RDS para armazenamento de banco de dados. Os custos podem variar dependendo do volume de solicitações e das necessidades de armazenamento de dados a cada mês. É crucial orçar os custos do AWS RDS para garantir que o aplicativo permaneça disponível e opere de forma otimizada.


## ⚖️ Trade-offs
### 📱 1. Portabilidade
> - O Aplicativo de Gestão de Finanças Pessoais é principalmente uma aplicação web otimizada para uso em desktop, potencialmente limitando sua acessibilidade em dispositivos móveis ou em cenários offline.

> - Consideração: Embora ser baseado na web forneça uma interface robusta para tarefas financeiras complexas, os usuários que são mais centrados em dispositivos móveis podem achar menos conveniente.

### 🛠️ 2. Funcionalidade
> - O aplicativo oferece uma cadastro de suas despesas e faturamentos e um grafico sobre suas movimentações.

> - Consideração: Embora um conjunto extenso de recursos torne o aplicativo versátil, ele também pode aumentar sua complexidade, potencialmente confundindo os usuários que procuram uma experiência simplificada.

### 🖱️ 3. Usabilidade
> - O design, feito em React e TypeScript com Tailwind CSS, visa oferecer uma experiência intuitiva e visualmente agradável, mas pode não atender a todas as preferências dos usuários.

> - Consideração: Padrões elevados de usabilidade são essenciais para a retenção de usuários, mas escolhas estéticas e de navegação podem não agradar a todos.

### ⏱️ 4. Eficiência
> - Como a API esta sendo hosteada em uma Lambda da AWS, temos um pequeno atraso na primeira requisição relizada, devido ao cold start, porém logo após este periodo seu desempenho deve melhorar.

> - Consideração : Ao optar entre um ECS e uma Lambda na aws, acabei optando pela lambda por causa de Custo, uma vez em que a Lambda irá gerar custos pelo tempo de execução. 

### 🛠️ 5. Manutenibilidade
> - O backend em C# e SQL Server, juntamente com o frontend em React e TypeScript, requer manutenção contínua para segurança, correções de bugs e novos recursos, o que pode ser intensivo em recursos.

> - Consideração: A manutenibilidade garante a longevidade e a segurança do aplicativo, mas pode desviar recursos do desenvolvimento de novos recursos ou outros aspectos do projeto.

## 📚 Links Rápidos
> - 🏗️ [C4 Model](/docs/C4Model/c4-models.md)
> - 🎯 [Use Case](/docs/UseCases/use-cases.md)
> - ✅ [Requirements](/docs/Requirements/requirements.md)

## 💻 Tech Stack
> - **Front-end:** React, TailwindCSS
> - **Back-end:** .NET Core 6.0
> - **Database:** SQLServer
> - **Quality:** Codacy
> - **Other Tools:** AWS RDS, AWS Lambda, Vercel, AWS Cloud Watch

## 🌐 Repositories URLs
> - **Backend: [Backend Repository URL](https://github.com/VitorRoecker/expense-control-portfolio-backend)**
> - **Frontend: [Frontend Repository URL](https://github.com/VitorRoecker/expense-control-portfolio-frontend)**
