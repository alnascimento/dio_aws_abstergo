RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 22/05/2026 Empresa: Abstergo Industries
Responsável: André Nascimento

Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por André Nascimento. O objetivo do projeto foi elencar 3
serviços AWS, com a finalidade de realizar diminuição de custos imediatos, focando nas categorias de Computação, Rede e Armazenamento/Banco de Dados.

Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: Otimização de Custos em Computação com Instâncias Spot do Amazon EC2

Nome da ferramenta: Amazon EC2 Spot Instances
Foco da ferramenta: Redução de custos em cargas de trabalho de computação flexíveis e tolerantes a falhas.
Descrição de caso de uso: As Instâncias Spot do Amazon EC2 permitem que a Abstergo Industries utilize a capacidade ociosa do EC2 a preços significativamente
mais baixos (até 90% de desconto em comparação com as instâncias sob demanda). Para redução imediata de custos, a equipe de André Nascimento identificará cargas de trabalho que podem ser interrompidas e reiniciadas sem impacto crítico, como processamento em lote, tarefas de desenvolvimento/teste, renderização de mídia ou análises de dados. A implementação de Instâncias Spot para essas cargas de trabalho resultará em economia substancial e imediata nos custos de computação, aproveitando a flexibilidade e a tolerância a falhas inerentes a esses tipos de processos.

Etapa 2: Otimização de Custos em Rede com AWS VPC Endpoints

Nome da ferramenta: AWS VPC Endpoints
Foco da ferramenta: Acesso privado e seguro a serviços AWS sem tráfego pela internet pública, reduzindo custos de transferência de dados e NAT Gateway.
Descrição de caso de uso: Os AWS VPC Endpoints permitem que instâncias em uma Virtual Private Cloud (VPC) acessem serviços AWS (como S3 e DynamoDB) de forma privada, sem a necessidade de um gateway NAT ou de tráfego pela internet pública. Para a Abstergo Industries, a implementação de VPC Endpoints para serviços AWS amplamente utilizados internamente eliminará os custos associados ao NAT Gateway e à transferência de dados para a internet pública. Isso proporcionará uma redução imediata nos custos de rede, além de aumentar a segurança e a performance do acesso aos serviços AWS.

Etapa 3: Otimização de Custos em Armazenamento com Amazon S3 Intelligent-Tiering

Nome da ferramenta: Amazon S3 Intelligent-Tiering
Foco da ferramenta: Otimização automática de custos de armazenamento,movendo dados entre camadas de acesso com base nos padrões de uso. 
Descrição de caso de uso: O Amazon S3 Intelligent-Tiering é uma classe de armazenamento que move automaticamente objetos entre três camadas de acesso (acesso frequente, acesso infrequente e acesso de arquivo) quando os padrões de acesso mudam, sem impacto no desempenho ou sobrecarga operacional. Para a Abstergo Industries, a aplicação do S3 Intelligent-Tiering em buckets com dados de acesso variável (por exemplo, logs, backups, arquivos de projeto) garantirá que os dados sejam armazenados na camada de custo mais eficiente. Isso resultará em uma redução imediata e contínua dos custos de armazenamento, pois a ferramenta se adapta dinamicamente aos padrões de acesso aos dados.

Conclusão

A implementação das ferramentas Amazon EC2 Spot Instances, AWS VPC Endpoints e Amazon S3 Intelligent-Tiering na empresa Abstergo Industries tem como esperado
redução significativa e imediata dos custos operacionais na nuvem nas categorias de Computação, Rede e Armazenamento, respectivamente. Além disso, proporcionará
melhor visibilidade e controle sobre os gastos e otimização contínua da infraestrutura. Isso aumentará a eficiência e a produtividade da empresa, liberando
recursos financeiros para outras iniciativas estratégicas. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:
André Nascimento

