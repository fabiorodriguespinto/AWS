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