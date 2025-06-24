# DIO - Trilha .NET - Explorando a linguagem C#
Este repositório contém o código do desafio de projeto da trilha .NET - Explorando a linguagem C# (www.dio.me).

## Desafio de projeto :bulb: 
O objetivo do desafio é implementar um sistema de hospedagem funcional para gerenciar reservas de um hotel, garantindo regras de validação e cálculo dinâmico de preços.

## Contexto :hotel:
O sistema de hospedagem foi desenvolvido para:
- Gerenciar hóspedes e reservas em um hotel.
- Relacionar hóspedes, suítes e reservas.
- Calcular o valor correto das diárias com base em regras definidas.

## Funcionalidades Implementadas :computer:
### Validação de Regras
- Capacidade da Suíte: Não é possível realizar uma reserva de uma suíte com capacidade menor do que a quantidade de hóspedes. Exemplo: Caso a suíte comporte 2 pessoas, uma tentativa de reservar para 3 hóspedes resultará em uma exceção.
- Quantidade de Hóspedes: O método ObterQuantidadeHospedes retorna a quantidade total de hóspedes cadastrados.
- Cálculo de Diárias: O método CalcularValorDiaria calcula o valor da diária com base nos dias reservados e no valor da suíte. Um desconto de 10% é aplicado automaticamente para reservas de 10 ou mais dias.

### Estrutura do Sistema
- Classe Pessoa: Representa os hóspedes.
- Classe Suíte: Representa as suítes disponíveis no hotel, contendo informações como tipo, capacidade e valor da diária.
- Classe Reserva: Faz o relacionamento entre hóspedes e suítes, gerenciando as reservas e aplicando as regras de validação e cálculo.

### Dinâmica de Uso
- Cadastro de hóspedes em uma reserva.
- Atribuição de uma suíte específica a uma reserva.
- Cálculo automático de valores, considerando regras de desconto.

## Regras do Desafio :white_check_mark:
1. Implementação das regras descritas no contexto.
2. Desenvolvimento do sistema de forma robusta e seguindo boas práticas de codificação.
3. Adaptação das funcionalidades aos requisitos propostos.

![Diagrama de classe estacionamento](diagrama_classe_hotel.png)

## Conclusão :trophy:
O desafio foi concluído com sucesso, implementando todas as regras e funcionalidades propostas. O código foi estruturado para ser claro, escalável e fácil de manter.

Se tiver interesse em colaborar ou discutir melhorias, sinta-se à vontade para entrar em contato! 😊

Autora: Kezia Oliveira
