## ✅ Requisitos Funcionais

**1. Cadastro de Usuário**
  > - Permitir que novos usuários se registrem no sistema com CPF, email e senha.

**2. Login de Usuário:**
  > - Autenticar usuários através de CPF e senha para acessar o sistema.

**3. Gerenciamento de Categorias**
  > - Permitir o cadastro, alteração e exclusão de categorias de gastos e rendas.
  > - Categorias devem ter nome, tipo (gasto ou renda) e possivelmente uma descrição.

**4. Gerenciamento de Gastos**
  > - Permitir o cadastro, alteração e exclusão de gastos associados a categorias previamente cadastradas.
  > - Gastos devem ter valor, data, descrição e categoria associada

**5. Gerenciamento de Rendas**
  > - Permitir o cadastro, alteração e exclusão de rendas associadas a categorias previamente cadastradas.
  > - Rendas devem ter valor, data, descrição e categoria associada

**6. Comparação de Renda e Gasto**
  > - Exibir um gráfico que compare o total de renda com o total de gastos em um determinado período de tempo.

**7. Exclusão de Conta de Usuário**
  > - Permitir que o usuário exclua sua conta, o que implica na exclusão de todos os dados associados a ela, como gastos, rendas e categorias.

## 🛡️ Requisitos Não Funcionais

**1. Desempenho**
  > - O backend foi desenvolvido para operar com tarefas assíncronas, garantindo um bom desempenho mesmo sob carga alta de operações.
  > - A hospedagem na AWS Lambda ajuda na escalabilidade do sistema, permitindo lidar com aumentos repentinos de tráfego sem comprometer o desempenho.
  
**2. Segurança**
  > - Utilizar o hash do Identity para criptografar as senhas dos usuários, garantindo a segurança das informações de login.

**3. Interface Usuário**
  > - A interface deve ser simples e fácil de usar, com apenas três tabs (Categoria, Gasto e Renda), e uma opção no canto superior direito para ir para tela de gráfico.
  > - Mensagens de erro são tratadas e exibidas em um toast, melhorando a usabilidade ao fornecer feedback imediato ao usuário.

**4. Manutenabilidade**
  > - O código do backend foi desenvolvido de forma autoexplicativa, com métodos e propriedades bem nomeados, facilitando a manutenção e evolução do sistema.
