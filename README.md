# Usinas Nucleares: Monitoramento Global

Painel de Power BI com visão consolidada das usinas nucleares no
mundo: localização, capacidade instalada e geração de eletricidade
por país.

🔗 [Ver relatório publicado](https://app.powerbi.com/view?r=eyJrIjoiYTQ4NDkxZGQtNmJkMy00YzE4LTgzOWYtYTY5YWIzM2U5ZjMzIiwidCI6IjY1OWNlMmI4LTA3MTQtNDE5OC04YzM4LWRjOWI2MGFhYmI1NyJ9)

---

## O Problema

Dados sobre usinas nucleares vêm de fontes internacionais dispersas,
cada uma com seu próprio padrão, idioma e formato. Sem consolidação,
fica difícil comparar países de forma justa: número de reatores não
é a mesma coisa que geração real, e essa distinção se perde numa
tabela crua.

## A Solução

Modelo consolidando dados da IAEA, World Nuclear Association e bases
públicas num único dataset, com:

- Mapa interativo com a localização de cada usina
- Capacidade instalada (MW) e energia gerada (GWh) por país
- Filtros por continente, status (ativa/inativa) e tipo de reator
- Medidas DAX pra comparar países por número de usinas, geração total
  e produção média por reator

Painel dividido em visão geral, análise por país, mapa global e
ranking, pra separar "quantos reatores tem" de "quanto realmente
produz".

## Resultado

O dashboard deixa visível algo que não aparece numa lista simples:
países com muitos reatores nem sempre são os que mais geram energia.
Isso serve de base pra quem estuda matriz energética, política
pública ou só quer entender a distribuição real da energia nuclear
no mundo, sem depender de tabela dispersa por fonte.

## Stack

| Camada | Tecnologia |
|---|---|
| Modelagem | Power BI Service, DAX |
| Visualização geográfica | Azure Maps |
| Fontes de dados | IAEA, World Nuclear Association, Excel/CSV, APIs públicas |
