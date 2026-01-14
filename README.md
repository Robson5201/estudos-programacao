# 🚀 Meu Plano de Estudos e Projetos

Este repositório serve para organizar os conceitos de Git que aprendi e listar ideias de projetos para praticar C++ e JavaScript.

---

## 🛠️ Comandos Git que Aprendi

### Alterar Mensagens de Commit (Rebase)
* `git rebase -i HEAD~n`: Abre o editor para os últimos `n` commits.
* No editor, mude `pick` para `reword` no commit que deseja renomear.

### Comparar Local vs. GitHub
1. `git fetch origin`: Atualiza as referências do servidor.
2. `git diff main origin/main`: Mostra a diferença de código.
3. `git log main..origin/main`: Mostra commits que estão no GitHub mas não na minha máquina.

### Deletar Commits (Reset e Rebase)
* **Reset (Últimos commits):**
    * `git reset --soft HEAD~1`: Deleta o commit mas mantém o código.
    * `git reset --hard HEAD~1`: Deleta tudo (cuidado!).
* **Rebase (Commits do meio da história):**
    * `git rebase -i HEAD~n` e mude `pick` para `drop` na linha do commit.

---

## 💡 Ideias de Projetos para Praticar

### 🟢 Iniciante (Foco em Lógica)
- [ ] **Conversor de Bases (JS):** Criar uma página que converte Decimal para Binário/Hexadecimal.
- [ ] **Batalha de RPG (C++):** Jogo simples via terminal com sistema de vida e ataque por turnos.
- [ ] **Simulador de Caixa Eletrônico:** Treinar controle de saldo, saques e depósitos.

### 🟡 Intermediário (Foco em APIs e Web)
- [ ] **App de Clima:** Consumir uma API de meteorologia com JavaScript.
- [ ] **Dashboard de Recursos:** Usar C++ para ler dados do sistema e JS para mostrar em gráficos.
- [ ] **Filtro de Imagem com WebAssembly:** Usar a performance do C++ para processar imagens no navegador.

---

> "O segredo de progredir é começar."