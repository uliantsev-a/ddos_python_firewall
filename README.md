### DDOS Python Firewall

Скрипт служит для защиты от DDOS атак следующего типа:
- TCP-ACK Flood
- TCP-SYN Flood
- TCP-RST Flood
- KIL-TCP Flood

Использует:
- scapy
- iptables
- tcpdump

Преднозначен для использования c python3 под Linix.

Он попал ко мне как-то из [глубин интернета](https://hastebin.com/ruxacodino.py), после чего была необходимость его доработать. Мало вероятно, что сможет конкурировать с более серьёзными решениями по защите от DDOS, но тем не менее, свое дело делает.

###### Автор

[*Ульянцев Александр*](mailto:it.bumerang@gmail.com)

## Лицензия
Лицензируется по лицензии [MIT](LICENSE.txt)
