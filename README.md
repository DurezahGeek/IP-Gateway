# 🛠️ Projeto Cisco Packet Tracer: Configuração de IP, Gateway e Subnet

## 🎯 Objetivo
Configurar dois computadores (PCs) em uma rede local, atribuindo IPs, gateway e máscara de sub-rede de forma que consigam se comunicar corretamente entre si.

## 🛠️ Topologia Utilizada

- 🖥️ **2 PCs:** PC1 (PCA) e PC2 (PCB)  
- 🔀 **1 Switch:** Switch0  
- 🌐 **1 Roteador:** Router0  
- 🔌 **Cabos:** Copper Straight-Through (conectando PCs e roteador ao switch)

---

## 🔧 Configurações Realizadas

### 📍 PC1 (PCA)
- **IP:** 192.168.1.10  
- **Máscara de Sub-rede:** 255.255.255.0  
- **Gateway:** 192.168.1.1  

### 📍 PC2 (PCB)
- **IP:** 192.168.1.20  
- **Máscara de Sub-rede:** 255.255.255.0  
- **Gateway:** 192.168.1.1  

### 📡 Roteador (Router0)
- **Interface:** FastEthernet 0/0  
- **IP:** 192.168.1.1  
- **Máscara de Sub-rede:** 255.255.255.0  
- **Porta:** Ativada (Port Status: ON)

---
## ✅ Teste de Conectividade

- No **PC1**, foi executado:
```bash
ping 192.168.1.20
```
Resultado: respostas bem-sucedidas confirmando a comunicação entre os dispositivos.

---
## 📝 Observações

- Todos os dispositivos estão na mesma sub-rede (`192.168.1.0/24`).
- O roteador atua como gateway para os PCs, permitindo a comunicação via camada 3 (IP).
- A conectividade foi testada com sucesso.


## 🖼️ Capturas de Tela

### 🔌 Topologia da Rede
> Estrutura completa com os 2 PCs, switch e roteador conectados.
![Topologia da Rede](https://raw.githubusercontent.com/DurezahGeek/IP-Gateway/refs/heads/main/src1/1.png)

---

### 💻 PCA – Configuração de Rede
> Mostra o modelo, IP, MAC Address e Gateway configurado no PC1.
![PC1 Detalhes](https://raw.githubusercontent.com/DurezahGeek/IP-Gateway/refs/heads/main/src1/6.png)

---

### 💻 PCB – Configuração de Rede
> Mostra o modelo, IP, MAC Address e Gateway configurado no PC2.
![PC2 Detalhes](https://raw.githubusercontent.com/DurezahGeek/IP-Gateway/refs/heads/main/src1/bbb.png)

---

### 📶 Switch Detalhes
> Apresenta o modelo do switch (2960) e as portas que estão conectadas aos dispositivos.
![Switch Detalhes](https://raw.githubusercontent.com/DurezahGeek/IP-Gateway/refs/heads/main/src1/S.png)

---

### 🌐 Roteador Detalhes
> Informações do roteador (1841), portas conectadas e IP configurado na interface.
![Roteador Detalhes](https://raw.githubusercontent.com/DurezahGeek/IP-Gateway/refs/heads/main/src1/rr.png)


## 📂 Arquivos Incluídos

- `Configuração de IP, Gateway e Subnet.pkt`: Arquivo da simulação no Cisco Packet Tracer
- `README.md`: Este documento explicando o projeto

## 👩‍💻 Autora

Biatriz Gomes

---
