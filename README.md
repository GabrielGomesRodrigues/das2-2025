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

## Aula 06/03/2025

IAC (Infrastructure as Code) – Automatizar os processos (exemplo: servidor caiu às 2 da manhã).
Tratar os recursos como descartáveis (nunca ter servidores "sagrados" com nomes personalizados).
Evitar acoplamento – anti-pattern.
Para alta disponibilidade, é essencial ter redundância.
O que importa não é a máquina, mas sim o serviço permanecer no ar.

## Aula 06/03

Trade-Offs: Escolhas estratégicas que equilibram benefícios e custos, como desempenho vs. custo.

Evitar Ponto Único de Falha: Implementação de redundância para garantir alta disponibilidade.

Otimização de Custo: Estratégias para reduzir gastos sem comprometer a performance.

Uso de Cache: Melhoria de desempenho armazenando dados acessados com frequência.

Proteger sua Infraestrutura: Medidas de segurança para evitar ataques e falhas.

Infraestrutura Global da AWS: Rede distribuída para oferecer serviços resilientes.

Regiões: Áreas geográficas separadas onde a AWS opera seus serviços.

Zonas de Disponibilidade: Conjuntos de data centers independentes dentro de uma região.

Local Zones: Extensões de regiões para baixa latência.

Data Centers: Instalações físicas onde os servidores da AWS operam.

## Aula 10/03

Infraestrutura Global da AWS: Estrutura distribuída para garantir escalabilidade e resiliência.

POPs - Edge Locations: Pontos de presença para entrega rápida de conteúdo.

Segurança: Conjunto de práticas para proteger dados e sistemas.

Modelo de Responsabilidade Compartilhada: Divisão de responsabilidades entre AWS e cliente.

Autenticação: Verificação de identidade do usuário.

Autorização: Controle de permissões de acesso.

Princípio do Privilégio Mínimo: Conceder apenas as permissões essenciais.

Criptografia: Proteção de dados por meio de técnicas de codificação.

## Aula 13/03

Modelo de Responsabilidade Compartilhada: Cliente gerencia segurança dos dados, AWS da infraestrutura.

Princípio do Privilégio Mínimo: Redução de riscos limitando acessos desnecessários.

Autenticação: Confirmação de identidade do usuário.

Autorização: Definição de permissões para ações e recursos.

Identity and Access Management (IAM): Serviço de controle de acesso na AWS.

Usuários: Contas individuais com permissões definidas.

Acesso pela Console / Programático: Interface gráfica vs. acesso via API/CLI.

## Aula 17/03

Policy de Identidade: Permissões associadas a usuários, grupos e funções.

Policy de Recurso: Definição de acesso em nível de recurso.

S3: Serviço de armazenamento escalável da AWS.

## Aula 24/03

S3 - Gerenciamento de Ciclo de Vida: Regras para arquivamento e exclusão automática de objetos.

S3 - Versionamento: Controle de versões para recuperação de arquivos modificados.

S3 - CORS: Configuração de permissões para acesso a recursos de diferentes domínios.

## Aula 27/03

Códigos S3

## Aula 31/03

Códigos S3

## Aula 03/04

EC2 (Elastic Compute Cloud): Serviço da AWS que permite criar e gerenciar servidores virtuais (instâncias) com diferentes configurações de CPU, memória e rede.

EBS (Elastic Block Store): Armazenamento em blocos usado por instâncias EC2. Funciona como um disco rígido persistente, podendo ser anexado, removido e redimensionado conforme necessário.

AMI (Amazon Machine Image): Modelo usado para lançar instâncias EC2. Contém o sistema operacional, configurações, apps e dados necessários para inicializar o servidor.

## 07/04

Placement:
Cluster: Alto desempenho, baixa latência, menos tolerante a falhas.
Spread: Alta disponibilidade, instâncias bem distribuídas.
Partition: Isolamento físico por grupos, ideal para cargas distribuídas.

EC2 Purchase Model:
On-Demand: Flexível, sem compromisso, mais caro.
Reserved: Compromisso de 1/3 anos, mais barato.
Savings Plans: Desconto com flexibilidade, baseado em gasto/hora.
Spot: Muito barato, mas pode ser interrompido.

## 10/04

RDS: Serviço gerenciado da AWS para bancos de dados relacionais. Cuida de backups, patching, e alta disponibilidade.

Bancos de dados relacionais: Organizam dados em tabelas com esquema fixo (ex: MySQL, PostgreSQL). Usam SQL e garantem consistência.

Bancos de dados não relacionais: Mais flexíveis, sem esquema fixo (ex: DynamoDB, MongoDB). Ideais para dados semi-estruturados e escalabilidade horizontal.

## Aula 05/05

VPC (Virtual Private Cloud):
É uma rede virtual isolada dentro da nuvem (como na AWS), onde você pode definir sua própria estrutura de rede (IPs, sub-redes, rotas, etc.). Permite que recursos como máquinas virtuais (EC2) se comuniquem de forma segura.

CIDR (Classless Inter-Domain Routing):
É a notação usada para definir intervalos de endereços IP. Exemplo: 192.168.0.0/24 indica uma rede com 256 endereços IP. O número após a barra (/24) define quantos bits são usados para a parte da rede.

Subnet Pública:
É uma sub-rede dentro da VPC que permite acesso à internet. Para ser pública, deve:

Estar associada a uma route table com rota para o internet gateway

Ter instâncias com endereços IP públicos ou elásticos

## Aula 12/05
Fazer os laboratórios Canvas
Guided lab: Creating a Virtual Private Cloud Challenge (Cafe)
lab: Creating a VPC Networking 
Environment for the Café
Atividades Feitas
