# O caso da Vinheira Agnello

Esse projeto é um sistema de monitoramento de ambiente para o local onde os vinhos são armazenados.

O sistema captura a luminosidade, umidade e temperatura do ambiente para garantir a qualidade do vinho, e com base nos dados coletados notificar a equipe responsável através de 3 leds: verde quando o ambiente estiver nas condições certas, amarelo quando estiver em níveis de alerta e vermelho para indicar algum problema, junto com o acionamento de um buzzer.

## Condições do ambiente:

### Luminosidade:
Os vinhos devem permanecer na penumbra para não afetar a sua qualidade

## Vídeo explicando como o sistema funciona:
https://youtu.be/f0wtTETWxHo?feature=shared

> [!NOTE]
> Pré-requisitos
> - Tinkercad para a simulação
> - Conhecimento básico de Arduino

## Funcionalidades

- Monitoramento da luminosidade do ambiente
- Aviso visual através de leds do estado em que o ambiente está: ideal, em alerta e problema

## Estrutura do projeto

<img width="476" height="519" alt="image" src="https://github.com/user-attachments/assets/5b410ab7-c34e-4d81-960d-a77ec1acfb79" />

## Link para simulação do projeto:
https://www.tinkercad.com/things/eycspBHlP9i-sensor-de-luminosidade?sharecode=DzSfoLtOpKuL4Q3SH4tyTOWgR0TrB1i7qmFrxQWK8l4

## Hardware - lista de componentes

- 1 Arduino
- 3 leds (vermelho, amarelo, verde)
- 1 buzzer
- 1 fotoresistor
- 10 cabos jumper
- 5 resistores de 300 ohms 

## Software:
Arduino IDE, Tinkercad

## Como rodar o projeto no Tinkercad:
- Copie a estrutura do projeto no simulador
- Copie o código do repositório dentro do editor de código do Tinkercad
- Comece a simulação

## Como rodar o projeto na sua máquina:
- Clone o projeto na sua máquina:` git clone `
- Abra o projeto dentro do Arduino IDE
- Siga a estrutura do projeto do README
- Faça o upload do código para a sua placa
