# ⚽ Pelada dos Papangu

Sistema web moderno e completo para gerenciamento de peladas de futebol com controle de acesso (Admin/Usuário), ranking de jogadores por estrelas, aprovação de cadastros e sorteio inteligente e equilibrado de times.

---

## 🚀 Funcionalidades

### 🔐 Autenticação & Níveis de Acesso
- **Tela de Login e Cadastro**: interface intuitiva com alternância rápida entre abas.
- **Fluxo de Aprovação**: novos usuários criam suas contas e ficam em fila de espera pendente.
- **Controle de Cargos (RBAC)**:
  - 🛡️ **Administrador**: acesso total ao painel gerencial, cadastro/edição de jogadores, promoção de outros administradores e aprovação/rejeição de cadastros.
  - 👥 **Usuário Comum**: visualiza o ranking dos atletas e participa da visualização do sorteio de times.
- **Promover/Rebaixar Administradores**: promova qualquer jogador a Admin ou rebaixe para usuário comum com um clique.

### 🏆 Ranking de Jogadores
- **Classificação por Estrelas**: ranqueamento automático dos atletas de 1 a 5 estrelas (★).
- **Pódio com Destaques**: medalhas dinâmicas para o Top 3 (🥇 Ouro, 🥈 Prata, 🥉 Bronze).
- **Filtros Avançados**: busca instantânea por nome/apelido e filtro por posição em campo (*Goleiro*, *Defensor*, *Meio-campo*, *Atacante*).
- **Identificação Visual**: avatar customizável (foto ou iniciais) e badges coloridas por posição.

### 🎲 Sorteio Inteligente de Times
- **Configuração Flexível**: escolha o número de times (2 a 6) e o número de jogadores por equipe.
- **Seleção de Presença**: marque facilmente apenas os atletas presentes no dia do jogo (com atalhos para marcar/desmarcar todos).
- **Dois Modos de Sorteio**:
  - ⚖️ **Equilibrado (Snake Draft)**: distribui os jogadores com base nas estrelas para gerar times equilibrados e competitivos.
  - 🔀 **Aleatório**: sorteio 100% randômico entre os selecionados.
- **Média dos Times**: cálculo e exibição instantânea da média técnica (estrelas) de cada time formado.

### 🛠️ Painel Administrativo
- **Gestão de Jogadores**: adicione, edite ou remova atletas com nome, apelido, posição, foto e estrelas.
- **Gestão de Usuários**: lista completa com opções para alternar permissão (Tornar Admin / Tornar Usuário) ou excluir contas.
- **Aba de Pendentes**: aprove novos membros escolhendo diretamente se entram como Usuário ou Administrador, com contador em tempo real (*badge* vermelho).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico**: estrutura acessível e modular.
- **CSS3 Moderno**: variáveis CSS (*custom properties*), layout flexbox/grid, modo escuro (*Dark Theme*) e design responsivo para smartphones e desktops.
- **JavaScript (ES6+) Vanilla**: zero dependências externas ou frameworks pesados.
- **Web Storage API (localStorage)**: persistência de dados local no próprio navegador, sem necessidade de configurar bancos de dados ou servidores backend para começar.

---

## 📂 Estrutura de Pastas

```text
pelada_dos_papangu/
├── index.html       # Estrutura principal da aplicação (Login, Ranking, Sorteio, Admin)
├── style.css        # Folha de estilo visual, tema escuro e responsividade
├── app.js           # Lógica do app, autenticação, ranking, algoritmos de sorteio e persistência
└── README.md        # Documentação do projeto
```

---

## 💻 Como Rodar o Projeto

Como o projeto foi desenvolvido em tecnologias web puras, não é necessário instalar `node_modules` ou executar comandos de compilação.

### Opção 1: Abrir diretamente no navegador
1. Faça o clone ou baixe este repositório como ZIP:
   ```bash
   git clone https://github.com/SEU_USUARIO/pelada_dos_papangu.git
   ```
2. Acesse a pasta do projeto e dê um duplo clique no arquivo `index.html`.

### Opção 2: Extensão Live Server (VS Code)
1. Abra a pasta no **VS Code**.
2. Clique com o botão direito sobre o arquivo `index.html` e selecione **"Open with Live Server"**.

---

## 🌐 Como Publicar no GitHub Pages (Online e Grátis)

Você pode colocar este site no ar gratuitamente em menos de 1 minuto:

1. Suba este projeto para um repositório no seu GitHub.
2. No repositório, acesse a aba **Settings** (Configurações).
3. No menu lateral esquerdo, clique em **Pages**.
4. Em **Build and deployment** > **Branch**, selecione a branch `main` (ou `master`) e a pasta `/(root)`.
5. Clique em **Save**.
6. Aguarde alguns instantes e seu link estará disponível no formato:
   `https://SEU_USUARIO.github.io/pelada_dos_papangu/`

---

## 👤 Credenciais Iniciais de Administrador

O projeto já conta com o administrador configurado por padrão:

- **Usuário:** `Sidney`
- **Senha:** `caua1015`

> 💡 *Nota: Você pode criar novas contas na aba "Cadastrar-se" e aprová-las pelo painel administrativo logado com a conta acima.*

---

## 🤝 Contribuições

Contribuições, sugestões e melhorias são sempre bem-vindas! Sinta-se à vontade para abrir uma *Issue* ou enviar um *Pull Request*.

---

Desenvolvido com ⚽ para a **Pelada dos Papangu**!
