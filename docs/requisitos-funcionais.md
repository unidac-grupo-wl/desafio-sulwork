# Requisitos funcionais

## Eventos

A aplicação deve permitir criar e organizar eventos de alimentação. Cada evento deve ter nome, descrição, tipo, data e horário, prazo para alterações e status.

Status mínimos: `RASCUNHO`, `ABERTO`, `ENCERRADO`, `REALIZADO` e `CANCELADO`. As ações permitidas devem respeitar o status; eventos encerrados ou realizados não aceitam contribuições. Defina e documente as transições entre status.

## Participantes

Colaboradores podem participar de vários eventos, mas não mais de uma vez no mesmo evento. O cadastro deve incluir nome, CPF válido com 11 dígitos e restrições alimentares.

## Categorias e itens

Eventos podem organizar itens por categoria e definir metas por categoria. Cada item deve informar nome, categoria, quantidade necessária, se é obrigatório ou opcional e seus alérgenos.

## Contribuições e prazo

Participantes podem incluir, alterar ou remover contribuições até o prazo definido para o evento. Cada contribuição associa participante, item e quantidade. Mais de uma pessoa pode contribuir com o mesmo item, mas a soma não pode ultrapassar a quantidade necessária. Após o prazo ou o encerramento do evento, alterações não são permitidas.

Defina um comportamento consistente para a interação entre prazo e status do evento e documente a decisão.

## Restrições alimentares e alérgenos

Apresente as restrições dos participantes e os alérgenos dos itens de forma útil. A estratégia para relacionar essas informações e seus efeitos na experiência fica a critério do candidato e deve ser documentada.

## Cobertura

Apresente quanto das necessidades do evento foi atendido. A fórmula não é prescrita: considere quantidades necessárias e contribuídas, metas por categoria e itens obrigatórios ou opcionais. Implemente uma estratégia coerente e explique-a no README da solução.

## Feature livre

Implemente uma funcionalidade adicional útil ao sistema. Explique no README o problema que ela resolve, como funciona e as principais decisões tomadas. A funcionalidade pode ser pequena; avaliaremos a coerência e a qualidade da implementação.
