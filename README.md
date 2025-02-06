











# Exercicios-de-Redes.

## 📌 Descrição
Este repositório contém uma série de exercícios sobre fundamentos de redes de computadores, incluindo questões teóricas e práticas para aprofundar o entendimento sobre o funcionamento das redes. Os exercícios teóricos ajudam a compreender conceitos essenciais, enquanto os práticos permitem aplicar os conhecimentos utilizando o terminal Linux.


## 🖥️ Exercícicos - Fundamentos de Redes
### 🔎 Teóricos
1️⃣ O que é uma rede de computadores e qual sua principal finalidade?

2️⃣ Explique a diferença entre LAN, WAN E MAN, incluindo um exemplo para cada tipo.

3️⃣ Relacione cada tipo de topologia de rede com uma vantagem e uma desvantagem:
- Estrela
- Malha
- Barramento
- Anel

4️⃣ Qual e diferença entre uma rede cabeada e uma rede sem fio? Cite vantagens e desvantagens de cada uma.

5️⃣ O que é um roteador e um switch? Como eles se diferenciam em uma rede?

--------------------------------------------------------------------------------------------------------------------


## 💻 Práticos (Terminal Linux)
**🔹 1. Identificar informações da rede**

Execute um comando no terminal para descobrir:
- O endereço IP da sua máquina
- A máscara de sub-rede
- O gateway padrão

Dica: Use o comandos como ip a, ipconfig ou ip route.

**🔹 2. Testar conectividade na rede**
1. Use um comando para testar a comunicação com um servidor (exemplo: google.com).
2. Descubra o tempo médio de resposta desse servidor.

Dica: Use **ping.**
**🔹 3. Identificar a rota dos pacotes**
Verifique qual caminho os pacotes percorrem até o servidor **www.google.com**
Dica: Use **traceroute** ou **tracepath**.

**🔹 4. Listar dispositivos conectados á sua rede local**
Descubra os dispositivos conectados na sua LAN.

Dica: Use **arp-a** ou *nmap -sn 192.168.1.0/24** (substitua pelo IP correto da rede).

---------------------------------------------------------------------------------------


## 🖥️ Exercícios - Fundamentos de Redes (Parte 2)
### 🔎 Teóricos
1️⃣ Defina os seguintes termos:
- Host
- Cliente
- Servidor
- Protocolo

2️⃣ Qual a diferença entre um endereço IP privado e um endereço IP público?

3️⃣ Explique o que acontece quando um computador tenta acessar um site na internet, desde a digitação do endereço no navegador até o carregamento da página.

4️⃣ Cite três exemplos práticos de onde cada tipo de rede seria mais adequado:
- LAN
- WAN
- MAN

5️⃣ Descreva um cenário real onde cada tipo de topologia (estrela, malha, barramento e anel) seria mais adequado.

6️⃣ Qual a diferença entre **rede ponto-a-ponto (P2P) e rede cliente-servidor?**

-----------------------------------------------------------------------------------------------

**💻 Práticos (Terminal Linux)**

**🔹 1. Descobrir detalhes da conexão de rede**

Utilize comandos no terminal para exibir:
- O endereço MAC da interface de rede
- O nome da interface de rede ativa
- O status da interface de rede

Dica: Use e ip link show, ifconfig ou ip a.

**🔹 2. Descobrir seu IP externo**

Use um comando para descobrir qual é o seu endereço IP público.
Dica: Utilize curl ifconfig.me wget -q0- ifconfig.me.

**🔹 3. Analisar portas abertas na máquina**

Liste todas as conexões ativas e portas abertas no sistema.

Dica: Use netstat -tulnp ou ss -tulnp.

**🔹 4. Resolver um nome de domínio para endereço IP**

Descubra o IP associado a um domínio (exemplo: www.google.com).

Dica: Use nslookup ou dig.

**🔹 5. Simular um teste de velocidade de rede via terminal**

Verifique a velocidade de usa conexão com a internet diretamente pelo terminal.

**🔹 6. Verificar latência da conexão com diferentes servidores**

Meça o tempo de resposta para diferentes servidores ao redor  do mundo.




