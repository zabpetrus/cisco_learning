iptables -L -v
iptables -I FORWARD -p tcp -d 209.165.202.133 --dport 6666 -J DROP

----

Hexadecimal criado pelo Kibana

xxd -r -p "NS-Queries.csv" > secret.txt

-----
se o wireshark não der permissão:

#muda a configuração do wireshark. Se estiver não, marca sim para todos os usuarios
sudo dpkg-reconfigure wireshark-common

#onde a magica acontece: muda a permissão do dumpcad
sudo chmod +x /usr/bin/dumpcap



