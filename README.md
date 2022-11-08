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
  <img src="https://user-images.githubusercontent.com/24874487/200634700-71acbaeb-db71-42c2-9cdb-a00f60c31da3.JPG" width="450" title="Comparação On-premises x Virtualização x AWS">
</p>


Vantagens da AWS sobre um ambiente On-premises

Um ambiente On-premises é aquele onde é preciso adquirir servidores, possuir um datacenter, ativos de redes, storages, swithces, routeradores, fazer a parte energetica, cabeamento de redes, etc.

Desvantagens

As perguntas que devemos fazer são:

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

<p align="center">
  <img src="https://user-images.githubusercontent.com/24874487/200639368-863f2001-b406-44d5-8e26-a77e6a2cb9ac.JPG" width="450" title="Comparação On-premises x Virtualização x AWS">
</p>


Aula 02: Certificações AWS

Recursos:

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