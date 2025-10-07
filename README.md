# Desafio "Game Dev Challenge" 🎮

## Descrição do Projeto

Desenvolver um **MVP (Minimum Viable Product)** de um jogo original, desde a concepção até a implementação jogável. Cada grupo terá liberdade criativa para definir gênero, estilo visual, plataforma e narrativa, mas deverá entregar um produto funcional que demonstre mecânicas de gameplay e conceitos fundamentais de desenvolvimento de jogos.


## Requisitos Técnicos

### Obrigatórios
- ✅ Jogo funcional e jogável
- ✅ Versionamento no Git 
- ✅ Documento de Game Design
- ✅ README com instruções de instalação/execução


### Definições Obrigatórias do Grupo

#### 1. Estilo Visual
Escolher **UM** dos formatos:
- **2D** (Pixel Art, Vetorial, Hand-drawn, etc)
- **3D** (Low Poly, Realista, Stylized, etc)
- **2.5D** (Híbrido com elementos 3D em gameplay 2D)

#### 3. Gênero do Jogo
Definir o gênero principal (pode combinar até 2):
- Plataforma
- Puzzle
- RPG
- Ação/Aventura
- Tower Defense
- Endless Runner
- Visual Novel
- Estratégia
- Roguelike/Roguelite
- Simulação
- Survival
- Beat 'em up
- Shoot 'em up
- Card Game
- *Outros (justificar)*

## Engines e Ferramentas Sugeridas

### Game Engines (Na aula vamos ver Unity, mas podem escolher outra caso queiram)
- **Unity** (C#) 
- **Godot** (GDScript/C#) 
- **Unreal Engine** (Blueprint/C++)
- **PyGame** (Python) 

### Ferramentas de Arte
- **2D**: Aseprite, Piskel, GIMP, Krita, Photoshop
- **3D**: Blender, Maya, 3ds Max
- **UI**: Figma, Adobe XD


## Componentes Obrigatórios do MVP

### 1. Gameplay Core
- ✅ Pelo menos **1 mecânica principal** funcional
- ✅ Loop de gameplay claro (objetivo → ação → feedback)
- ✅ Hitbox bem definido
- ✅ Condição de vitória OU progressão infinita

### 2. Interface
- ✅ Menu inicial (Play, Quit)
- ✅ Tela de Game Over ou Vitória
- ✅ Instruções básicas (in-game ou menu)

### 3. Conteúdo Mínimo
- ✅ Pelo menos **1 fase/nível** completo OU
- ✅ Gameplay de **3-5 minutos** demonstrável
- ✅ Assets visuais consistentes (não misturar estilos drasticamente)
- ✅ Pelo menos 1 efeito sonoro e/ou música

### 4. Polish Básico
- ✅ Feedback visual para ações do jogador
- ✅ Transições entre telas
- ✅ Tratamento de inputs inválidos
- ✅ Sistema de pausa (se aplicável)

## Estrutura do Repositório Git

```
nome-do-jogo/
├── README.md                    # Instruções completas
├── GDD.md                       # Game Design Document
├── docs/
│   ├── concept-art/            # Arte conceitual
│   ├── screenshots/            # Capturas de tela
│   └── devlog.md              # Diário de desenvolvimento
├── src/                        # Código fonte
├── assets/
│   ├── sprites/
│   ├── sounds/
│   ├── music/
│   └── fonts/
├── builds/                     # Executáveis
└── LICENSE
```

## Game Design Document (GDD) Simplificado

Documento obrigatório em formato Markdown contendo:

### Seção 1: Visão Geral
- **Nome do Jogo**
- **Gênero**
- **Estilo Visual**
- **Público-alvo**
- **Resumo em uma frase** (elevator pitch)

### Seção 2: Storytelling
- **Premissa**: Contexto e mundo do jogo
- **Protagonista**: Quem o jogador controla
- **Objetivo**: O que o jogador precisa alcançar
- **Conflito**: Obstáculos e desafios
- **Tom Narrativo**: Sério, cômico, sombrio, etc

### Seção 3: Gameplay
- **Mecânicas Principais**: O que o jogador faz
- **Controles**: Mapeamento de inputs
- **Progressão**: Como o jogo avança
- **Vitória/Derrota**: Condições finais

# Distribuição de Notas

## Fase 1: Planejamento e Setup  (Entrega 15/10)

### Entregas Obrigatórias
1. **Repositório Git** criado e compartilhado
2. **README.md** inicial com:
   - Nome do jogo
   - Integrantes do grupo
   - Tecnologias escolhidas
3. **GDD.md** completo (versão 1.0)


### Apresentação (5-10 minutos) (Entrega 11/11)
- Pitch do jogo
- Explicação das escolhas técnicas
- Gameplay de demonstração do MVP

### Critérios de Avaliação
- Clareza da proposta 
- Qualidade do GDD 
- Organização inicial 

## Fase 2: Protótipo Jogável (25/11)

### Entregas Obrigatórias
1. **Build funcional** versão compilavel do jogo
2. **Core gameplay** implementado
3. **Código fonte completo** no Git



### Requisitos Mínimos do Protótipo
- ✅ Movimento do personagem/câmera funcional
- ✅ Pelo menos 1 mecânica jogável
- ✅ Detecção de colisões 
- ✅ UI básica (pode ser placeholder)
- ✅ Jogo não trava ou crasha facilmente

### Critérios de Avaliação
- Funcionalidade (40%)
- Controles e responsividade (20%)
- Qualidade do código (15%)
- Progresso desde Fase 1 (15%)
- Histórico de commits (10%)



### Critérios de Avaliação

#### Funcionalidade (25%)
- Jogo funciona sem crashes
- Mecânicas implementadas completamente
- Objetivo claro e alcançável


## Regras e Diretrizes

### Permitido ✅
- Asset packs gratuitos
- Tutoriais e documentação oficial
- Plugins da engine
- Músicas Creative Commons
- Code snippets (com atribuição)
- IA para gerar assets (declarar uso)

### Não Permitido ❌
- Copiar jogos existentes integralmente (validação por detector de plagio)
- Usar projetos prontos/templates completos
- Plagiar código de outros grupos
- Assets pirateados
- Submeter trabalho de outras pessoas

### Trabalho em Grupo
- **Grupo**: 4 pessoas
- Divisão clara de responsabilidades



### Documentação de Engines
- [Unity Learn](https://learn.unity.com/)
- [Godot Docs](https://docs.godotengine.org/)
- [Unreal Engine Learning](https://dev.epicgames.com/community/learning)

### Game Design
- [Game Design Compendium](https://www.gamedesigning.org/)
- [Extra Credits (YouTube)](https://www.youtube.com/@extracredits)
- [GDC Vault](https://www.gdcvault.com/)

### Assets Gratuitos
- [OpenGameArt.org](https://opengameart.org/)
- [Kenney.nl](https://kenney.nl/)
- [Itch.io Assets](https://itch.io/game-assets)
- [FreeSFX](https://www.freesfx.co.uk/)

### Ferramentas
- [Git Tutorial](https://git-scm.com/docs/gittutorial)
- [Trello/Notion](https://trello.com/) - Gestão de tarefas
- [OBS Studio](https://obsproject.com/) - Gravação de gameplay



**Professor:** Prof. Dr. Luiz Custódio
**Disciplina:** Desenvolvimento de Jogos  


**Boa sorte e divirtam-se criando!**
