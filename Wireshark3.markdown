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
<br>
<p>Referências: www.inf.pucrs.br/~benso/redes601/2004_2/tcp_udp.ppt</p>
<br>
<br>
<br>
<br>
<h4>TCP</h4>
<br>
<br>
O arquivo capturado está no repositório em "link" com o nome <b>"filename"</b>
