Treinamento completo em AWS

Seção 1: Introdução

Aula 01: Introdução a Computação em Nuvem através da AWS

Recursos:

Benefícios da Computação em nuvem:
http://nuvym.com/beneficios-cloud/

Amadurecimento no uso de Computação em nuvem:
http://nuvym.com/amadurecimento-cloud/

DEVOPS - Tratando sua infraestrutura como códico:
http://nuvym.com/devops/

Arquivo introducao.pptx

<p align="center">
  <img src="https://user-images.githubusercontent.com/24874487/200634700-71acbaeb-db71-42c2-9cdb-a00f60c31da3.JPG" width="450" title="S1A1_Imagem01">
</p>

Vantagens da AWS sobre um ambiente On-premises

Um ambiente On-premises é aquele onde é preciso adquirir servidores, possuir um datacenter, ativos de redes, storages, swithces, routeradores, fazer a parte energetica, cabeamento de redes, etc.

Desvantagens

As desvantagens são:

1 - Tempo

Qual o tempo para adiquirir (comprar) um servidor;
Qual o tempo para configuração do servidor;
Qual o tempo para instalação do sistema operacional;
Qual o tempo para configuração do sistema operacional;
Qual o tempo para instalação da aplicação desejada;
Qual o tempo para configuração da aplicação;

Diante de tudo isso, qual o tempo total até que a aplicaçaõ esteja no ar?

2 - Alto custo

Qual o custo do datacenter?
Qual o custo do servidor?
Qual o custo dos ativos de rede?
Qual o custo dos licenciamentos de softwares necessários a aplicação?

Até que a aplicação esteja no ar, há um alto custo envolvido. 

Após surgiu a virtualização onde o hardware é abstraido e é possivel ter diversos sistemas operacionais sobre uma infraestrutura virtualizada.

A AWS é uma extensão de um ambiente virtualizado, algo como o próximo passo evolutivo.

Vantagens da AWS:

1 - Umas das vantagens da AWS é a robusta e extença infraestrutura cloud já implementada na forma de serviços, incluindo segurança, redundancia, alta disponibilidade.

A AWS usa o conceito de regiões, onde há de uma infraestrutura global de datacenters contendo todos os serviços que a AWS oferece.

<p align="center">
  <img src="https://user-images.githubusercontent.com/24874487/200639368-863f2001-b406-44d5-8e26-a77e6a2cb9ac.JPG" width="450" title="S1A1_Imagem02">
</p>

A durabilidade de dados (11 x 9's) na AWS e latência de rede que acontece através de reduncias entre os datacenters e/ou balanceamento de carga entre os datacenters que são zonas de disponibilidade e conectados por links de dados de altissima velocidade que formam uma região.

<p align="center">
  <img src="https://user-images.githubusercontent.com/24874487/200643291-4cffc30c-05b2-4eed-b1b1-9fe371532a26.JPG" width="450" title="S1A1_Imagem03">
</p>

AWS trabalha com um modelo de responsabilidade compartilhada

<p align="center">
  <img src="https://user-images.githubusercontent.com/24874487/200652670-58ae3b37-2acb-42b4-897e-591bca762261.JPG" width="450" title="S1A1_Imagem04">
</p>

Gama de serviços da AWS

<p align="center">
  <img src="https://user-images.githubusercontent.com/24874487/200652860-b709487a-53ad-47d1-b388-bb35a7cbc160.JPG" width="450" title="S1A1_Imagem05">
</p>

Diferenças entre os serviços da AWS

<p align="center">
  <img src="https://user-images.githubusercontent.com/24874487/200652957-43fc95e3-51d8-49b9-bf40-d7a26768d3d4.JPG" width="450" title="S1A1_Imagem06">
</p>

Aula 02: Certificações AWS

Recursos:

AWS - Certificações:
https://aws.amazon.com/pt/certification/


Tarefa01: Descreva as diferenças entre os níveis das seguintes certificações AWS:

Cloud Practitioner
Associate
Professional
Specialty


Aula 03: Analise de Custos, cálculo de TCO e classificação de instancias - 19min

Recursos:

Calculadora de custos mensais da AWS:
https://calculator.s3.amazonaws.com/index.html

Calculadora de TCO da AWS:
https://calculator.aws/#/

Definição de preço do Amozon EC2:
https://aws.amazon.com/pt/ec2/pricing/on-demand/

Habilitar e desabilitar o monitoramento detalhado para suas instancias:
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/using-cloudwatch-new.html

Centro de informações sobre a nuvem:
https://aws.amazon.com/pt/economics/



Tarefa02: Vantagens da AWS sobre On-premises

Fale das vantagens da AWS sobre On-premises, bem como sobre sua calculadora e a ferramenta de análise de TCO, descreva os casos de uso de instâncias sob demanda, spot ou reservadas.


Tarefa03: Verificação de aprendizagem

Tarefa04: Acesse o site da AWS


Seção 2: IAM - Identity and Access Management

Aula 04: IAM

Recursos:

AWS SSO:
https://aws.amazon.com/pt/iam/identity-center/

Autenticação e controle de acesso do AWS SSO:
https://docs.aws.amazon.com/pt_br/singlesignon/latest/userguide/iam-auth-access.html

AWS Diretory Service:
https://aws.amazon.com/pt/directoryservice/

Arquivo Iam.pptx

Serviço principal da AWS - Será configurado usuários, grupos, roles, credenciais, níveis de acesso, permissões, politicas.
Permiti add um provedor de autenticação externo (Active diretory) para usar 

Roles são regras de acesso a serviços
Politicas de acesso são doctos json

Dois tipos de acesso, a CLI (linha de comando) e a console do IAM - interface web e acessos para APIs.

Aula 05: Gerenciando o IAM - Aula prática


Tarefa05: Estude mais sobre o IAM

Acesse a documentação oficial do IAM

Simulado01: - IAM

É necessário ter 70% de acertos para ser aprovado

Simulado sobre o IAM, com foco na prova de certificação.


Instruções:

Você pode pausar o teste a qualquer momento e retomar mais tarde.
Você pode refazer o teste quantas vezes quiser.
A barra de progresso na parte superior da tela mostrará o progresso, bem como o tempo restante no teste. Se o tempo se esgotar, não se preocupe, pois você ainda poderá concluir o teste.
Você pode pular uma pergunta para voltar no final do exame.
Se preferir, você pode usar a opção "Marcar para revisão" e rever as perguntas em que ainda tem dúvidas antes de enviar o teste.
Se você quiser concluir o teste e ver seus resultados imediatamente, pressione o botão Parar.


Seção 3: S3 - Simple Storage Service

Aula 06: Introdução ao S3 e suas caracteristicas

Recursos:

AWS - Introdução ao S3
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html

AWS - Precificãção do S3
https://aws.amazon.com/pt/s3/pricing/

AWS - Versionamento do S3
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Versioning.html

AWS - Exemplos de politicas do bucket S3
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/example-bucket-policies.html

AWS - Conteúdo da prova - Modelo de consistencia de dados do S3
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html#ConsistencyModel

AWS - Conteúdo da prova - Criptografia no S3
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingEncryption.html

AWS - Replicação S3
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/replication-what-is-isnot-replicated.html

AWS - Elementos de configuração do ciclo de vida
https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/intro-lifecycle-rules.html

AWS - Remoção de marcadores de exclusão
- Validar link ??

Arquivo S3.pptx

Serviços de armazenamento ilimitado gerenciavel (Gereciamento é feito de forma automatica pela AWS), provê o armazenamento de dados com segurança durabilidade e escalabilidade.

- Baseado em objetos;
- Acessos pela console web, CLI e API
- Dados são replicados em multiplos datacenters, 99,99999999999 (11 x 9's)
- Arquivos (objetos) são armazenados em buckets que são similares a diretorios ou pastas em um sistema operacional.
- Os nomes de bucket são universais, precisam ser compativeis com a entrada DNS
Ex.: https://myawsbucket.s3.amazonaws.com

É gerado um código de sucesso HTTP 200 qdo um objeto é transferido para o S3. 
- Upload de arquivos que podem ser de 0 Bytes a 5TB 

- Os objetos armazenados no S3 consistem em:
Chave: Nome do objeto;
Valor: dados armazenados;
Metadados: informações sobre os objetos (data, tamanho, storage class, versionamento, etc);
ACL's: listas de controle de acesso.

- Recursos do S3
Gerenciamento de ciclo de vido;
Versionamento;
Criptografia;
Controle de acesso baseado em ACL's (Para objetos) e Bucket Policies.

Classes de armazenamento


Aula 07: S3 na prática

Criação de bucket

Buckets são regionais, precisam ter nomes compatíveis com DNS, podem ser configurados, com relaçao a segurança, permissições
Por padrão um bucket é privado e não é possível alterar, para criar um bucket publico é necessário configurar as permissões no momento da criação.


Seção 4: CloudFront

Aula 08: CloudFront

Recursos:

AWS - CloudFront
https://aws.amazon.com/pt/cloudfront/

Arquivo CloudFront.pptx

É um serviço é uma CDN (Content Delivery Network) rápida, na qual é possível distribuir conteúdo WEB globalmente, com baixa latencia, baseado na localização de usuários, páginas e dos servidores de conteúdo.

Terminologia:

Edge locations - é um local onde o conteúdo web é cacheado, estaõ distribuidos globalmente, não utilizados exclusivamente pleo cloudfront.

Origin - é a origem 

Aula 09: Aula Pratica CloudFront | Integração com outros serviços AWS

Recursos:

AWS - Valores especificados ao criar ou atualizar uma distribuição CloudFront:
https://docs.aws.amazon.com/pt_br/AmazonCloudFront/latest/DeveloperGuide/distribution-web-values-specify.html#DownloadDistValuesOAIRestrictBucketAccess

AWS - Utilizando URLs amigáveis:
https://docs.aws.amazon.com/pt_br/AmazonCloudFront/latest/DeveloperGuide/CNAMEs.html#CreatingCNAME

Tarefa06: Questionário

Aula prática sobre o CloudFront

Seção 5: Storage Gateway

Aula 10: Storage Gateway

Recursos:

AWS - Como implantar um Gateway de arquivos em host do Amazon EC2:
https://docs.aws.amazon.com/pt_br/storagegateway/index.html

AWS - Como criar um Gateway de volume:
https://docs.aws.amazon.com/pt_br/storagegateway/index.html

Wikipédia - iSCSI:
https://pt.wikipedia.org/wiki/ISCSI

Wikipédia - NFS
https://pt.wikipedia.org/wiki/Network_File_System

Como criar um Gateway de arquivos
https://docs.aws.amazon.com/pt_br/storagegateway/index.html

Arquivo Storage-gateway.pptx


Funcionamento do Storage Gateway.

É um serviço que possibilita a sua rede On-premises utilizar a infraestrutura de armazenamento da AWS de forma segura, ágil e escalável.
É possivel utilizar para backup e arquivamento, disaster recovery, processamento em nuvem e migrações.



Aula 11: Aula prática - Storage Gateway

Tarefa07: Storage Gateway

Tarefa sobre o Storage Gateway

Seção 6: Snowball

Aula 12: Snowball

Recursos:

Snowball:
https://aws.amazon.com/pt/snowball/

Arquivo Snowball.pptx

Facilita transferência de grandes quantidades de dados para a AWS.
Dividido em 3 categorias

Snowball - 
Snowball Edge
Snowmobile

Seção 7: EC2

Aula 13: EC2

Recursos:

Tipos de instância do Amazon EC2:
https://aws.amazon.com/pt/ec2/instance-types/

Tipos de volume do Amazon EBS:
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/ebs-volume-types.html

Instâncias reservadas do Amazon EC2:
https://aws.amazon.com/pt/ec2/pricing/reserved-instances/

Instâncias spot do Amazon EC2:
https://aws.amazon.com/pt/ec2/spot/

Volume do dispositivo raiz da instância do Amazon EC2:
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/RootDeviceStorage.html

Arquivo EC2.pptx

Um dos serviços mais importantes da AWS, não é gerenciado

É um web service que provê capacidade computacional de forma vertical (Aumenta recursos da instancia) e horizontal (Aumenta a quantidade de instancias).

Possui 4 tipos de execução:

On-demand - Por demanda, pago por hora ou segundo de uso.

Reservadas - Paga-se adiantada por 1 ou 3 anos, o valor é bem mais atrativo.

Spot - Algo como um leilão, ao chegar no valor o lançe, começa a utilizar e esta pode ser finalizada a qualquer momento.

Host dedicados - Um host é reservado para o uso, pode-se trazer a licença dos sistemas operacionais e de softwares.

As instancias EC2 possuem vários tipos de armazenamentos:

Volumes raiz - Volumes bootaveis

Volumes EBS - Usado para armazenar dados, criar o volume EBS e depois o sistema de arquivos. O ideal é que os volumes EBS fiquem na mesma zona de disponibilidade onde a instancia foi criada.

Tipos de volumes EBS:

General Purpose SSD gp2 - Balanciado ente preço e performance.

Provisioned IOPS SSD io1 - Aplicações que fazem uso itensivo de leitura e escrita.

Cold HDD sc1 - Armazenamento de baixo custo, dados não acessados frequentimente

Throughput optimized hdd st1 - alta vazão de dados, usado para bid data, datawarehouse.

Magnetic (standard) - Custo mínimo de armazenamento.


Aula 14: EC2 - Aula prática

Recursos:

Grupos de posicionamento:
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/placement-groups.html

Amazon EC2 já oferece reservas de capacidade sob demanda:
https://aws.amazon.com/pt/about-aws/whats-new/2018/10/Amazon-EC2-now-offers-On-Demand-Capacity-Reservations/

Modo ilimitado de instâncias expansíveis:
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/burstable-performance-instances-unlimited-mode.html

Executar comandos na instância do Linux no lançamento
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/user-data.html

Conectar-se à instância do Linux no Windows usando PuTTY
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/putty.html


Aula 15: EC2 - Aula prática - Avançado

Recursos:

Grupos de segurança do Amazon EC2 para instâncias do Linux:
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/ec2-security-groups.html

Armazenamento de instâncias do Amazon EC2:
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/InstanceStorage.html

Amazon Elastic Block Store (EBS):
https://aws.amazon.com/pt/ebs/

Criar snapshots de Amazon EBS:
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/ebs-creating-snapshot.html

Imagens de máquina da Amazon (AMIs):
https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/AMIs.html


Aula 16: Balaceamento de carga - Load Balancer

Recursos:

Elastic Load Balancing:
https://aws.amazon.com/pt/elasticloadbalancing/?nc1=h_ls

Cabeçalhos HTTP e balanceadores de carga clássicos:
https://docs.aws.amazon.com/pt_br/elasticloadbalancing/latest/classic/x-forwarded-headers.html


São 3 os tipos de balaceamentos de carga na Amazon

Application Load Balancer
Network Load Balancer
Classic Load Balancer


Aula 17: Balaceamento de carga - Aula Prática


Aula 18: Roles - Permitindo uma instânica Ec2 acesso total ao S3 - Aula Prática

Recursos:

Funções do IAM:
https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_roles.html


Aula 19: Aula prática - automatizando tarefas simples na inicialização de uma instância


Aula 20: Aula prática - Metadados da instância


Aula 21: CloudWatch


Aula 22: AutoScaling

Faz o scalonamento de instancias EC2 para cima ou para baixo.

Aula 23: EFS - Elastic File System (NFS)

Recursos:

Amazon Elastic File System:
https://aws.amazon.com/pt/efs/

Armazenamento de arquivos na nuvem:
https://aws.amazon.com/pt/what-is/cloud-file-storage/

FreeBSD - NFS Handbook
https://docs.freebsd.org/en/books/handbook/network-servers/#network-nfs


Éum sistema de arquivos em blocos no qual um HD é exportado das suas maquinas para instancias EC2, é um disco rigido remoto, acesso via protocolo NFS (Network File System) versão 4 ou superior. O espaço em disco é redimensionado conforme a necessidade - escalabilidade automativa, latencia baixa dependendo da configuração, reduncia qdo configuração em várias zonas de disponibilidade, alta disponibilidade e resiliencia.

Aula 24: Lambda

Recursos:

AWS Lambda:
https://aws.amazon.com/pt/lambda/

Perguntas frequentes sobre o AWS Lambda:
https://aws.amazon.com/pt/lambda/faqs/

Criação de aplicações com arquiteturas sem servidor:
https://aws.amazon.com/pt/lambda/serverless-architectures-learn-more/


<p align="center">
  <img src="https://user-images.githubusercontent.com/24874487/200652957-43fc95e3-51d8-49b9-bf40-d7a26768d3d4.JPG" width="450" title="S7A24_Imagem01">
</p>


O Lambda faz parte da arquitetura Serverless.



Teste 1: Questionário sobre EC2, focado na prova de certificação. 23 Perguntas.


Seção 8: Route 53


Aula 25:  Route 53

O route 53 é o serviço de DNS da AWS.


Aula 26:  Route 53 - Weighted Routing Policy


Aula 27:  Route 53 - Latency

Deve-se configurar o servidor DNS para a zona onde o servidor possuir a menor latência.


Aula 28:  Route 53 - Failover

Politica de failover, que é a checagem de falha


Aula 29:  Route 53 - Geolocation


Aula 30:  Route 53 - Multivalue Answer

qualquer requisição sempre serão respondidos pelos dois sites.

Teste 2: Route 53


Seção 9: Bancos de Dados


Aula 31: AWS - Bancos de Dados

Recursos:

Relational Database Service (RDS)
https://aws.amazon.com/pt/rds/

O que é NoSQL?:
https://aws.amazon.com/pt/nosql/

Amazon DynamoDB:
https://aws.amazon.com/pt/dynamodb/

Conceitos de Data Warehouse:
https://aws.amazon.com/pt/data-warehouse/

Amazon Redshift:
https://aws.amazon.com/pt/redshift/

Amazon ElastiCache:
https://aws.amazon.com/pt/elasticache/

Arquivo S9A31_RDS.pptx.


Serviço gerenciado (A AWS gerencia a infraestrutura) de banco de dados relacionais.

Aula 32: RDS - Aula prática - Aurora

Recursos:

Criar uma instância de banco de dados MySQL e conectar-se a um banco de dados em uma instância de banco de dados MySQL:
https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/CHAP_GettingStarted.CreatingConnecting.MySQL.html

Implantações Multi-AZ do Amazon RDS:
https://aws.amazon.com/pt/rds/features/multi-az/

Réplicas de leitura do Amazon RDS:
https://aws.amazon.com/pt/rds/features/read-replicas/

Modificar uma instância de banco de dados do Amazon RDS

Aula 33: DynamoDB

Aula 34: Redshift

Aula 35: Elasticache

Solução de cache baseada em web service, pode melhor consideravelmente o acesso a serviços comumente acessados.
O cache é armazenado em mémoria que é muito mais rápido que acessar a informação em disco ou BD.

ElastiCache é

Teste 3: Bancos de Dados


Seção 10: Serviços de Aplicação


Aula 36: SQS (Simple Queue Service)

Recursos:

Amazon Simple Queue Service (SQS):
https://aws.amazon.com/pt/sqs/

Consumo de mensagens usando a sondagem longa:
https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-short-and-long-polling.html#sqs-long-polling

Perguntas frequentes sobre o Amazon SQS:
https://aws.amazon.com/pt/sqs/faqs/

Arquivo S10A36_SQS.pptx


Serviço de mensagem da AWS

Como funciona?

Aula 37: SWF (Simple Workflow Service)


Recursos:

Amazon Simple Workflow Service (SWF):
https://aws.amazon.com/pt/swf/

Desenvolver um operador de atividade no Amazon SWF:
https://docs.aws.amazon.com/pt_br/amazonswf/latest/developerguide/swf-dg-develop-activity.html

Recursos da Web para o Amazon Simple Workflow Service:
https://docs.aws.amazon.com/pt_br/amazonswf/latest/developerguide/resources-web.html


Gerenciador de fluxos de trabalho orientado a tarefas.

Mais de 500 mili segundos

Assegura que a tarefa apenas uma vez. Alem de cordenar a lógica de execução, ou seja, após uma tarefa for executa, a próxima tarefa é chamada para ser executada.


Aula 38: SNS (Simple Notification Service)


Recursos:

Amazon Simple Notification Service (SNS):
https://aws.amazon.com/pt/sns/

Definição de preço do Amazon SNS:
https://aws.amazon.com/pt/sns/pricing/

Serviço de publicação de mensagens

Mensagens são armazenadas em zonas de disponibilidade diferentes, isso assegura que as mensagens não serão perdidas.


Aula 39: Elastic Transcoder

Conversor de arquivos de mídia

Recursos:

Amazon Elastic Transcoder:
https://aws.amazon.com/pt/elastictranscoder/


Aula 40: API Gateway

Gateway para as suas APIs

Usado para integrar as aplicações com outros serviços AWS.

Recursos:

Amazon API Gateway:
https://aws.amazon.com/pt/api-gateway/

Recursos do Amazon API Gateway:
https://aws.amazon.com/pt/api-gateway/features/


Aula 41: Kinesis

Serviço da AWS para trabalhar com streaming de dados.

Recursos:

O que são dados em streaming?:
https://aws.amazon.com/pt/streaming-data/

Amazon Kinesis Data Streams:
https://aws.amazon.com/pt/kinesis/data-streams/

Amazon Kinesis Data Firehose:
https://aws.amazon.com/pt/kinesis/data-firehose/

Amazon Kinesis Data Analytics:
https://aws.amazon.com/pt/kinesis/data-analytics/


Aula 42: Laboratório - Kinesis

Recursos:

DevOps:
http://nuvym.com/devops/

Ansible:
https://aws.amazon.com/marketplace/pp/prodview-nysmxgv7brv5g

AWS CloudFormation:
https://aws.amazon.com/pt/cloudformation/


Teste 4: Questionário


Seção 11: VPC - Virtual Private Cloud

Aula 43: VPC

Recursos:

Como funciona a Amazon VPC:
https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/how-it-works.html#vpc-subnet-basics

Rede Privada:
https://pt.wikipedia.org/wiki/Rede_privada

CIDR - Classless Inter-Domain Routing
https://pt.wikipedia.org/wiki/Roteamento_entre_dom%C3%ADnios_sem_classes

Gateway endpoints:
https://docs.aws.amazon.com/pt_br/vpc/latest/privatelink/gateway-endpoints.html

Gateways da Internet somente de saída:
https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/egress-only-internet-gateway.html

AWS NAT:
https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-nat.html

Emparelhamento da VPC:
https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-peering.html

Conjuntos de opções DHCP no Amazon VPC:
https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/VPC_DHCP_Options.html

Como usar o DNS com sua VPC:
https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-dns.html




