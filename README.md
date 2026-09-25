# MYLIFE

**Minha vida. Meu controle. Meu sistema.**

Aplicativo pessoal de organização construído apenas com HTML5, CSS3 e JavaScript puro.

## Funcionalidades

- Dashboard **Meu Dia** com data dinâmica, resumo, prioridades, agenda, progresso e alertas.
- Navegação desktop completa, sidebar recolhível com tooltips e navegação inferior no mobile.
- Design System centralizado com tokens de cores, espaçamento, tipografia, estados e componentes reutilizáveis.
- Central de Criação Rápida com 12 tipos de registro: tarefa, evento, gasto, receita, meta, hábito, refeição, água, treino, compra, anotação e estudo.
- Formulários dinâmicos com campos específicos para cada tipo.
- Persistência real em `localStorage`, com repositório isolado para futura substituição por API.
- Registros criados exibidos na seção “Meus registros”, com edição e exclusão funcionando.
- Dark mode persistido, busca, checkboxes de prioridades, painéis e modal responsivo preservados.

## Como executar

Abra `index.html` diretamente no navegador. Não há processo de build, servidor ou dependência externa.

## Correções desta versão

- Corrigida a navegação completa dos módulos, que havia sido reduzida na implementação anterior.
- Corrigido o fluxo de busca para não apagar a dashboard ao trocar de rota.
- Corrigida a Central de Criação Rápida: agora fechar, voltar, salvar, editar e excluir são operações funcionais.
- Corrigida a persistência dos dados e a atualização visual da lista de registros após alterações.
- Corrigido o uso de `crypto.randomUUID` com fallback para navegadores que não oferecem essa API.

## Arquitetura

- `index.html`: marcação, Design System, navegação e JavaScript modular.
- `.gitignore`: arquivos locais que não devem ser versionados.

A camada `repository` concentra o armazenamento dos registros e pode ser trocada por um backend sem alterar os formulários ou componentes visuais.
