Treinamento completo em AWS

Seção 1: Introdução

Aula 01: Introdução a Computação em Nuvem através da AWS

Recursos:

http://nuvym.com/beneficios-cloud/


http://nuvym.com/amadurecimento-cloud/


http://nuvym.com/devops/


Arquivo introducao.pptx

Aula 02: Certificações AWS

Recursos:

https://aws.amazon.com/pt/certification/


Tarefa01: Descreva as diferenças entre os níveis das seguintes certificações AWS:

Cloud Practitioner
Associate
Professional
Specialty


Aula 03:

Analise de Custos, cálculo de TCO e classificação de instancias - 19min

Tarefa02: Vantagens da AWS sobre On-premises

Fale das vantagens da AWS sobre On-premises, bem como sobre sua calculadora e a ferramenta de análise de TCO, descreva os casos de uso de instâncias sob demanda, spot ou reservadas.


Tarefa03: Verificação de aprendizagem

Tarefa04: Acesse o site da AWS


Seção 2: IAM - Identity and Access Management

Aula 04: IAM

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


É um serviço é uma CDN (Content Delivery Network) rápida, na qual é possível distribuir conteúdo WEB globalmente, com baixa latencia, baseado na localização de usuários, páginas e dos servidores de conteúdo.

Terminologia:

Edge locations - é um local onde o conteúdo web é cacheado, estaõ distribuidos globalmente, não utilizados exclusivamente pleo cloudfront.

Origin - é a origem 

Aula 09: Aula Pratica CloudFront | Integração com outros serviços AWS

Tarefa06: Questionário

Aula prática sobre o CloudFront



Aula 01:
Aula 01:

