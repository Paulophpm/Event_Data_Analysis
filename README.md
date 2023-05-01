# Event_Data_Analysis
Análise de dados de um evento de empreendedorismo

Observação: A base de dados desse repertório contém dados reais de um evento de empreendedorismo realizado em 2019 realizado dentro de uma universidade, o qual o autor desse github participou da organização do evento.

Porém por motivos de LGPD, a base de dados foi modificada para que não fosse compartilhado nenhum dados sensível dos participante do evento, por isso a coluna "Documento" que contém o CPF, foi excluída, e a coluna Nome, foi gerado nomes dados aleatório utilizando numpy, mas mantendo o padrão do dataset original.

## Objetivo:
Objetivo é construir um dashboard que seja possível responder as seguintes perguntas:

- Quantidade de pessoas inscrita;
- Quantidade de inscritos PCD;
- Numero total de pesssoas por gênero;
- Quais são os cursos das pessoas que participaram;
- Evolução da Quantidade de inscritos por dia;
- De quais cidades/Estados são os inscritos;

## Etapa 0  - Pipeline dos Dados (Figma):

[Link Pipeline Figma](https://www.figma.com/file/T3S4HP4TafQHkQfUjESg2g/Evento?node-id=0%3A1&t=QeOpw5xiinfov121-1)

Antes de inicia a análise é necessário saber com conectar os dados a serem analisados. No caso em questão, foi feito uma consulta no dataset original para retirar apenas os dados dos participantes com excecões dos dados sensíveis e assim criado uma nova fonte de dados.

A nova fonte de dados foi realizado o processo de ETL, como mostrado no proximo item, para que seja criado uma nova fonte que servirá de base para visualizar os dados através do Power BI.   

## Etapa 1 - Limpeza de Dados (Python):

Como uma boa parte dos dados dos inscritos foram os prórprios inscritos que preencheram, é necessário entender se todos os dados estão no mesmo padrão para que seja possível realizar a análise dos dados de forma mais fácil e eficiente possível.

- Conferência de dados duplicados;
- Ajustar tipos de dados;
- Renomear colunas;
- Excluir colunas que não vão ser usadas na análise;
- Conferência de valores ausentes;
- Tratamento dos valores ausentes;
- Concatenação de colunas;

# Etapa 2 - Visualização dos Dados (Power BI):

Mockup no Figma

https://www.figma.com/file/WoX35lSFOwFijMCDkRe8Nn/Dash?node-id=0%3A1&t=gNLjJBCDLKfxKWtV-1


Visualização dos dados:

![image](https://user-images.githubusercontent.com/53667656/235383514-5471051d-4836-4a0c-8d36-a7cc8a2aa1dd.png)
