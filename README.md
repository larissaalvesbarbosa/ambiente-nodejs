# ambiente-nodejs


# Guia Prático: Do GitHub ao Google Classroom 🚀

Olá! Este tutorial vai te ensinar a preparar seu ambiente de trabalho e manter seu código seguro no GitHub. Siga cada passo com atenção.

---

## 1. Criando sua "Pasta na Nuvem" (Repositório)

O primeiro passo é preparar o lugar onde seu projeto vai morar na internet.

1. No seu **GitHub**, clique no botão ➕ **New Repository** (Novo Repositório).
2. **Nome do repositório:** Escolha um nome simples (evite espaços e acentos).
3. **Visibilidade:** Mantenha como **Public**.
4. **Arquivos Iniciais (Muito Importante):**
    - Marque **Add a README.md** (será o rosto do seu projeto).
    - Em **Add .gitignore**, procure e selecione **Nextjs**. Isso evita que arquivos desnecessários "sujem" seu repositório.
5. Clique em **Create repository**.
6. **Copie o Link:** Clique no botão verde **<> Code** e copie o endereço que começa com `https://`.

---

## 2. Trazendo o Projeto para o seu Computador

Agora vamos "baixar" essa pasta para você poder trabalhar nela.

1. Use o atalho `Windows + R`, digite `cmd` e dê **Enter**.
2. **Entre na sua pasta de estudos:**
    
    ```bash
    cd projetos
    ```
    
3. **Faça o clone:** Digite o comando abaixo e cole o link que você copiou:
    
    ```bash
    git clone https://github.com/seunome/nome-do-repositorio.git
    ```
    
4. **Entre na pasta criada:**
    
    ```bash
    cd nome-do-repositorio
    ```
    
5. **Abra o editor VS Code:**
    
    ```bash
    code .
    ```
    

---

## 3. Ciclo de Trabalho (Salvar e Enviar)

No VS Code, abra o terminal com `Ctrl + Shift + '`. Sempre que terminar uma tarefa, faça esse "ritual" para não perder seu progresso:

| Comando | O que ele faz? |
| --- | --- |
| `git status` | Lista o que você mudou no código. |
| `git add .` | Prepara todos os arquivos para serem salvos. |
| `git status` | Verifica se os arquivos ficaram **verdes** (prontos). |
| `git commit -m "texto"` | Cria um "ponto de restauração" com uma legenda. |
| `git push origin main` | Envia tudo definitivamente para o GitHub. |

> **Dica:** Use mensagens de commit claras, como: *"Criando a estrutura da página"* ou *"Finalizando exercício 01"*.
> 

---

## 4. Entregando a Atividade

Não esqueça de avisar o professor que você terminou!

1. Vá ao navegador e **copie o link** da página principal do seu repositório.
2. Abra o **Google Classroom** na atividade correspondente.
3. Clique em **Adicionar ou criar** e escolha a opção **Link**.
4. Cole o link do GitHub e clique em **Entregar**.

---

✅ **Tarefa concluída com sucesso!**