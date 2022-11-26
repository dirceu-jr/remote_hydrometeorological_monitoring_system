# Sobre

<img src="https://raw.githubusercontent.com/dirceu-jr/ambient-water-quality/master/readme_files/water_FILL0_wght400_GRAD0_opsz48.svg" align="middle">

[Read in English](https://dirceu-jr.github.io/ambient-water-quality/)

Eu morava na frente de um [lindo mas poluído lago](https://pt.wikipedia.org/wiki/Ficheiro:Lago_Igap%C3%B3_Londrina.jpg). Agora eu moro na [cidade de Curitiba](https://pt.wikipedia.org/wiki/Curitiba), alguns dizem <i>a cidade mais ecológica do Brasil</i>.

Eu desenvolvo esse projeto com o objetivo de implementar uma rede de monitoramento. E também com objetivos educacionais.

O estado atual é o início da prototipagem de hardware e software.

## Hardware atual

- [Atlas Scientific Wi-Fi Pool Kit](https://atlas-scientific.com/kits/wi-fi-pool-kit/) (<i>Legacy</i>, com <i>ESP8266</i>). Possui sondas de pH, ORP (Potencial de redução) e temperatura, mas fornece apenas conectividade Wi-Fi.

<a target="_blank" href="https://atlas-scientific.com/kits/wi-fi-pool-kit/"><img alt="Atlas Scientific Wi-Fi Pool Kit" width="260" src="https://raw.githubusercontent.com/dirceu-jr/ambient-water-quality/master/readme_files/wi-fi-pk01.jpeg"></a>

- [LILYGO® TTGO T-BAT Battery Holder](https://pt.aliexpress.com/item/4001156737871.html). Suporte de bateria e circuito de carga do painel solar. Pode fornecer energia para o Wi-Fi Pool Kit.

<a target="_blank" href="https://pt.aliexpress.com/item/4001156737871.html"><img alt="LILYGO® TTGO T-BAT Suporte de Bateria" width="260" src="https://raw.githubusercontent.com/dirceu-jr/ambient-water-quality/master/readme_files/lilygo-ttgo-t-bat.webp"></a>

## Trabalho em progresso

Alguns locais onde seria bom ter estações de monitoramento não possuem ponto de acesso Wi-Fi. Portanto, conectividade celular ou mesmo via satélite são necessárias.

- [LILYGO® TTGO T-SIM7000G](https://pt.aliexpress.com/item/4000542688096.html). Esta placa de baixo consumo de energia e baixo custo vem com microcontrolador <i>ESP32</i> da Espressif, modem 7000G da SIMCom, suporte de bateria e circuito de energia solar, tudo por volta de 200 Reais. O <i>ESP32</i> é mais capaz que o <i>Arduino</i> e mais barato que o <i>Raspberry Pi</i>. Pode fornecer conectividade celular ao Kit da Atlas Scientific.

<a target="_blank" href="https://pt.aliexpress.com/item/4000542688096.html"><img alt="LILYGO® TTGO T-SIM7000G" width="260" src="https://raw.githubusercontent.com/dirceu-jr/ambient-water-quality/master/readme_files/lilygo-t-sim7000g.webp"></a>

## Referências

- Danos Socioambientais Urbanos Em Curitiba: Uma Abordagem Geográfica ([PDF](https://github.com/dirceu-jr/ambient-water-quality/blob/master/references/danos-socioambientais-urbanos-em-curitiba-uma-abordagem-geografica.pdf))

## Software

- [Software Embarcado](https://github.com/dirceu-jr/ambient-water-quality/blob/master/firmware/legacy_pool_kit.ino)
- [Canal no ThingSpeak](https://thingspeak.com/channels/1956479/)
- [Protótipo de painel](https://dirceu-jr.github.io/ambient-water-quality/dashboard/)

## Fornecedores

Para fins educacionais...

- [Atlas Scientific](https://atlas-scientific.com/)
- [Espressif](https://www.espressif.com/)
- [LILYGO](https://pt.aliexpress.com/store/2090076)
- [Swarm](https://swarm.space/)

## Dados em tempo real

<iframe width="450" height="260" src="https://thingspeak.com/channels/1643222/charts/1?bgcolor=%23ffffff&color=%23d62020&dynamic=true&results=60&title=pH&type=line"></iframe>

<iframe width="450" height="260" src="https://thingspeak.com/channels/1643222/charts/2?bgcolor=%23ffffff&color=%23d62020&dynamic=true&results=60&title=ORP&type=line"></iframe>

<iframe width="450" height="260" src="https://thingspeak.com/channels/1643222/charts/3?bgcolor=%23ffffff&color=%23d62020&dynamic=true&results=60&title=Temp&type=line"></iframe>