# Comandos-TK-GPRS-SMS.
Lista dos comandos GPRS da linha TK e seus equivalentes em SMS.
- \**,imei:123456789012345,A; (suppress243102) - Os dados do GPS param de ser atualizados se o veículo não estiver em movimento (ACC DESLIGADO). Os comandos deixam de funcionar.
- \**,imei:123456789012345,B; - Pede posição atual.
- \**,imei:123456789012345,C,020s; (fix020s\***n123456) - Definir a localização a cada xxx segundos.
- \**,imei:123456789012345,D; (nofix123456) - Parar de enviar posições. Cancela o comando "C".
- \**,imei:123456789012345,E; - Confirma recebimento de um alarme após disparo (door alarm, acc alarm, power alarm, SOS alarm) e cancela o envio.
- \**,imei:123456789012345,F,0050m; (distance123456 0050) - Definir envio de posição por distância, ou seja, enviar posição a cada xxxx metros.
- \**,imei:123456789012345,G; (move123456) - Ativa alarme de movimento (ancoragem).
- \**,imei:123456789012345,H,080; (speed123456 080) - Ativa alarme de velocidade. Envia mensagem se velocidade superior a xxxKm/h.
- \**,imei:123456789012345,I,-3; (time zone123456 -3) - Definir o fuso horário para GMT -3.
