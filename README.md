# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 24/12/2025
Empresa: Abstergo Industries 
Responsável: Leandro

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo, realizado por Leandro. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 (Simple Storage Service)
- Armazenamento de dados com baixo custo e alta durabilidade
- Caso de uso: O Amazon S3 foi utilizado para armazenar históricos de vendas, notas fiscais, dados de estoque e logs de sistemas das farmácias. Ao substituir servidores locais e soluções on‑premises por um armazenamento em nuvem escalável, a empresa reduz custos com manutenção de hardware, energia elétrica e backups físicos, pagando apenas pelo volume efetivamente utilizado.

Etapa 2: 
- Amazon EC2 (Elastic Compute Cloud)
- Processamento sob demanda e escalável
- Caso de uso: O Amazon EC2 foi aplicado para executar rotinas de análise de dados e modelos em Python utilizados para prever demanda de medicamentos e otimizar o controle de estoque. A utilização de instâncias sob demanda (ou spot, quando aplicável) permite reduzir custos ao evitar servidores ligados continuamente, pagando apenas pelo tempo de processamento necessário.

Etapa 3: 
- Amazon DynamoDB
- Banco de dados NoSQL escalável e de baixo custo operacional
- Caso de uso: O Amazon DynamoDB foi utilizado para armazenar dados transacionais das farmácias, como movimentações de estoque, registros de vendas em tempo real e cadastros de produtos. Por ser um banco de dados totalmente gerenciado e serverless, o DynamoDB elimina a necessidade de administração de servidores e permite o pagamento apenas pelo volume de leituras e escritas realizadas. Isso reduz custos operacionais e melhora a performance em períodos de alta demanda, como promoções ou sazonalidades.



## Conclusão
A implementação de ferramentas na empresa Abstergo tem como esperado redução significativa de custos operacionais, maior controle financeiro e melhor aproveitamento dos recursos computacionais, o que aumentará a eficicência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

 - [Amazon DynamoDB](https://aws.amazon.com/pt/dynamodb/)
 - [Amazon DynamoDB: O quê, por que e quando usar o design de tabela única com DynamoDB](https://dev.to/oieduardorabelo/amazon-dynamodb-o-que-por-que-e-quando-usar-o-design-de-tabela-unica-com-dynamodb-ao9)
 - [O que é o armazenamento em nuvem?](https://aws.amazon.com/pt/what-is/cloud-storage/)
 - [O que é o Amazon EC2?](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/concepts.html)
 - [O que é o Amazon S3?](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)

Assinatura do Responsável pelo Projeto:

Leandro
