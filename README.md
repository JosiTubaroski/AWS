# AWS (Amazon Web Services) Cloud Computing

A Amazon Web Services(AWS) é uma plataforma de computação em nuvem oferecida pela Amazon.com. Ela fornece uma variedade de serviços de computação em nuvem, incluindo armazenamento, computação, banco de dados, análise, machine learning,
Internet das Coisas (IoT), segurança e muito mais.

Imagem de um Data Center AWS

<img src="https://github.com/JosiTubaroski/AWS/blob/main/IMG/01_Data_Center.png">


### 01: Os Conceitos de Cloud Computing

É transferido o data center tradicional de dentro das empresas para a AWS poupando espaço e custos com hardwares, manutenções entre outros.

Lista de Benefícios:

1. Velocidade para implementação e desenvolvimento de soluções, é possivel iniciar e assinar serviços em segundos
2. Realizar os updates de atualizações Sistemas Operacionais por exemplo (As manutenções são realizadas sem interromper o serviço)
3. Custo muito mais baixo do que o normal.
4. Data Security (Com estrutura de backup)
5. Escalabilidade que pode ser automática ou manual

### 02: IAM e Access Management

IAM (Identity and Access), um serviço da AWS que permite gerenciar o acesso aos recursos da AWS de forma centralizada. Ele permite criar e gerenciar usuários e grupos de usuários,
bem como definir permissões granulares sobre quais recursos da AWS eles podem acessar e quais ações podem realizar.

### 03: ARCHITECT - Armazenamento AWS

- O serviço S3 (Simple Storage Service) da AWS é um serviço de armazenamento altamente escalavel.

- O S3 permite que você aramazene virtualmente qualquer tipo de objeto, como arquivos de mídia, backups de banco de dados, arquivos de log, conteudos estáticos de sites e muito mais.
- Ele fornece uma interface simples e robusta para upload, download e gerenciamento de objetos, além de oferecer recursos avançados, como controle de acesso granular, criptografia de dados, versionamento de objetos e capacidade de configurar políticas de ciclo de vida para automatizar a movimentação e expiração de objetos.

### 04: ARCHITECT - Servidores EC2

- Com o EC2, você pode lançar virtualmente qualquer tipo de servidor, seja ele para hospedar um site, executar um aplicativo, processar grandes quantidades de dados ou até mesmo criar um
  ambiente de desenvolveimento ou teste. O EC2 oferece uma ampla variedade de tipos de instância com diferentes configurações de CPU, memória, armazenamento e capacidade de rede para
  atender às necessidades especificas de diferentes cargas de trabalho.

 - Além disso, o EC2 oferece recursos de escabilidade automática, permitindo que você aumente ou diminua a capacidade de sers servidores de acordo com a demanda, garantindo assim que
   seus aplicativos tenham sempre os recursos necessários disponíveis para lidar com picos de tráfego ou carga de trabalho. 

### 03: ARCHITECT - VPC

O serviço VPC (Virtual Private Cloud) da AWS é uma parte fundamental da infraestrutura de nuvem oferecida pela AWS. O VPC permite que você crie uma rede
virtual isolada na nuvem AWS, na qual você pode lançar recursos de computação, como instâncias EC2, e armazenar dados em serviços com o S3.

### 04: Load Balancers e Auto Scaling

  1)Load Balancing (Balanceamento de Carga): O Elastic Load Balancing (ELB) é o serviço de balanceamento de carga da AWS, projetado para distribuir automaticamente
  o tráfego de entrada entre várias instâncias de aplicativos ou recursos, garantindo que nenhuma instância fique sobrecarregada. Existem três tipos de balance de carga:
  Application Load Balance (ALB), Network Load Balance(NLB) e Classic Load Balancer. Eles oferecem recursos avançados, como roteamento de tráfego baseado em conteúdos,
  integração com serviços da AWS e suporte a protocolos variados para atender às necessidades especificas dos aplicativos.

2)Auto Scaling (Dimensionamento Automático): O serviço Auto Scaling permite que você ajuste automaticamente o numério de instancias de aplicativos conforme a demanda
   de tráfego ou carga de trabalho varia. Ele ajuda a manter a disponibilidade e o desempenho do aplicativo adicionando instâncias quando a demanda aumenta e removendo-as
   quando a demanda diminui. O Auto Scaling pode ser configurado para escalar horizontalmente (adicionando ou removendo instâncias) com base em métricas de desempenho, como
   utilização da CPU, ou em horários especificos do dia.

### 05: ARCHITECT - Database AWS

A Amazon Web Services (AWS) oferece uma ampla gama de serviços de banco de dados para atender às diversas necessidades de armazenamento, processamento e gerenciamento de dados. Alguns dos principais serviços de banco de dados oferecidos pela AWS incluem:

1) Amazon Relational Database Service (RDS): O Amazon RDS oferece uma maneira fácil de configurar, operar e escalar bancos de dados relacionais na nuvem. Ele suporta vários motores de banco de dados, incluindo MySQL, PostgreSQL, SQL Server, Oracle e MariaDB, e gerencia tarefas administrativas, como provisionamento de hardware, backup e patching.

2) Amazon Aurora: Amazon Aurora é um banco de dados relacional compatível com MySQL e PostgreSQL, projetado para ser altamente disponível, durável e escalável. Ele oferece desempenho rápido e custo eficaz, com capacidade de dimensionamento automático para lidar com cargas de trabalho variáveis.

3) Amazon DynamoDB: Amazon DynamoDB é um banco de dados NoSQL totalmente gerenciado, que oferece desempenho rápido e escalabilidade automática para aplicativos que exigem acesso de baixa latência a dados estruturados e semiestruturados. Ele é ideal para aplicativos da web, jogos, IoT e outras cargas de trabalho de alto desempenho.

4) Amazon Redshift: Amazon Redshift é um data warehouse totalmente gerenciado, projetado para análise de dados de grande escala. Ele oferece consultas rápidas e escalabilidade maciça, permitindo que as empresas processem grandes volumes de dados para insights analíticos.

5) Amazon ElastiCache: Amazon ElastiCache é um serviço de cache totalmente gerenciado, que oferece suporte a cache em memória para melhorar o desempenho e a escalabilidade de aplicativos. Ele suporta os mecanismos de cache Redis e Memcached.

6) Amazon Neptune: Amazon Neptune é um serviço de banco de dados de grafo totalmente gerenciado, otimizado para armazenar e consultar conjuntos de dados altamente conectados. Ele suporta o modelo de banco de dados de grafo padrão do W3C (RDF) e a API de consulta de grafo (Gremlin).

### 06: DNS

O serviço de DNS da amazon refere-se ao Amazon Route 53, que é um serviço de sistema de nomes de domínio (DNS) oferecido pela Amazon Web Services (AWS).
O DNS é um sistema fundamental da Internet que traduz nomes de domínio legíveis por humanos, como exemplo.com, em endereços IP numéricos, que são
usados para identificar e localizar dispositivos e serviços na internet.

### 07: Block e File Storage

### 08: ARCHITECT - Aplicações AWS

### 09: Serverless Lambda

### 10: Segurança na Cloud

### 11: ARCHITECT - Finalizando




