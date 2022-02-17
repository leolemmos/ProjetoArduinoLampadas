## projetoArduinoCasa

#Projeto de automação com arduino para ligar 16 lâmpadas
<div>
<img src="https://blogmasterwalkershop.com.br/wp-content/uploads/2019/07/img01_como_usar_com_arduino_modulo_rele_5v_de_16_canais_uno_mega_2560_nano_automacao_residencial_lampada_blynk_esp32_esp8266.jpg"></a>

</div>
<h3>Descrição</h3>

Os relés são componentes eletromecânicos capazes de controlar circuitos externos de grandes correntes a partir de pequenas correntes ou tensões, ou seja, acionando um relé com uma pilha podemos controlar um motor que esteja ligado em 110 ou 220 volts, por exemplo.

O Módulo Relé 5V de 16 Canais permite que a partir de uma plataforma microcontrolada seja possível controlar cargas AC (alternada) de forma simples e prática. Por ter 16 canais, é possível controlar até dezesseis cargas AC de até 10A. Comumente é utilizado em projetos de automação residencial para controle de lâmpadas, ventiladores e outras saídas que possam ser acionadas através de relé.

<h3>Especificações e características:</h3>

– Tensão de operação: 5VDC
– Corrente de operação: 60 ~ 80mA
– Capacidade do relé: 30VDC/10A e 250VAC/10A
– 16 canais
– LED indicador para acionamento do relé
– Tempo de resposta: 5 ~ 10ms

<h3>Aplicações:</h3>

Projetos com Arduino ou outras plataformas microcontroladas em que seja necessário fazer o controle de cargas AC. Caso o módulo seja utilizado junto a uma plataforma que esteja conectada à internet, torna-se possível controlar cargas AC através de uma página web, smartphone ou tablet.

</h3> Proposta da prática:</h3>

Utilizar o Módulo Relé 5V de 16 Canais em conjunto com o Arduino para controlar dezesseis lâmpadas através do envio de comandos pelo monitor serial do ambiente de programação do Arduino.

<h3> Lista dos itens necessários:</h3>

01 – Arduino com Cabo USB
01 – Módulo Relé 5V de 16 Canais
17 – Cabos Jumper macho-fêmea
01 – Fonte 5V 1A (5V 4A)
01 – Cabo Adaptador Conector Jack P4 Fêmea 5.5×2.1mm
16 – Lâmpada
16 – Receptáculo (boquilha)
 – Cabo paralelo de 1,5mm ou 2,5mm

<h3>Tomada (Rede alternada de 127V)</h3>

1) Por ter uma quantidade maior de canais, você deverá utilizar uma fonte externa que fornaça 5V e pelo menos 1A (REAL) para alimentar o módulo relé. Com todos os canais do módulo ligados, a tensão da fonte chega a cair 450mV. Cada canal do módulo quando ligado, consome aproximadamente 60mA.

2) Lembre-se de comutar / juntar o GND da fonte externa com o GND do Arduino. Além disso, fique atento ao esquema de ligação, pois são muitas conexões e uma falta de atenção pode comprometer o seu circuito.

3) O acionamento (ligar / desligar) de cada canal será feito através do envio de uma letra pelo monitor serial do IDE do Arduino. Basta digitar no monitor serial a letra correspondente a cada canal (vide código mais abaixo) e em seguida clicar em ENVIAR ou pressionar ENTER.

4) Após a montagem desta prática, caso em seus testes apenas uma quantidade pequena de canais do módulo forem ligados e os demais que você tentar acionar apenas acenderem o LED referente o canal, mas não acenderem a lâmpada, recomendo que troque a sua fonte de 5V por uma de melhor qualidade, pois esta que estiver utilizando não está fornecendo tensão / corrente suficiente.

<h3> Esquema de ligação da prática:</h3>

ATENÇÃO: MUITO CUIDADO AO EXECUTAR PRÁTICAS QUE ENVOLVAM TENSÃO / CORRENTE ALTERNADA! FAÇA TODAS AS LIGAÇÕES COM O CIRCUITO COMPLETAMENTE DESLIGADO E ANTES DE FAZER OS TESTES VERIFIQUE CADA UMA DAS LIGAÇÕES PARA ELIMINAR A POSSIBILIDADE DE CURTO ENTRE FASE / NEUTRO OU FASE / FASE.


