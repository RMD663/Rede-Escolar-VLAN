# Simulação de Rede Escolar - VLAN

Projeto de simulação de rede desenvolvido para a disciplina de Tópicos Especiais em Redes de Computadores. O foco é a segmentação lógica de departamentos e roteamento inter-VLAN.

##  Configurações
A rede utiliza a técnica **Router-on-a-Stick** para permitir que as sub-redes de Alunos e Professores se comuniquem através de um único roteador.

* **VLAN 10 (Alunos):** Rede 192.168.10.0/24
* **VLAN 20 (Professores):** Rede 192.168.20.0/24
* **DHCP:** Servidores dedicados para atribuição automática de IPs em ambas as redes

## Tecnologias
* Cisco Packet Tracer
* Roteador Cisco 2811
* Switches Cisco 2960

## Resultados
Os testes de conectividade via ping validaram o funcionamento do roteamento entre as VLANs, apresentando tempos de resposta menores que 1ms e o comportamento esperado do TTL após os saltos de rede.

## Equipe
* Ryan Mesquita Damasceno
* Antonio Wesley Silva do Nascimento
* Higor Gabriel Rocha do Carmo
