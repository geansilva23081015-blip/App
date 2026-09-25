# MYLIFE

**Minha vida. Meu controle. Meu sistema.**

Fundação visual e estrutural do MYLIFE, um sistema pessoal de organização e gerenciamento da vida. Esta primeira versão entrega a página **Meu Dia**, construída apenas com HTML5, CSS3 e JavaScript puro, sem frameworks ou dependências externas.

## Funcionalidades

- Data e saudação atualizadas dinamicamente.
- Resumo do dia com tarefas, compromissos, estudos, treino e hábitos.
- Prioridades interativas com checkbox, status e contador atualizado.
- Timeline da agenda do dia.
- Indicadores de progresso.
- Área de alertas com estados visuais.
- Busca visual por prioridades e eventos.
- Painéis de notificações e perfil.
- Tema claro, escuro e sistema, persistido em `localStorage`.
- Layout responsivo para desktop, tablet e smartphone.

## Como executar

Abra `index.html` diretamente no navegador. Não há processo de build ou servidor obrigatório.

## Estrutura

- `index.html`: marcação, estilos e lógica da fundação inicial em um único arquivo HTML portátil.
- `.gitignore`: arquivos locais que não devem ser versionados.

A arquitetura utiliza atributos `data-*`, componentes semânticos e funções JavaScript separadas para facilitar a futura inclusão de sidebar, tarefas, agenda, finanças, estudos, saúde, metas, hábitos e IA.
