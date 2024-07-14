# 🎯 Casos de uso
## Caso de Uso 1: Cadastro com CPF, Email e Senha
Nome: Cadastro com CPF, Email e Senha

Atores: Usuário

Objetivo: Permitir que novos usuários se registrem no sistema.

Pré-condições: Nenhuma.

Pós-condições: Um novo usuário é registrado no sistema.

Fluxo Principal:
- 1 - O usuário acessa a página de cadastro.
- 2 - O sistema exibe o formulário de cadastro.
- 3 - O usuário insere seu CPF, email e senha.
- 4 - O usuário clica no botão "Registrar".
- 5 - O sistema valida os dados fornecidos.
- 6 - Se os dados forem válidos, o sistema registra o usuário.
- 7 - O sistema exibe uma mensagem de sucesso e redireciona o usuário para a página de login.

Fluxo Alternativo:
- 6a - Se os dados forem inválidos ou se o CPF ou email já estiverem cadastrados, o sistema exibe uma mensagem de erro.
- 7a - O usuário corrige os dados e tenta novamente.
#### UML
![UML1](https://github.com/user-attachments/assets/d7b73001-0ca7-4d0a-9bbb-ca6d56f7b624)

## Caso de Uso 2: Login com CPF e Senha
Nome: Login com CPF e Senha

Atores: Usuário

Objetivo: Permitir que o usuário acesse o sistema usando suas credenciais (CPF e senha).

Pré-condições: O usuário deve estar registrado no sistema.

Pós-condições: O usuário é autenticado e redirecionado para a tela principal do sistema.

Fluxo Principal:
- 1 - O usuário acessa a página de login.
- 2 - O sistema exibe o formulário de login.
- 3 - O usuário insere seu CPF e senha.
- 4 - O usuário clica no botão "Login".
- 5 - O sistema valida as credenciais fornecidas.
- 6 - Se as credenciais forem válidas, o sistema autentica o usuário.
- 7 - O usuário é redirecionado para a tela principal do sistema.

Fluxo Alternativo:
- 6a - Se as credenciais forem inválidas, o sistema exibe uma mensagem de erro.
- 7a - O usuário é solicitado a inserir novamente suas credenciais.

#### UML
![UML2](https://github.com/user-attachments/assets/09da9b2d-ed22-44e9-ab92-a2a18a4de18e)

## Caso de Uso 3: Cadastrar Categoria de Gasto ou de Renda
Nome: Cadastrar Categoria de Gasto ou de Renda

Atores: Usuário

Objetivo: Permitir que o usuário cadastre uma nova categoria de gasto ou de renda.

Pré-condições: O usuário deve estar autenticado no sistema.

Pós-condições: A nova categoria de gasto ou de renda é adicionada ao sistema.

Fluxo Principal:
- 1 - O usuário acessa a tab de categorias.
- 2 - O sistema exibe a lista de categorias existentes e um botão para adicionar uma nova categoria.
- 3 - O usuário clica no botão "Adicionar Categoria".
- 4 - O sistema exibe o formulário de cadastro de categoria.
- 5 - O usuário insere o nome da categoria, uma descrição e seleciona se é de entrada ou de saída.
- 6 - O usuário clica no botão "Salvar".
- 7 - O sistema valida os dados e salva a nova categoria.
- 8 - O sistema exibe a lista de categorias atualizada.

Fluxo Alternativo:
- 7a - Se os dados forem inválidos, o sistema exibe uma mensagem de erro.
- 7b - O usuário corrige os dados e tenta novamente.

#### UML
![UML3](https://github.com/user-attachments/assets/7134b38c-2aa7-4cf8-97e6-8b36849b9f76)

## Caso de Uso 4: Cadastrar Gasto
Nome: Cadastrar Gasto

Atores: Usuário

Objetivo: Permitir que o usuário registre um novo gasto.

Pré-condições: O usuário deve estar autenticado no sistema e deve haver pelo menos uma categoria de gasto cadastrada.

Pós-condições: O novo gasto é adicionado ao sistema.

Fluxo Principal:
- 1 - O usuário acessa a tab de gastos.
- 2 - O sistema exibe a lista de gastos existentes e um botão para adicionar um novo gasto.
- 3 - O usuário clica no botão "Adicionar Gasto".
- 4 - O sistema exibe o formulário de cadastro de gasto.
- 5 - O usuário insere os detalhes do gasto (valor, data, descrição) e seleciona a categoria de gasto.
- 6 - O usuário clica no botão "Salvar".
- 7 - O sistema valida os dados e salva o novo gasto.
- 8 - O sistema exibe a lista de gastos atualizada.

Fluxo Alternativo:
- 7a - Se os dados forem inválidos, o sistema exibe uma mensagem de erro.
- 7b - O usuário corrige os dados e tenta novamente.

#### UML
![UML4](https://github.com/user-attachments/assets/f8d06dc0-9cd1-483f-8d0c-ea28ec9dec98)

## Caso de Uso 5: Cadastrar Renda
Nome: Cadastrar Renda

Atores: Usuário

Objetivo: Permitir que o usuário registre uma nova renda.

Pré-condições: O usuário deve estar autenticado no sistema e deve haver pelo menos uma categoria de renda cadastrada.

Pós-condições: A nova renda é adicionada ao sistema.

Fluxo Principal:
- 1 - O usuário acessa a tab de rendas.
- 2 - O sistema exibe a lista de rendas existentes e um botão para adicionar uma nova renda.
- 3 - O usuário clica no botão "Adicionar Renda".
- 4 - O sistema exibe o formulário de cadastro de renda.
- 5 - O usuário insere os detalhes da renda (valor, data, descrição) e seleciona a categoria de renda.
- 6 - O usuário clica no botão "Salvar".
- 7 - O sistema valida os dados e salva a nova renda.
- 8 - O sistema exibe a lista de rendas atualizada.

Fluxo Alternativo:
- 7a - Se os dados forem inválidos, o sistema exibe uma mensagem de erro.
- 7b - O usuário corrige os dados e tenta novamente.

#### UML
![UML5](https://github.com/user-attachments/assets/e6ddeb8e-2bc4-4090-9a67-5066d9085707)

## Caso de Uso 6: Comparar Renda com Gasto no Gráfico
Nome: Comparar Renda com Gasto no Gráfico

Atores: Usuário

Objetivo: Permitir que o usuário visualize um gráfico comparando a renda com os gastos.

Pré-condições: O usuário deve estar autenticado no sistema e deve haver dados de renda e de gastos cadastrados.

Pós-condições: O gráfico é exibido com a comparação de renda e gastos.

Fluxo Principal:
- 1 - O usuário acessa a tela de gráficos.
- 2 - O sistema exibe um gráfico comparando a renda com os gastos.
- 3 - O usuário analisa a comparação e toma decisões com base nas informações apresentadas.

Fluxo Alternativo:
- 2a - Se não houver dados suficientes, o sistema exibe o gráfic com os dados zerados.

#### UML
![UML6](https://github.com/user-attachments/assets/bbdea419-8417-43dd-a33c-69a653a3cb56)

## Caso de Uso 7: Excluir Conta do Usuário
Nome: Excluir Conta do Usuário

Atores: Usuário

Objetivo: Permitir que o usuário exclua sua conta do sistema.

Pré-condições:
- O usuário deve estar autenticado no sistema.
- O usuário deve confirmar a exclusão da conta.

Pós-condições: A conta do usuário é permanentemente removida do sistema.

Fluxo Principal:

- 1 - O usuário acessa as configurações da conta.
- 2 - O sistema exibe a opção para exclusão da conta.
- 3 - O usuário confirma a exclusão da conta.
- 4 - O sistema realiza a exclusão da conta e todos os dados associados.

Fluxo Alternativo:
- 3a - O usuário decide não prosseguir com a exclusão da conta, cancelando a operação.

Regras de Exceção:
- Se a conta do usuário não puder ser excluída por alguma razão específica (por exemplo, existência de transações pendentes), o sistema deve informar ao usuário e impedir a exclusão.

#### UML
![UML7](https://github.com/user-attachments/assets/e785602e-7877-40c4-bcb9-e1d696ffc199)

## Caso de Uso 8: Alterar Categoria de Gasto ou de Renda
Nome: Alterar Categoria de Gasto ou de Renda

Atores: Usuário

Objetivo: Permitir que o usuário modifique uma categoria de gasto ou renda existente.

Pré-condições: 
- O usuário deve estar autenticado no sistema.
- Deve haver categorias de gasto ou renda existentes para modificar.

Pós-condições: A categoria de gasto ou renda é modificada conforme as alterações feitas pelo usuário.

Fluxo Principal:

- 1 - O usuário acessa a lista de categorias de gasto ou renda.
- 2 - O sistema exibe opções para modificar cada categoria.
- 3 - O usuário seleciona uma categoria para modificar.
- 4 - O sistema permite que o usuário altere os detalhes da categoria (nome, descrição, tipo).
- 5 - O usuário salva as alterações feitas na categoria.
- 6 - O sistema exibe a lista de categorias atualizada com as modificações.

Fluxo Alternativo:
- 3a - Se o usuário decide não modificar a categoria, ele cancela a operação.

Regras de Exceção:
- Se a categoria não puder ser modificada por alguma restrição específica (por exemplo, uso em transações existentes), o sistema deve informar ao usuário e impedir a operação.

#### UML
![UML8](https://github.com/user-attachments/assets/a5bd8c9d-e724-4585-a1b7-610b125f8f64)

Caso de Uso 9: Deletar Categoria de Gasto ou de Renda
Nome: Deletar Categoria de Gasto ou de Renda

Atores: Usuário

Objetivo: Permitir que o usuário exclua uma categoria de gasto ou renda existente.

Pré-condições: O usuário deve estar autenticado no sistema. Deve haver categorias de gasto ou renda existentes para excluir.

Pós-condições: A categoria de gasto ou renda é removida permanentemente do sistema.

Fluxo Principal:

- 1 - O usuário acessa a lista de categorias de gasto ou renda.
- 2 - O sistema exibe opções para excluir cada categoria.
- 3 - O usuário seleciona uma categoria para excluir.
- 4 - O sistema solicita confirmação para a exclusão da categoria.
- 5 - O usuário confirma a exclusão da categoria.
- 5 - O sistema remove a categoria selecionada da lista.

Fluxo Alternativo:
- 3a - Se o usuário decide não excluir a categoria, ele cancela a operação.

Regras de Exceção:
- Se a categoria não puder ser excluída por alguma restrição específica (por exemplo, uso em transações existentes), o sistema deve informar ao usuário e impedir a operação.

#### UML
![UML9](https://github.com/user-attachments/assets/58fca7e8-ba6e-45cb-b954-76b1cf7860ac)

## Caso de Uso 10: Alterar um Gasto
Nome: Alterar um Gasto

Atores: Usuário

Objetivo: Permitir que o usuário modifique um gasto registrado.

Pré-condições:
- O usuário deve estar autenticado no sistema.
- Deve haver pelo menos um gasto registrado para modificar.

Pós-condições: O gasto é atualizado conforme as alterações feitas pelo usuário.

Fluxo Principal:

- 1 - O usuário acessa a lista de gastos registrados.
- 2 - O sistema exibe opções para modificar cada gasto.
- 3 - O usuário seleciona um gasto para modificar.
- 4 - O sistema permite que o usuário altere os detalhes do gasto (valor, data, descrição, categoria).
- 5 - O usuário salva as alterações feitas no gasto.
- 6 - O sistema exibe a lista de gastos atualizada com as modificações.

Fluxo Alternativo:
- 3a - Se o usuário decide não modificar o gasto, ele cancela a operação.

Regras de Exceção:
- Se o gasto não puder ser modificado por alguma restrição específica (por exemplo, já foi reconciliado em um relatório financeiro), o sistema deve informar ao usuário e impedir a operação.

#### UML
![UML10](https://github.com/user-attachments/assets/90db4e20-a077-42ba-a237-fab94c6562c1)

## Caso de Uso 11: Deletar um Gasto
Nome: Deletar um Gasto

Atores: Usuário

Objetivo: Permitir que o usuário exclua um gasto registrado.

Pré-condições:
- O usuário deve estar autenticado no sistema.
- Deve haver pelo menos um gasto registrado para excluir.

Pós-condições: O gasto é removido permanentemente do sistema.

Fluxo Principal:
- 1 - O usuário acessa a lista de gastos registrados.
- 2 - O sistema exibe opções para excluir cada gasto.
- 3 - O usuário seleciona um gasto para excluir.
- 4 - O sistema solicita confirmação para a exclusão do gasto.
- 5 - O usuário confirma a exclusão do gasto.
- 6 - O sistema remove o gasto selecionado da lista.

Fluxo Alternativo:
- 3a - Se o usuário decide não excluir o gasto, ele cancela a operação.

Regras de Exceção:
- Se o gasto não puder ser excluído por alguma restrição específica (por exemplo, já foi reconciliado em um relatório financeiro), o sistema deve informar ao usuário e impedir a operação.

#### UML
![UML11](https://github.com/user-attachments/assets/a9f362b3-4177-49ea-a1dc-ac07296c4a7a)

## Caso de Uso 12: Alterar uma Renda
Nome: Alterar uma Renda

Atores: Usuário

Objetivo: Permitir que o usuário modifique uma renda registrada.

Pré-condições:
- O usuário deve estar autenticado no sistema.
- Deve haver pelo menos uma renda registrada para modificar.

Pós-condições: A renda é atualizada conforme as alterações feitas pelo usuário.

Fluxo Principal:
- 1 - O usuário acessa a lista de rendas registradas.
- 2 - O sistema exibe opções para modificar cada renda.
- 3 - O usuário seleciona uma renda para modificar.
- 4 - O sistema permite que o usuário altere os detalhes da renda (valor, data, descrição, categoria).
- 5 - O usuário salva as alterações feitas na renda.
- 6 - O sistema exibe a lista de rendas atualizada com as modificações.

Fluxo Alternativo:
- 3a - Se o usuário decide não modificar a renda, ele cancela a operação.

Regras de Exceção:
- Se a renda não puder ser modificada por alguma restrição específica (por exemplo, já foi utilizada em cálculos de saldo), o sistema deve informar ao usuário e impedir a operação.

#### UML
![UML12](https://github.com/user-attachments/assets/01b69e4e-d2b8-4691-a744-e90735ebe147)

## Caso de Uso 13: Deletar uma Renda
Nome: Deletar uma Renda

Atores: Usuário

Objetivo: Permitir que o usuário exclua uma renda registrada.

Pré-condições:
- O usuário deve estar autenticado no sistema.
- Deve haver pelo menos uma renda registrada para excluir.

Pós-condições: A renda é removida permanentemente do sistema.

Fluxo Principal:
- 1 - O usuário acessa a lista de rendas registradas.
- 2 - O sistema exibe opções para excluir cada renda.
- 3 - O usuário seleciona uma renda para excluir.
- 4 - O sistema solicita confirmação para a exclusão da renda.
- 5 - O usuário confirma a exclusão da renda.
- 6 - O sistema remove a renda selecionada da lista.

Fluxo Alternativo:
- 3a - Se o usuário decide não excluir a renda, ele cancela a operação.

Regras de Exceção:
- Se a renda não puder ser excluída por alguma restrição específica (por exemplo, já foi utilizada em cálculos de saldo), o sistema deve informar ao usuário e impedir a operação.

#### UML
![UML13](https://github.com/user-attachments/assets/c6e1f696-8a4a-4079-a62e-d916be0eef38)
