<h1>Wireskark Lab 3 - Relatório</h1>
<h3>Criado e Respondido por <b>Lhaís Rodrigues (lrs4@cin.ufpe.br)</b></h3>
<br>
<br>
<h4>UDP</h4>
<br>
<br>
<p>1. Source Port, Destination Port, Lenght e Checksum</p>
<p>2. O cabeçalho UDP tem fixo 8 bytes de tamanho. Cada um desses 4 dados do cabeçalho tem 2 bytes.</p>
<p>3. O tamanho do segmento UDP</p>
<p>4. (2^16 – 1) + os bytes do cabeçalho</p>
<p>5. (2^16 – 1)</p>
<p>6. O número é 0x11 em hexadecimal que em decima equivale a 17</p>
<p>7. O checksum no UDP é opcional, ele é verificado apenas se for diferente de 0. O cálculo do checksum usa o cabeçalho, os dados e pseudo-cabeçalho. O pseudo-cabeçalho é utilizando para verificação adicional e confirmação que o datagrama chegou ao destino correto. No Pseudo-cabeçalho os dados são Endereço IP Origem/Destino, Zero, Protocolo e Tamanho. O pseudo-cabeçalho não é enviado no segmento UDP, ele é usado apenas para o cálculo e verificação do checksum.</p>
<p>8. A porta de origem UDP enviada pelo hospedeiro e a mesma porta do destino enviada no pacote de resposta e vice-versa</p>
<br>
<h6>Extra Credit:</h6>
<br>
<p>Considerando os dados do Segmento UDP Transmissor:</p>
<p>Endereço Origem IP = 58.10.77.186 e transformando para bits = 00111010.00001010.01001101.10111010</p>
<p>Endereço Destino IP = 203.144.207.49 e transformando para bits = 11001011.10010000.11001111.00110001</p>
<p>Considerando o protocolo UDP (0x11) = 00010001</p>
<p>O tamanho do UDP que é 53 e transformando para bits temos 00110101</p>
<p>Realizando o cálculo do checksum temos: 00111010 00001010 + 01001101 10111010 01110111 10110000 + 11001011 10010000 10111100 00110001 + 11001111 00110001 01110011 00010001 + 00010001 00110101 01100010 00100100
10011101 11011011 complementando 1 </p>
<br>
<p>Considerando os dados do Segmento UDP Receptor:</p>
<p>Endereço Destino IP = 58.10.77.186 e transformando para bits = 00111010.00001010.01001101.10111010</p>
<p>Endereço Origem IP = 203.144.207.49 e transformando para bits = 11001011.10010000.11001111.00110001</p>
<p>Considerando o protocolo UDP (0x11) = 00010001</p>
<p>O tamanho do UDP que é 53 e transformando para bits temos 00110101</p>
<p>Realizando o cálculo do checksum temos: 11001011 10010000 + 11001111 00110001 00000100 10100001 + 00111010 00001010 00111110 10101011 + 01001101 10111010 01110011 00010001 + 00010001 00110101 01100010 00100100: Resultado do Receptor dividido por  10011101 11011011 seria o resultado do transmissor result sender 11111111 11111111 para não gerar erros</p>
<br>
<p>Referências: www.inf.pucrs.br/~benso/redes601/2004_2/tcp_udp.ppt</p>
<br>
<br>
<br>
<br>
<h4>TCP</h4>
<br>
<br>
<p>1. </p>
<br>
<br>
<br>
<br>
O arquivo capturado está no repositório em "link" com o nome <b>"filename"</b>
