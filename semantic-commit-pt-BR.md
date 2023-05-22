# Semântica de Commit
A semântica de commit é uma prática recomendada para criar mensagens de commit claras e significativas que ajudam a compreender facilmente as alterações realizadas em um projeto. Uma mensagem de commit bem elaborada fornece informações sobre o propósito da alteração, tornando o histórico de commits mais organizado e compreensível.

## Padrão Conventional Commits
Um dos padrões comumente adotados é o Conventional Commits. Ele propõe uma estrutura consistente para as mensagens de commit, composta por um cabeçalho e, opcionalmente, um corpo e um rodapé.

## Cabeçalho
O cabeçalho é uma descrição curta e concisa do objetivo da alteração. Ele começa com uma palavra-chave que indica o tipo de alteração realizada, seguida de dois pontos e um espaço. Algumas palavras-chave comuns são:

- feat: Adição de uma nova funcionalidade ou recurso.
- fix: Correção de um bug ou erro.
- docs: Alterações na documentação do projeto.
- style: Alterações relacionadas à formatação do código.
- refactor: Refatoração do código existente.
- test: Adição ou modificação de testes.
- chore: Tarefas de manutenção, atualização de dependências, etc.
- perf: Melhorias de desempenho no código.
- revert: Reverter uma alteração anterior.
- build: Alterações relacionadas ao sistema de build.
- ci: Alterações nas configurações ou scripts de integração contínua.

## Corpo (opcional)
O corpo do commit é usado para fornecer mais detalhes sobre a alteração. Pode incluir informações adicionais, motivação, contexto ou qualquer outro detalhe relevante.

## Rodapé (opcional)
O rodapé pode ser usado para adicionar informações adicionais, como números de problemas relacionados, referências ou links úteis.

Exemplo de Mensagem de Commit
Aqui está um exemplo de como uma mensagem de commit usando o padrão Conventional Commits pode ser estruturada:


Exemplo de mensagem de commit usando semântica:
```

feat: Adicionar funcionalidade de login

Adiciona a funcionalidade de login para que os usuários possam autenticar-se na aplicação.

Closes #123
```


Neste exemplo, a mensagem de commit começa com a palavra-chave feat para indicar que uma nova funcionalidade está sendo adicionada. O cabeçalho descreve brevemente a alteração realizada. O corpo do commit fornece detalhes adicionais sobre a alteração, e o rodapé inclui a referência ao problema nº 123, que está sendo fechado com essa alteração.

## Benefícios da Semântica de Commit
Histórico de commits mais organizado e compreensível.
Facilita a busca e rastreamento de alterações específicas.
Ajuda a entender rapidamente o propósito de uma alteração.
Melhora a colaboração entre membros da equipe.
Permite a automação de tarefas com base no tipo de alteração.
Adotar a semântica de commit é uma prática recomendada para manter um histórico claro e informativo de um projeto, facilitando a colaboração e o entendimento das alterações realizadas ao longo do tempo
