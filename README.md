---
website: "Temporada Música em São Roque"          # Entre as aspas escreve o nome do website
date: "11/03/2026"                    # Entre as aspas escreve a data de criação do 1º relatório. Os restantes estão no histórico
uri: "https://tmsr.scml.pt/"   # Entre as aspas escreve o domínio do website
owner: "Santa Casa da Misericórdia"         # Entre as aspas escrever o nome do owner do website
a11y_statement: "https://tmsr.scml.pt/declaracao-de-acessibilidade/" # Entre as aspas escrever o url da Declaração de Acessibilidade
seal: "Prata"                          # Entre as aspas escreve Bronze, Prata ou Ouro
status: "Auditoria sem efeito porque criaram site novo"    # Entre as aspas escreve uma das seguintes opções: "Auditoria a decorrer", "A aguardar correções da entidade", "Concluído" 
---

# Relatório de auditoria

Sítio Web: {{ page.website }} 

- Data de criação: {{ page.date }}
- URL: {{ page.uri }} 
- Propriedade: {{ page.owner }}
- Candidatura: {{ page.seal }}
- Validade do Selo: {{ page.validity }}
- Estado: {{ page.status }}

## Relatório {{ page.website }}

O presente relatório resultou da auditoria da informação publicada na [Declaração de Acessibilidade e Usabilidade]({{ page.a11y_statement }}).

Consulte aqui a última atualização: [Relatório {{ page.website }}](report.html)

<details>
  <summary>Histórico de atualizações</summary>
  <ul aria-label="lista de relatórios já efetuados">
    <li><a href="06042026_report.html">(06/04/2026). Relatório {{ page.website }}</a></li>
