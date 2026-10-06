# 04 - Topologia Física
Topologia: Estrela Estendida com núcleo no Roteador Principal.

Justificativa técnica:
1. Hierarquia: Provedor -> ONT -> Roteador -> Switches/APs
2. Segurança: VLAN 10 Adm+Servidor, VLAN 20 Lab, VLAN 30 Professores, VLAN 99 Visitantes isolada (só internet)
3. Desempenho: Switch dedicado para 20 PCs evita travamento
4. Foco na lógica técnica, não só na beleza.