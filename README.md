# MYLIFE

**Minha vida. Meu controle. Meu sistema.**

Aplicativo pessoal de organização construído somente com HTML5, CSS3 e JavaScript puro.

## Funcionalidades atuais

- Dashboard **Meu Dia** com data dinâmica, resumo, prioridades, agenda, progresso e alertas.
- Navegação desktop completa com sidebar fixa e recolhível, tooltips no modo compacto e estados de módulos futuros.
- Navegação inferior para mobile com Início, Agenda, Tarefas, Criar e Mais.
- Design System centralizado em variáveis CSS e componentes reutilizáveis.
- Componentes globais: botões, cards, inputs, selects, checkboxes, switches, badges, modais, dropdowns, tabs, progress bars, alertas, empty states e tooltips.
- Modal demonstrativo responsivo para criação de itens, preparado para tarefas, gastos, metas e estudos.
- Prioridades interativas com checkbox, status e contador atualizado.
- Busca visual por prioridades e eventos.
- Painéis de notificações e perfil.
- Tema claro/escuro persistido em `localStorage`.
- Layout responsivo para desktop, tablet e smartphone.

## Como executar

Abra `index.html` diretamente no navegador. Não há processo de build, servidor ou dependência externa.

## Arquitetura

- `index.html`: interface, Design System, navegação e lógica organizada em funções.
- `.gitignore`: arquivos locais que não devem ser versionados.

Novos módulos devem consumir as classes globais (`.btn`, `.card`, `.field`, `.badge`, `.modal`, `.progress`, `.alert`, etc.) e as variáveis de `:root`, mantendo a identidade visual consistente.
