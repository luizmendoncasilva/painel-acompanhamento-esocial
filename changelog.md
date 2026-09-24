# Changelog — Painel de Monitoramento eSocial (V1)

## 24/09/2026

- Padronizada a ordem das colunas em todas as tabelas para seguir a mesma ordem usada em Validados: **Status → Empregador/Colaborador → Evento → Competência → Data → Tipo de Envio → Recibo** — os campos que só existem na tabela principal (Situação, Retorno, Resumo) ficam no final.

## 23/09/2026

- Novo filtro de data: agora dá pra escolher se o período (Data de / Data até) filtra por **Competência** ou por **Data de envio**.
- Coluna "Leiaute" renomeada para **"Evento"** em toda a tela (tabelas e detalhe).
- Datas agora aparecem formatadas (dd/mm/aaaa hh:mm) em vez do formato "D-0", "D-1" etc.
- Nova coluna **Competência** nas tabelas de eventos.
- Nova coluna **Tipo de Envio** (Inclusão / Alteração / Retificação / Exclusão) nas abas Processamento e Invalidados — antes só existia (fixo em "Inclusão") na aba Validados.
- Empregador agora mostra **razão social + CNPJ + Origem + ERP operado + Licença**, no mesmo formato usado no Gestor de Tarefas — antes só aparecia o CNPJ.
- Novo filtro por **Origem** (BHub / Carnevale).
- Aba Validados: nova coluna **"Dados do Colaborador"** (nome + CPF) e nova coluna **Competência**.
- Aba Validados → Advertências: eventos com advertência não aparecem mais duplicados em outras sub-abas (Tabelas, Periódicos etc.) — agora só aparecem em Advertências, com uma coluna nova mostrando o **motivo da advertência**.
- Ajuste visual: o status (badge) não quebra mais linha dentro da célula.
- Removida a coluna de checkbox de seleção da tabela de eventos.
- Cabeçalhos da tabela: voltaram a quebrar em até 2 linhas normalmente quando o nome da coluna é grande — trocamos a ideia inicial de cortar com "..." (ficava ilegível) por permitir a quebra de linha, que é mais comum e fácil de ler.
- Aberta a issue [DP-483](https://linear.app/bhub/issue/DP-483/melhoria-painel-esocial-v1-ajustes-de-campos-e-filtros-conforme) (sub-issue de DP-284) documentando todos esses ajustes para a engenharia.
