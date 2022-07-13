# Ranqueamento de clientes por predisposição em aderir a apólice de seguro automotivo

![TSafe](https://cdn.autopapo.com.br/box/uploads/2020/03/20163712/shutterstock-apolice-seguro-auto-documentos-carro-homem-gravata-camisa-social-732x488.jpg)

## Totally Safe S.A

## Contextualização:

A Totally Safe S.A é uma empresa consolidada no mercado de seguro de saúde que em essa nova etapa analisa a possibilidade de oferecer aos seus clientes um novo produto: O seguro automotivo.
Ao longo de todo ano passado, foi realizada uma pesquisa com cerca de 380 mil de seus clientes quanto ao interesse em aderir ao seu novo serviço gerando assim uma base de dados contendo informações sobre cada cliente e sua resposta.
A equipe de produtos selecionou mais de 125 mil novos clientes de sua carteira que ainda não foram expostos a oferta do novo produto para serem contactados por telefone e apresentados ao seguro automotivo.
No entanto a capacidade real de abrangência da equipe de vendas são 20 mil atendimentos no período da campanha.

## Desafio:
- Coletar os dados que estão alocados na plataforma AWS quanto a pesquisa já realizada anteriormente com os clientes;
- Construin um modelo que preveja se o cliente estariam ou não interessados no seguro automotivo;
- Definir a porcentagem de interessados poderão ser alcançados pela equipe de vendas fazendo 20.000 ligações; 

## Proposta de solução:
Desenvolver um modelo de aprendizado de máquina que possa ranquear (LTR - Learning to Rank) os clientes quanto a probabilidade de interesse na aquisição do seguro com base nas informações contidas na base de dados da empresa.
Como artefato de entrega, será encaminhado ao SEO uma tabela contendo essa lista de clientes ranqueada juntamente com as métricas de eficiência do modelo.

## Resultados
O CEO terá acesso ao [Dashboard Interativo]() com todas as informações facilitando assim o acesso, independente do local e dispositivo que tenha a disposição. 
Além de receber por e-mail a planilha contendo os clientes em potencial ranqueados para que possa encaminhar ao setor de vendas para o início da campanha.

## Ferramentas utilizadas:
- Python com foco em análise de dados;
- Git, Github;
- Heroku Cloud;
- Streamlit
- Pacotes de Machine Learning: sklearn e xgboost;
- Técnicas de seleção de atributos (Random Forest, Extra Trees e Boruta);
### Escopo 
Todo o processo de EDA (Análise exploratória dos dados ) bem como escolha e criação das máquinas preditivas, estão disponíceis [Neste Link](https://github.com/rsantosluan/Helth_Insurance_Cross_Sell/blob/master/Notebooks/data_exploration.ipynb)


## Referências:

- A mecânica de negócio utilizada no projeto apresentado foi desenvolvida na [Comunidade DS](https://www.comunidadedatascience.com/)
- Os dados utilizados nesse projeto estão disponíveis no [Kaggle](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction)

