# Atividade Prática: Contribuindo para um Livro de Receitas com Fork e Pull Request

## Objetivo
Nesta atividade, você irá praticar o uso de Fork e Pull Request contribuindo para um projeto de livro de receitas online. Você irá adicionar uma nova receita ao projeto existente.

## Pré-requisitos
- Conta no GitHub
- Git instalado em sua máquina local
- Conhecimento básico de HTML

## Passos

### 1. Fork do Repositório
1. Acesse o repositório original: https://github.com/RyanOliveira00/receitas-pratica-monitoria-devops-cesupa-2024
2. No canto superior direito, clique no botão "Fork"
3. Selecione sua conta pessoal para criar o fork

### 2. Clone do seu Fork
1. No seu fork, clique no botão verde "Code"
2. Copie a URL do repositório
3. Abra o terminal e execute:
   ```
   git clone [URL_DO_SEU_FORK]
   cd receitas-pratica-monitoria-devops-cesupa-2024
   ```

### 3. Crie uma Nova Branch
```
git checkout -b adiciona-receita-[NOME_DA_SUA_RECEITA]
```

### 4. Adicione sua Receita
1. Crie um novo arquivo HTML para sua receita (ex: `minha_receita.html`)
2. Use a estrutura do arquivo `lasanha-a-bolonhesa.html` como base, mas adicione sua própria receita
3. Adicione um link para sua receita no arquivo `index.html`

### 5. Commit das Alterações
```
git add .
git commit -m "Adiciona receita de [NOME_DA_SUA_RECEITA]"
```

### 6. Push para o seu Fork
```
git push origin adiciona-receita-[NOME_DA_SUA_RECEITA]
```

### 7. Crie um Pull Request
1. Vá para a página do seu fork no GitHub
2. Clique em "Pull requests" e depois em "New pull request"
3. Selecione sua branch com as alterações
4. Clique em "Create pull request"
5. Adicione um título e descrição para o seu Pull Request
6. Clique em "Create pull request" novamente

### 8. Aguarde a Revisão
- O monitor do projeto irá revisar sua contribuição
- Se necessário, faça as alterações solicitadas
- Quando aprovado, sua receita será incorporada ao projeto principal

## Entrega
- URL do seu fork
- URL do Pull Request criado

## Avaliação
Você será avaliado com base em:
- Correta execução do processo de fork e pull request
- Seguimento das instruções e boas práticas de Git

Boa sorte e bom apetite!