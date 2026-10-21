# 🖥️ Windows 95 Web Simulator

Uma recriação completa e funcional do Windows 95 utilizando apenas HTML, CSS e JavaScript vanilla. Experimente a nostalgia do sistema operacional mais icônico dos anos 90 diretamente no seu navegador!

![Windows 95](https://img.shields.io/badge/Windows-95-008080?style=for-the-badge&logo=windows95)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🌟 Demonstração

🔗 **[Acesse a demo ao vivo](https://fernando-silvano.github.io/)**

## ✨ Características

### 🎮 Interface Autêntica
- **Desktop funcional** com ícones clicáveis
- **Barra de tarefas** com relógio em tempo real
- **Menu Iniciar** com efeitos hover e gradiente original
- **Janelas arrastáveis** com controles de minimizar, maximizar e fechar
- **Estilo visual 100% fiel** ao Windows 95 original

### 🚀 Sequência de Boot Realista
- **Tela de Power Off** com botão de ligar interativo
- **BIOS Phoenix-AwardBIOS** com logo Energy Star e erros realistas
  - Pressione **F2** durante a BIOS para entrar no Setup
  - BIOS Setup navegável com configurações fictícias
- **Tela de carregamento** do Windows 95 com barra de progresso
- **Tela de login** com autenticação
  - Usuário: `administrador`
  - Senha: `github`

### 💻 Programas Funcionais

#### 📁 Meu Computador
- Visualização de drives (C:, D:, A:)
- Ícones de Impressoras e Painel de Controle
- Interface autêntica de explorador

#### 📝 Bloco de Notas
- Editor de texto funcional
- Área de texto editável
- Interface clássica do Notepad

#### 🌐 Internet Explorer
- Navegador simulado
- Barra de endereços
- Botões de navegação
- Conteúdo HTML customizado

#### 💣 Campo Minado (Minesweeper)
- **Jogo completo e funcional!**
- Tabuleiro 8x8 com 10 minas
- Sistema de revelação de células
- Marcação de bandeiras com botão direito
- Contador de minas e timer
- Detecção de vitória/derrota
- Botão de reset com emoticon

#### 🗑️ Lixeira
- Visualização de lixeira vazia
- Interface autêntica

#### ℹ️ Sobre o Windows 95
- Informações do sistema
- Logo e versão

### 🔌 Sistema de Desligamento

- **Dialog de desligamento** com 4 opções:
  1. Desligar o computador
  2. Reiniciar o computador
  3. Reiniciar em modo MS-DOS
  4. Fazer logon como outro usuário
- **Tela de desligamento autêntica** com nuvens azuis e logo Windows 95
- **Animações suaves** entre estados

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura da página
- **CSS3** - Estilização autêntica do Windows 95
  - Gradients para efeitos 3D
  - Animações e transições
  - Layout responsivo
- **JavaScript Vanilla** - Lógica e interatividade
  - Sistema de janelas com z-index dinâmico
  - Drag and drop
  - Gerenciamento de eventos
  - Lógica completa do Campo Minado

## 📦 Instalação

### Deploy no GitHub Pages

1. **Fork este repositório**
2. **Vá em Settings → Pages**
3. **Em "Source", selecione a branch `main` ou `master`**
4. **Salve e aguarde alguns minutos**
5. **Acesse em**: `https://seu-usuario.github.io/nome-do-repositorio`

### Uso Local

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2. **Abra o arquivo HTML**
```bash
# Windows
start win95.html

# Linux/Mac
open win95.html
# ou
xdg-open win95.html
```

3. **Ou use um servidor local** (recomendado)
```bash
# Python 3
python -m http.server 8000

# Node.js com npx
npx serve

# Acesse: http://localhost:8000
```

## 🎯 Como Usar

### Iniciando o Sistema
1. **Clique no botão Power** na tela preta
2. **Durante a BIOS**, pressione **F2** para entrar no Setup (opcional)
3. **Aguarde** o carregamento (3 segundos)
4. **Faça login** com:
   - Usuário: `administrador`
   - Senha: `github`

### Navegação
- **Clique simples** nos ícones para selecioná-los
- **Duplo clique** nos ícones do desktop para abrir programas
- **Menu Iniciar** → Clique em "Iniciar" na barra de tarefas
- **Arraste janelas** pela barra de título (apenas janelas, não ícones)
- **Botões de controle** no canto superior direito das janelas:
  - `_` Minimizar
  - `□` Maximizar
  - `×` Fechar

### Jogando Campo Minado
- **Clique esquerdo** para revelar célula
- **Clique direito** para marcar/desmarcar bandeira
- **Objetivo**: Revelar todas as células sem minas
- **Clique no emoji** para reiniciar

### Desligando
1. **Menu Iniciar → Desligar...**
2. **Selecione uma opção**
3. **Clique em "Sim"**

## 🎨 Detalhes Técnicos

### Paleta de Cores Autêntica
- Desktop: `#008080` (Teal)
- Janelas: `#c0c0c0` (Cinza claro)
- Barra de título: Gradiente `#000080` → `#1084d0`
- Bordas 3D: `#dfdfdf` (highlight) e `#808080` (shadow)

### Ícones
- Ícones originais do Windows 98 via [win98icons.alexmeub.com](https://win98icons.alexmeub.com)
- Floppy disk com SVG inline personalizado

### Funcionalidades Técnicas
- Sistema de z-index dinâmico para gerenciamento de janelas
- Drag and drop para movimentação de janelas
- Event delegation para performance
- LocalStorage não utilizado (estado não persiste)
- Sem dependências externas
- Código vanilla puro (sem frameworks)

## 📝 Roadmap

- [ ] Ícones arrastáveis no desktop
- [ ] Adicionar sons do Windows 95
- [ ] Paint simulado
- [ ] Calculadora funcional
- [ ] More games (Solitaire, FreeCell)
- [ ] Sistema de arquivos com localStorage
- [ ] Temas customizáveis
- [ ] Modo mobile responsivo

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. **Fazer um Fork** do projeto
2. **Criar uma branch** para sua feature (`git checkout -b feature/MinhaFeature`)
3. **Commit suas mudanças** (`git commit -m 'Adiciona MinhaFeature'`)
4. **Push para a branch** (`git push origin feature/MinhaFeature`)
5. **Abrir um Pull Request**

## 📄 Licença

Este projeto é livre para uso pessoal e educacional. Windows 95 e todos os recursos relacionados são marcas registradas da Microsoft Corporation.

## 🙏 Créditos

- **Ícones**: [Windows 98 Icon Viewer](https://win98icons.alexmeub.com) por Alex Meub
- **Inspiração**: Microsoft Windows 95 (1995-2001)
- **Desenvolvido com**: ❤️ e muita nostalgia

## 📸 Screenshots

### Desktop
![Desktop](screenshots/desktop.png)

### BIOS Setup
![BIOS](screenshots/bios.png)

### Campo Minado
![Minesweeper](screenshots/minesweeper.png)

### Internet Explorer
![IE](screenshots/ie.png)

---

⭐ **Se você gostou deste projeto, deixe uma estrela!** ⭐

💾 Feito com saudades da era Dial-Up 💾
