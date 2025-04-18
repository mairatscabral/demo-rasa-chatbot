
# 🤖 demo-rasa-chatbot

Este é um projeto de exemplo de chatbot usando o [Rasa](https://rasa.com/), criado para fins educacionais e faz parte do curso Trilha para ELAS – Introdução à Inteligência Artificial oferecido pelo TIC em Trilhas.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mairatscabral/demo-rasa-chatbot/HEAD)

Clique no badge acima para abrir o projeto no **Binder**.

## 🚀 Instruções para rodar o chatbot no Binder

1. Após o ambiente carregar, clique em **"Terminal"** no menu superior.

2. Instale o Rasa com o comando:

   ```bash
   pip install rasa
   ```

3. Inicialize o projeto com:

   ```bash
   rasa init
   ```

   - Pressione `Enter` para aceitar o diretório atual como destino do projeto.
   - Quando aparecer a pergunta "`Directory '/home/jovyan' is not empty. Continue? (Y/n)`", digite `y` e pressione `Enter`.
   - Quando perguntado "`Do you want to train an initial model? 💪🏽 (Y/n)`", digite `n` e pressione `Enter`.

4. Comprima os arquivos criados com o comando:

   ```bash
   tar -czvf projetorasa.tar.gz *
   ```

## ✏️ Edição dos Arquivos

Edite os arquivos `domain.yml`, `config.yml`, `nlu.yml`, `rules.yml`, `stories.yml` e `tests.yml` de acordo com o comportamento desejado do chatbot.

## 🧠 Treinamento e Execução

Após editar os arquivos, treine o modelo com:

```bash
rasa train
```

Para testar seu chatbot no terminal, use:

```bash
rasa shell
```

---

Criado com ❤️ por [Maíra Cabral](https://github.com/mairatscabral)
