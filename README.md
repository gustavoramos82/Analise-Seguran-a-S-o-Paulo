# Analise de Segurança de São Paulo

Neste repositório, será feita uma análise da cidade de São Paulo, de um dataset disponivel na base de dados (que pode ser obtido
[aqui](https://basedosdados.org/dataset/dbd717cb-7da8-4efd-9162-951a71694541?table=a2e9f998-e2c2-49b7-858a-ae1daef46dc0)), mas como são muitos crimes, foram escolhido esses três, que são eles:

- Roubo de veiculo
- Roubo a banco
- Roubo de carga

O intuito é primeiro fazer uma análise mais geral, depois recortar a anlise seguindo alguns critérios (como PIB, população, entre
outros para comparar essa separação pode influenciar em algo ou não.

## Análise Geral

Clique [aqui](https://github.com/gustavoramos82/Analise-Seguran-a-S-o-Paulo/blob/main/Texto/An%C3%A1lise%20Inicial.md) para ler esta parte

A conclusão obtida nessa análise foi que:
- Se olharmos por região, a capital foi onde teve mais roubos
  - Logo poderemos fazer uma análise por região em três parte: capital, região metropolitana (menos a capital) e o restante para vericar se há alguma mudança de comportamentos
- Em relação ao roubo de veiculos, teve mais casos no ano de 2012, roubo de carga teve mais em 2017 e roubo a banco em 2005
    - Quanto a isso, pesquisando sobre, verificamos noticias da época sobre roubo de veiculos (que pode ser lido se clicar [aqui](https://www2.jornalcruzeiro.com.br/materia/522864/roubos-de-veiculos-aumentam-62) e apontou os motivos
      > Sobre os motivos do crescimento dos crimes de furto e roubo de veículos, Cafisso afirma que existem alguns fatores nos quais a polícia acredita que podem refletir esse fato. "Levamos em conta fatores como o crescimento populacional, desenvolvimento urbano e a frota existente. Com referência à frota, podemos concluir que, embora o número de registros de furtos e roubos tenha apresentado um aumento significativo, ele acompanhou o crescimento da frota licenciada, que dobrou nos últimos 10 anos, enquanto os registros criminais dessa modalidade tiveram um acréscimo de 91,45%", relata.
    - Logo se pode fazer uma análise se há uma relação entre numero de frota de carros com roubo de veiculos
- De 2017 a 2020 tem uma tendência de queda nos três crime citados
