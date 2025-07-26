# 🌐 CCNA Labs GNS3

Laboratórios práticos para simulação de redes e aplicação dos conhecimentos do conteúdo **CCNA (Cisco Certified Network Associate)**, utilizando **GNS3**, **Packet Tracer** e topologias reais de redes corporativas.

---

## 💡 Objetivo

- Reforçar os conceitos de redes com foco no exame CCNA
- Praticar configurações em roteadores e switches Cisco
- Simular topologias complexas com GNS3 e Packet Tracer
- Testar conectividade, segurança de rede e troubleshooting

---

## 🚀 Projetos disponíveis

| Projeto | Descrição | Tecnologias |
|---------|-----------|-------------|
| VLANs e Inter-VLAN Routing | Criação e roteamento entre VLANs | Cisco IOS, Switch Layer 2, Router-on-a-Stick |
| NAT e DHCP | Tradução de endereços e atribuição automática | Cisco IOS, NAT, DHCP Server |
| Roteamento Estático e Dinâmico | Configuração de RIP, OSPF e EIGRP | Routers Cisco, CLI |
| Redes IPv6 | Configuração e roteamento de redes IPv6 | IPv6, OSPFv3, ICMPv6 |

---

## 🧰 Stack utilizada

- Cisco Packet Tracer 8.x  
- GNS3 com imagens Cisco IOSv  
- Wireshark (análise de pacotes)  
- VirtualBox + GNS3 VM (emuladores)  
- CLI Cisco (IOS)

---

## 🗂️ Estrutura do projeto

```bash
📁 ccna-labs-gns3/
├── vlan-intervlan/
│   ├── vlan-config.txt
│   ├── topologia.pkt
├── nat-dhcp-lab/
│   ├── nat-config.txt
│   ├── dhcp-config.txt
├── routing-lab/
│   ├── rip.txt
│   ├── ospf.txt
│   ├── eigrp.txt
├── ipv6-lab/
│   ├── ipv6-routing.txt
│   ├── topologia.gns3project
```

---

## 🧠 Como rodar os labs

1. **Packet Tracer**
   - Instale o Cisco Packet Tracer (versão mais recente)
   - Abra os arquivos `.pkt` para visualizar e interagir com os cenários

2. **GNS3**
   - Instale o GNS3 + GNS3 VM com imagens Cisco IOSv
   - Importe os projetos `.gns3project`
   - Inicie os dispositivos e conecte aos terminais para executar comandos

---

## 🧪 Em breve

- Simulação de ASA Firewall no GNS3  
- Configuração de STP, EtherChannel e HSRP  
- Labs de Troubleshooting com cenários de falhas  
- Integração com syslog e SNMP para monitoramento
