# Critérios de aceitação — US01 a US10

Especificações para verificação futura; não representam testes executados. Os itens preservam o planejamento de referência.

## US01 — Cadastrar coleções
- Informar nome, descrição e quantidade prevista de volumes.
- Exigir nome.
- Aceitar quantidade total não informada.
- Exibir a coleção na listagem.

## US02 — Cadastrar volumes
- Informar título e número ou identificação do volume.
- Exigir vínculo com coleção existente.
- Permitir edição dos dados.
- Exibir o volume na coleção correspondente.

## US03 — Registrar edição nacional
- Informar editora nacional e data de publicação.
- Registrar primeira impressão ou reimpressão.
- Disponibilizar número e data da impressão, quando conhecidos.
- Aceitar datas desconhecidas em branco.

## US04 — Controlar exemplares
- Disponibilizar Possuo, Desejo adquirir e Não possuo.
- Permitir alteração dessa classificação.
- Disponibilizar conservação opcional.
- Manter situação da coleção independente da leitura.

## US05 — Acompanhar leitura
- Disponibilizar Não iniciado, Em leitura, Concluído e Pausado.
- Permitir alteração do estado.
- Registrar página atual e total de páginas.
- Impedir progresso negativo ou superior ao total informado.

## US06 — Adicionar capa
- Aceitar seleção de JPG ou PNG.
- Exibir capa no cadastro do volume.
- Permitir substituição e remoção.
- Usar imagem padrão na ausência de capa.

## US07 — Registrar profissionais
- Cadastrar nome do profissional.
- Associar ao volume como roteirista ou desenhista.
- Aceitar vários profissionais por função.
- Exibir créditos no detalhamento.

## US08 — Avaliar quadrinhos
- Permitir nota de 0 a 5.
- Escrever, editar e remover comentário pessoal.
- Manter avaliação opcional.
- Distinguir ausência de avaliação de nota zero.

## US09 — Pesquisar e filtrar
- Pesquisar por título ou coleção.
- Filtrar por editora, profissional, situação da coleção e estado de leitura.
- Informar ausência de resultados.
- Permitir limpar filtros.

## US10 — Consultar resumo pessoal
- Contar volumes cadastrados.
- Contar volumes marcados como Possuo.
- Contar volumes concluídos e em leitura.
- Atualizar totais conforme os registros.

## Precisões para refinamento

Exclusão lógica de volumes, granularidade da nota e latência de atualização de indicadores não foram definidas como requisitos aprovados. Critérios de aceitação por história não substituem uma Definition of Done do produto. Não foi estabelecida uma suíte BDD ou automatização dos cenários.
