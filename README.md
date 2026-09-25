# MYLIFE

**Minha vida. Meu controle. Meu sistema.**

Aplicativo pessoal de organização construído somente com HTML5, CSS3 e JavaScript puro.

## Entregue

- Dashboard Meu Dia com data dinâmica, resumo, prioridades, agenda, progresso e alertas.
- Sidebar desktop fixa, recolhível, com tooltips; navegação mobile inferior.
- Design System centralizado em tokens CSS e componentes reutilizáveis.
- Dark mode com preferências `light`, `dark` e `system`, salvo no `localStorage`.
- Central de Criação Rápida com 12 tipos: tarefa, evento, gasto, receita, meta, hábito, refeição, água, treino, compra, anotação e estudo.
- Formulários dinâmicos com campos específicos, validação nativa e layout responsivo.
- CRUD funcional de registros: criar, visualizar, editar e excluir.
- Persistência local isolada na camada `repository`, pronta para futura substituição por API.

## Como executar

Abra `index.html` diretamente no navegador. Não há build, servidor ou dependência externa.

## Verificação

A versão atual foi reorganizada para eliminar regressões entre navegação e criação rápida: eventos de CRUD usam delegação, registros são escapados antes de renderizar e o estado de tema é aplicado de forma segura.

## Arquivos

- `index.html`: estrutura, estilos, Design System, navegação e lógica da aplicação.
- `.gitignore`: arquivos locais ignorados pelo Git.
