# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 25/08/2025

Empresa: Abstergo Industries

Responsável: JANTOVANNE MONTEIRO DE MELO

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por JANTOVANNE MONTEIRO DE MELO. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1: Otimização de Custo em Computação
- Nome da ferramenta: Amazon EC2 Spot Instances

- Foco da ferramenta: Otimização de custos para cargas de trabalho flexíveis e tolerantes a interrupções.

- Descrição de caso de uso: Implementação de instâncias Spot para ambientes de desenvolvimento e testes, bem como para processamento de dados em lotes (batch processing). Essas cargas de trabalho podem ser interrompidas e retomadas sem impactar a operação principal, resultando em economias de até 90% em comparação com as instâncias sob demanda.

### Etapa 2: Redução de Custo com Arquitetura Serverless
- Nome da ferramenta: AWS Lambda

- Foco da ferramenta: Redução de custos com infraestrutura através da arquitetura Serverless.

- Descrição de caso de uso: Migração de scripts e tarefas agendadas (por exemplo, backups, processamento de relatórios) de servidores EC2 para funções AWS Lambda. Com o modelo de cobrança "pay-per-use", a empresa paga apenas pelo tempo de execução do código, eliminando os custos de servidores ociosos e a necessidade de gerenciar a infraestrutura.

### Etapa 3: Gerenciamento Inteligente de Armazenamento
- Nome da ferramenta: Amazon S3 Lifecycle Policies

- Foco da ferramenta: Automação de gerenciamento de armazenamento e otimização de custos de longo prazo.

- Descrição de caso de uso: Configuração de políticas de ciclo de vida para buckets do Amazon S3. Arquivos de log e backups mais antigos que não são acessados com frequência são movidos automaticamente para classes de armazenamento mais baratas (como S3 Glacier Instant Retrieval ou S3 Glacier Deep Archive) após um período definido. Isso reduz os custos de armazenamento sem a necessidade de intervenção manual.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a otimização significativa de custos operacionais (OpEx), maior eficiência na utilização dos recursos de computação, flexibilidade para dimensionar cargas de trabalho conforme a demanda e automação de tarefas de gerenciamento de dados e infraestrutura, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
Documento de Recomendações de Otimização de Custos AWS

Planilha de Estimativa de Economia (AWS Cost Explorer)

Manuais de configuração dos serviços EC2, Lambda e S3

Diagrama de Arquitetura da Solução Implementada

## Assinatura do Responsável pelo Projeto:

JANTOVANNE MONTEIRO DE MELO