# MYLIFE

**Minha vida. Meu controle. Meu sistema.**

Aplicativo pessoal de organização construído somente com HTML5, CSS3 e JavaScript puro. A página **Meu Dia** permanece como dashboard principal e agora conta com uma navegação escalável para os módulos futuros.

## Funcionalidades atuais

- Dashboard Meu Dia com data dinâmica, resumo, prioridades, agenda, progresso e alertas.
- Prioridades interativas com checkbox, status e contador atualizado.
- Busca visual por prioridades e eventos.
- Painéis de notificações e perfil.
- Tema claro/escuro persistido em `localStorage`.
- Sidebar desktop fixa, recolhível e com tooltips no modo compacto.
- Navegação modular com estados de módulos ainda não implementados.
- Navegação inferior adaptada para mobile com Início, Agenda, Tarefas, Criar e Mais.
- Layout responsivo para desktop, tablet e smartphone.

## Como executar

Abra `index.html` diretamente no navegador. Não há processo de build, servidor ou dependência externa.

## Estrutura

- `index.html`: interface, estilos e lógica organizada em funções de navegação e dashboard.
- `.gitignore`: arquivos locais que não devem ser versionados.

Os itens de navegação usam `data-route` e um único controlador de rotas. Assim, novos módulos podem substituir os estados de placeholder sem reconstruir a navegação existente.
