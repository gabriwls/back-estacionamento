# Construindo um Sistema para um Estacionamento com C# 

Construção de um sistema de gerenciamento de veículos estacionados.  

Através de um menu interativo, o sistema permite adicionar, listar e remover veículos (e encerrar o programa).  
No ato de remoção, exibe também o valor a ser cobrado pela estadia.   

Os métodos do sistema encontram-se na classe "Estacionamento", como no diagrama abaixo:
<p align="center"><img src="/diagrama_classe_estacionamento.png"></p>


A classe contém três variáveis:

**precoInicial**: é o preço cobrado para deixar seu veículo estacionado.

**precoPorHora**: é o preço cobrado por hora que o veículo permanecer estacionado.

**veiculos**: é uma lista de string, representando uma coleção de todos os veículos estacionados, contendo todas as placas.

<br>

Quanto aos métodos:

**AdicionarVeiculo**: recebe a placa digitada pelo usuário, guarda-a na variável **veiculos** e confirma ao usuário o êxito no cadastramento do veículo.

**RemoverVeiculo**: verifica se um determinado veículo está estacionado uma vez digitada sua placa. Em caso positivo, requere a quantidade de horas que este permaneceu no estacionamento e retorna ao usuário o preço a ser pago pela estadia (**precoInicial** * **precoPorHora**).

**ListarVeiculos**: lista todos os veículos estacionados atualmente no estacionamento. Caso não haja nenhum, exibe a mensagem "Não há veículos estacionados".  
<br>
*(Desafio de projeto do bootcamp "Pottencial .NET Developer" oferecido pela [DIO](https://www.dio.me/) e pela [Pottencial](https://pottencial.com.br/))*
