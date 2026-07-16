# **visual_novel**
Projeto de visual novel

# **estrutura de pastas**
```
visual_novel/
│
├── game/                   # Pasta principal do jogo
│   ├── audio/               
│   │   ├── music/          # músicas de fundo
│   │   └── sfx/            # Efeitos sonoros
│   │
│   ├── gui/                # Interface gráfica (menus, caixas de diálogo, botões)
│   │   └── screens.rpy     # Código de definição da interface
│   │
│   ├── images/             # Todos os elementos visuais
│   │   ├── backgrounds/    # Cenários (CGs, locais)
│   │   ├── characters/     # Sprites (rostos, poses e expressões)
│   │   ├── items/          # Ícones e ilustrações de inventário
│   │   └── ui/             # Elementos para a tela (molduras, barras)
│   │
│   ├── scripts/            # Roteiros do jogo
│   │
│   └── cache/              # Arquivos temporários gerados pelo motor
│
├── .gitignore              # Arquivos que devem ser ignorados pelo controle de versão
├── README.md               # Documentação básica do seu projeto
└── LICENSE                 # Licença do seu jogo
```
# **Pardrão de commits**
```
feat: adiciona seção hero
fix: corrige responsividade da navbar
style: ajusta espaçamentos
refactor: reorganiza componente card
```