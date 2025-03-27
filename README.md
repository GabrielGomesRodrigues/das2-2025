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

Aula 24/03
S3 - Gerenciamento de Ciclo de Vida: Regras para arquivamento e exclusão automática de objetos.

S3 - Versionamento: Controle de versões para recuperação de arquivos modificados.

S3 - CORS: Configuração de permissões para acesso a recursos de diferentes domínios.








