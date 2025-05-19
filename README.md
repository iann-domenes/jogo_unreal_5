# MyProject

Developed with Unreal Engine 5

Terá um nome ainda. Por enquanto esse é um projeto criado para eu aprender a ferramenta.

Projeto criado no template Third Person;
Camera as child da cabeça, pois o jogo é em primeira pessoa;
Sistema de inventário simples sem gerenciamento do player e sem pause game;
Sistema de lanterna funcional com timer. Mas com muito a se resolver ainda;
Animações: Quase nada desenvolvido. Apenas o movimento do sistema de lanterna;

Components:
  - Interaction
  - Inventory

Interfaces:
  - Player
  - HUD
  - Interactable

Widgets:
  - HUD
  - Main Menu
  - Pause Menu
  - Inventory
    
Objetos interagíveis:

- Receptable
  . Busca item no inventário
- Door
  . Sistema de abertura em duas fases
  . Porta estática
  . Pode ser destrancada
- Candle
  . Pode ser acesa com ou sem item específico
- Table Drawer
  . Pode conter itens as child
  . Pode ser destrancada
- Inspectable
  . Renderiza o item para inspeção
  . Pode conter nota
- Collectable
  . Adiciona item ao inventário

Todos os objetos interagíveis são individualmente personalizáveis;


  

