# dados-criminalidade-meteorologia

Este projeto tem como objetivo aplicar técnicas de coleta, pré-processamento, integração e análise de dados, utilizando informações de criminalidade em Passo Fundo e correlacionando-as com variáveis meteorológicas.

## Equipe do Projeto

| RA      | Nome                 |
|---------|----------------------|
| 1134868 | Ábner Panazollo      |
| 1134433 | Ariel Diefenthaeler  |
| 1134933 | Eduardo Sichelero    |
| 1134890 | Gabriel Duarte       |
| 1135384 | Gabriel Onofre       |
| 1134821 | Vitor Quadros        |

Divisão das tarefas

- Tarefas 1 a 4 - Eduardo e Vitor
- Tarefa 5 - Gabriel D. e Gabriel O.
- Tarefa 6 - Abner e Ariel

## Descrição

O projeto visa analisar a relação entre dados de criminalidade e condições meteorológicas na cidade de Passo Fundo, utilizando técnicas de ciência de dados para identificar possíveis correlações e padrões.

## Dados

Os dados não estão incluídos no repositório devido ao tamanho dos arquivos. Para reproduzir a análise:

1. Baixe os dados de criminalidade da Secretaria de Segurança Pública do Rio Grande do Sul
2. Coloque os arquivos na pasta: `Dados Criminais 2021 - 2025/`
3. Execute o notebook principal: `main.ipynb`

## Links Úteis

- [Secretaria de Segurança Pública do RS - Dados de Criminalidade](https://www.ssp.rs.gov.br/dados-abertos)
- [Dados meteorológicos](https://drive.google.com/drive/folders/18sNL1jRsmNXyWfdZHkfhVXgYnIEN0E3k)

## Como Executar

1. Clone o repositório
2. **(Recomendado)** Crie e ative um ambiente virtual Python:
   ```bash
   python -m venv venv
   ```
   - No Windows:
     ```bash
     venv\Scripts\activate
     ```
   - No Linux/macOS:
     ```bash
     source venv/bin/activate
     ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
4. Baixe os dados conforme instruções acima
5. Execute o notebook principal `main.ipynb` (Jupyter)
   ```bash
   jupyter notebook main.ipynb
   ```

***

## Principais Conclusões da Análise

- **Influência da temperatura:** O número de crimes de agressão em dias com temperatura acima de 30ºC é menor, pois esses períodos são curtos ao longo do ano. Este foi o ponto inicial de investigação das possíveis relações entre o clima e os crimes.
  
- **Locais das agressões:** Em dias quentes, a maioria das agressões ocorre em residências e vias públicas.
  
- **Horários críticos:** A ocorrência de agressões se destaca durante a noite, especialmente entre 19h e 23h, com predominância em residências.
  
- **Gênero das vítimas:** Durante a noite, as agressões em residências afetam homens e mulheres de forma praticamente igual. Contudo, em vias públicas nesse mesmo horário, as mulheres são vítimas com uma frequência significativamente maior.

