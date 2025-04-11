# Oficina - Modelo Conceitual ER

Este projeto é a criação de um modelo conceitual de banco de dados para um sistema de oficina, utilizando como ferramenta MySQL Workbench.

## 📌 Objetivo

Criar o modelo conceltual de banco de dados do zero para atender os seguintes pontos abordados no desafio:

- Os clientes levam os veiculos até a oficina para serem consertados ou para serem revisados periódicamente.
- Cada veiculo é designado a uma equipe de mecanicos para identificar os serviços a serem executados e preenchem uma OS com data de entrega.
- A partir da OS é feito o calculo do valor de cada serviço, que é guardado em uma tabela de referencia que possui o valor da mão-de-obra.
- O valor de cada peça tambem ira compor a OS e o cliente autoriza a execução dos serviços.
- Os mecanimos possuem codigo, nome, endereço e especialidade.
- Cada OS possui numero, data de emissão, valor, status e uma data de conclusão.

## 📝 Entidades

- Cliente
- Veiculos
- OrdemServico
- Equipe
- Mecanico
- Peça
- Serviço

## 🔗 Relacionamentos

- OSOrdemServico
- EquipeMecanico
- PecasOrdemOS
  
