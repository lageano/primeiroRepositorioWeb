# Como Subir o Projeto para o GitHub

Olá! Preparei todo o projeto conforme a atividade solicitada. A pasta `primeiroRepositorioWeb` contém um repositório Git completo com o histórico de commits e as branches `main` e `feature01`.

Siga estes passos para criar um novo repositório no seu GitHub e enviar o projeto para ele.

---

### Passo 1: Criar um Novo Repositório no GitHub

1.  Acesse sua conta no [GitHub](https://github.com).
2.  No canto superior direito, clique no ícone de `+` e depois em **New repository**.
3.  Preencha as informações do novo repositório:
    *   **Repository name:** `primeiroRepositorioWeb` (ou outro nome que preferir).
    *   **Description:** `Repositório para treino GIT - Dev WEB` (sugestão).
    *   Deixe o repositório como **Public** (Público).
    *   **NÃO** marque nenhuma das opções: "Add a README file", "Add .gitignore" ou "Choose a license". O projeto que preparei já inclui tudo isso.
4.  Clique no botão **Create repository**.

### Passo 2: Conectar seu Repositório Local ao Remoto

Após criar o repositório, o GitHub mostrará uma página com alguns comandos. Você usará os comandos da seção **"…or push an existing repository from the command line"**.

1.  Abra o terminal ou prompt de comando no seu computador.
2.  Navegue até a pasta `primeiroRepositorioWeb` que você baixou.
3.  Copie e cole os seguintes comandos, um de cada vez, pressionando Enter após cada um. **Substitua a URL** pela URL do seu repositório, que você encontrará na página do GitHub.

```bash
# 1. Conecta o repositório local ao seu repositório remoto no GitHub
git remote add origin https://github.com/SEU-USUARIO/primeiroRepositorioWeb.git

# 2. Verifica se a conexão foi feita com sucesso
git remote -v
```

### Passo 3: Enviar o Projeto (Branches e Commits)

Agora que o repositório local está conectado ao remoto, vamos enviar todo o conteúdo, incluindo as duas branches (`main` e `feature01`).

1.  Use o comando a seguir para enviar **todas as branches** e o histórico de commits para o GitHub.

```bash
# Envia todas as branches para o repositório remoto chamado 'origin'
git push --all origin
```

2.  Opcionalmente, você pode enviar as tags (se houver) com o comando:

```bash
git push --tags origin
```

### Passo 4: Verificar no GitHub

Pronto! Após executar os comandos, atualize a página do seu repositório no GitHub. Você verá todos os arquivos, as duas branches (`main` e `feature01`) e o histórico de commits exatamente como foi solicitado na atividade.

Você poderá navegar entre as branches para ver que a `main` está intacta e a `feature01` contém a nova funcionalidade.

---

Qualquer dúvida, pode me perguntar!
