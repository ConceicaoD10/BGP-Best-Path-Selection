

 🌐 Laboratório BGP – Best Path Selection

Este laboratório teve como objetivo consolidar os principais critérios e atributos usados pelo Border Gateway Protocol (BGP) no processo de seleção da melhor rota. Através de um ambiente multi-AS, foram recriadas situações reais encontradas em provedores de internet e redes corporativas, permitindo a manipulação prática de cada atributo que influencia a escolha do melhor caminho.

🔹 Etapas abordadas

 ⚙️ Configuração inicial de endereçamento IPv4, IGPs (quando necessários) e sessões iBGP/eBGP.
 📡 Anúncio de rotas nativas e redistribuídas entre diferentes Sistemas Autônomos (AS).
 🎯 Manipulação do Weight e Local Preference, controlando preferências de saída do AS.
 🧩 Criação de agregações com AS-SET, preferindo rotas locais e específicas.
 🛠️ Demonstração do impacto de AS-Path Prepending e da escolha por rotas com menor comprimento de AS_PATH.
 🔍 Alterações de atributos como Origin e MED, explorando ainda conceitos como Always Compare MED e Deterministic MED.
 🔗 Diferença entre seleção de rotas eBGP versus iBGP, influência do NEXT_HOP IGP, Router ID e até Cluster List em ambientes com Route Reflectors.
 ⚖️ Testes práticos de BGP Multipath, com balanceamento de tráfego em cenários de atributos idênticos.

🔹 Resultados
O laboratório reforçou como cada atributo pode ser manipulado de forma estratégica para:
✅ Controlar fluxos de tráfego
✅ Definir políticas de engenharia de tráfego
✅ Preparar o ambiente para redes multi-homed e provedores de serviços.

📂 O repositório contém as configurações utilizadas e 📸 prints das saídas de verificação (`show ip bgp`, `show ip route`, etc.), servindo como referência prática para estudo e aplicação em cenários reais.

