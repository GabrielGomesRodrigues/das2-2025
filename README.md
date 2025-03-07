Design e Arquitetura de Software 2

## Gabriel Gomes Rodrigues

## Aula 27/02/2025

Design trade-offs - é fazer escolher, quando for fazer um sistema(escolher a linguagem as tecnologias, normalmente a que voce mais conhece)
-Consistencia
-Durabilidade
-Latencia
-Estabiliade
Normalmente um sistema nao tem como ter todos os pontos por conta do susto
Cache memoria temporaria que resolveria problemas de banco de dados lotados e lentos
Na maioria dos casos quando tiver uma demanda maior momentania de servidores é muito vantajoso alugar maquinas apenas para o momento, com alertas que avisam e ja ligam essas maquinas. Nesse caso melhora em varios pontos, mas a desvantem seria o valor que fica maior
# das2-2025


Aula 06/03/2025
IAC (Infrastructure as Code) – Automatizar os processos (exemplo: servidor caiu às 2 da manhã).
Tratar os recursos como descartáveis (nunca ter servidores "sagrados" com nomes personalizados).
Evitar acoplamento – anti-pattern.
Para alta disponibilidade, é essencial ter redundância.
O que importa não é a máquina, mas sim o serviço permanecer no ar.
