# MYLIFE

**Minha vida. Meu controle. Meu sistema.**

Aplicativo pessoal de organização construído somente com HTML5, CSS3 e JavaScript puro.

## Funcionalidades atuais

- Dashboard Meu Dia com prioridades, agenda, progresso e alertas.
- Navegação desktop/mobile e Design System centralizado.
- Central de Criação Rápida acionada pelo botão `+`.
- 12 tipos de registro: tarefas, eventos, gastos, receitas, metas, hábitos, refeições, água, treinos, compras, anotações e sessões de estudo.
- Formulários dinâmicos com campos específicos por entidade.
- Persistência em `localStorage`, com camada de repositório preparada para futura API.
- CRUD de registros: criar, listar, editar e excluir.
- Modal responsivo no desktop e bottom sheet no mobile.
- Dark mode, busca, checkbox de prioridades, sidebar recolhível e navegação mobile preservados.

## Como executar

Abra `index.html` diretamente no navegador. Não há processo de build, servidor ou dependência externa.

## Arquitetura

- `index.html`: interface, Design System e JavaScript modular da aplicação.
- `.gitignore`: arquivos locais que não devem ser versionados.

A persistência está isolada no objeto `repository`, que pode ser substituído por chamadas a backend sem alterar os formulários ou a interface.
