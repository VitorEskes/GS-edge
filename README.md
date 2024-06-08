# GS-edge

Projeto: Monitor de pH e Temperatura com LCD
Este projeto utiliza um display LCD, um sensor de pH e um sensor de temperatura TMP36 para medir e exibir os valores de pH e temperatura em um ambiente. O projeto também inclui ícones customizados para representar diferentes estados do pH.

Sumário
Introdução
Requisitos
Dependências
Instruções de Uso
Código
Notas
Introdução
Este projeto foi desenvolvido para demonstrar a integração de sensores analógicos com um display LCD utilizando a plataforma Arduino. O objetivo é ler os valores de pH e temperatura, mapear esses valores para uma escala compreensível e exibi-los no LCD junto com mensagens indicativas.

Requisitos
Arduino Uno (ou qualquer outra placa compatível)
Display LCD 16x2
Sensor de pH (simulado com potenciômetro)
Sensor de temperatura TMP36
Protoboard e cabos jumper
Dependências
Este projeto depende da biblioteca LiquidCrystal para controlar o display LCD. Esta biblioteca está incluída por padrão na IDE do Arduino.

Instruções de Uso
Montagem do Circuito:

Conecte os pinos do display LCD aos pinos digitais do Arduino conforme especificado no código.
Conecte o pino do sensor de pH (potenciômetro) ao pino A0 do Arduino.
Conecte o pino do sensor de temperatura TMP36 ao pino A1 do Arduino.
Configuração do Software:

Abra a IDE do Arduino.
Copie e cole o código fornecido abaixo no editor da IDE.
Compile e carregue o código na placa Arduino.
Operação:

Após carregar o código, o display LCD mostrará os valores de pH e temperatura atualizados a cada segundo.
O monitor serial também exibirá os valores de pH e temperatura para depuração.

Notas
Certifique-se de que todos os sensores estejam corretamente conectados e calibrados para obter leituras precisas.
Você pode ajustar os limites das mensagens de pH (pHMessage) conforme necessário para sua aplicação específica.
Os ícones personalizados (shit, smile, serious) podem ser modificados ou removidos conforme necessário para seu projeto.
Com essas instruções, você deve estar apto a configurar e utilizar seu monitor de pH e temperatura com LCD. Se tiver dúvidas ou problemas, sinta-se à vontade para perguntar!

Equipe
- Vitor Alves Titus Eskes - RM555137
- Nathan Craveiro Gonçalves Amin - RM555508
- Gabriel Matias Simões - RM556171
