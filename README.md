# Event_Data_Analysis
Análise de dados de um evento de empreendedorismo

Observação: A base de dados desse repertório contém dados reais de um evento de empreendedorismo realizado em 2019 realizado dentro de uma universidade, o qual o autor desse github participou da organização do evento.

Porém por motivos de LGPD, a base de dados foi modificada para que não fosse compartilhado nenhum dados sensível dos participante do evento, por isso a coluna "Documento" que contém o CPF, foi excluída, e a coluna Nome, foi gerado nomes gerados dados aleatório utilizando numpy, mas mantendo o padrão do dataset original.

## Objetivo:
Objetivo é construir um dashboard que seja possível responder as seguintes perguntas:

- Quantidade de pessoas inscrita por palestras;
- Quantidade de inscritos na palestra x quantidade de pessoas que compareceram;
- Quantidade de inscritos PCD;
- Numero total de pesssoas por gênero;
- Quais são os cursos das pessoas que participaram;
- Evolução da Quantidade de inscritos por dia;
- De quais cidades/Estados são os inscritos;

## Etapa Python:

[Link Pipeline Figma](https://www.figma.com/file/T3S4HP4TafQHkQfUjESg2g/Evento?node-id=0%3A1&t=QeOpw5xiinfov121-1)

Limpeza dos dados:

- Conferência de dados duplicados;
- Ajustar tipos de dados;
- Renomear colunas;
- Exlcuir colunas que não vão ser usadas na análise;
- Conferência de valores ausentes;
- Tratamento dos valores ausentes;
- Concatenação de colunas;

![image](https://user-images.githubusercontent.com/53667656/228702656-87535e5c-c6db-48a6-b7a1-aaa39272b3d5.png)

# Etapa Power BI:

Visualização dos dados:

![image](https://user-images.githubusercontent.com/53667656/228701502-d4777760-ef68-47a4-85e5-f2a4011c7847.png)

