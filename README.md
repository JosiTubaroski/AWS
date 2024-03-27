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

- 1) Load Balancing (Balanceamento de Carga): O Elastic Load Balancing (ELB) é o serviço de balanceamento de carga da AWS, projetado para distribuir automaticamente
  o tráfego de entrada entre várias instâncias de aplicativos ou recursos, garantindo que nenhuma instância fique sobrecarregada. Existem três tipos de balance de carga:
  Application Load Balance (ALB), Network Load Balance(NLB) e Classic Load Balancer. Eles oferecem recursos avançados, como roteamento de tráfego baseado em conteúdos,
  integração com serviços da AWS e suporte a protocolos variados para atender às necessidades especificas dos aplicativos.

-  2) Auto Scaling (Dimensionamento Automático): O serviço Auto Scaling permite que você ajuste automaticamente o numério de instancias de aplicativos conforme a demanda
   de tráfego ou carga de trabalho varia. Ele ajuda a manter a disponibilidade e o desempenho do aplicativo adicionando instâncias quando a demanda aumenta e removendo-as
   quando a demanda diminui. O Auto Scaling pode ser configurado para escalar horizontalmente (adicionando ou removendo instâncias) com base em métricas de desempenho, como
   utilização da CPU, ou em horários especificos do dia.

### 09: ARCHITECT - Database AWS

### 10: DNS, Cache e Performance

### 11: Block e File Storage

### 12: ARCHITECT - Aplicações AWS

### 13: Serverless Lambda

### 14: Segurança na Cloud

### 15: ARCHITECT - Finalizando




