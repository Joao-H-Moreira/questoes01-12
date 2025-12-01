# 📝 **Exercícios – Revisão de Python **

---

## **1. Cadastro de Alunos (Completo)**

Crie um programa que:

1. Peça ao usuário o nome, idade e uma lista de notas (separadas por vírgula).
2. Armazene tudo em um **dicionário**.
3. Use uma **função** para calcular a média.
4. Salve o resultado em um **arquivo** chamado `aluno.txt`.
5. Use uma **condicional** para dizer se o aluno está aprovado (média ≥ 7).
6. Use **tupla** para armazenar os nomes das matérias (ex.: `("Matemática", "Português")`).
7. Use **set** para remover notas repetidas antes de calcular a média.

---

## **2. Verificando Presença em um Evento**

Crie uma lista com 5 nomes. Depois:

1. Peça uma **entrada** de nome ao usuário.
2. Converta para **set** a lista para remover duplicatas.
3. Use um `if` para verificar se o nome está presente.
4. Use um `for` para mostrar todos os nomes no evento.
5. Crie uma função chamada `adicionar_nome` que adiciona o nome na lista **somente se ele não existir**.
6. Salve a lista final em um arquivo `presenca.txt`.

---

## **3. Sistema de Estoque Simples**

1. Crie um **dicionário** onde a chave é o nome do produto e o valor é a quantidade.
2. Peça ao usuário para digitar um produto e quantidade.
3. Use uma **função** que atualize o estoque.
4. Se o produto não existir, adicione. Caso contrário, incremente.
5. Use `while` para permitir várias inserções até o usuário digitar `"sair"`.
6. Mostre ao final os produtos em ordem alfabética (use `sorted` do módulo `builtins`).
7. Salve o dicionário em um arquivo `estoque.txt`.

---

## **4. Sistema de Login (Simples e Didático)**

Crie um programa que:

1. Armazene logins e senhas em um **dicionário**.
2. Peça ao usuário login e senha.
3. Use booleanos para indicar se o login é válido.
4. Use uma condição que:

   * Mostra "Login bem-sucedido"
   * Ou "Acesso negado"
5. Registre a tentativa de login em um arquivo `log.txt`.
6. Use uma **tupla** com os tipos de usuário: `("admin", "aluno", "visitante")`.
7. Leia quantas tentativas foram feitas usando um arquivo externo.

---

## **5. Analisador de Texto**

Crie um programa que:

1. Peça ao usuário um texto.
2. Transforme esse texto em uma **lista** de palavras.
3. Transforme a lista em **set** para descobrir quantas palavras diferentes existem.
4. Salve no arquivo `analise.txt`:

   * Número total de palavras
   * Número de palavras únicas
5. Use uma função `contar_palavras(texto)` para retornar estes valores.
6. Use `for` e `if` para contar quantas palavras começam com vogal.
7. Use uma **condicional** para dizer se o texto é "longo" (mais de 20 palavras).
8. Use um módulo da biblioteca (`string`) para ignorar pontuação.
