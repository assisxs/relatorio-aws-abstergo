# relatorio-aws-abstergo

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 07/01/2026
Empresa: Abstergo Industries 
Responsável: Raíssa Assis

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Raíssa Assis. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especÃ­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3
- Foco da ferramenta: Armazenamento de baixo custo e alta durabilidade
- Descrição de caso de uso: A Abstergo Industries utilizava soluções de armazenamento locais e serviços mais caros para dados pouco acessados. O Amazon S3 permite armazenar arquivos, backups e documentos com custo significativamente menor, pagando apenas pelo que é utilizado.

Etapa 2: 
- Amazon EC2
- Foco da ferramenta: Computação sob demanda
- Descrição de caso de uso: Antes da AWS, a empresa mantinha servidores superdimensionados, gerando desperdício. Com o Amazon EC2, é possível ajustar o tipo e o tamanho das instâncias conforme a real necessidade do negócio.

Etapa 3: 
- Amazon RDS
- Foco da ferramenta: Banco de dados gerenciado
- Descrição de caso de uso: A gestão manual de bancos de dados gera custos elevados com administração, backups e indisponibilidade. O Amazon RDS automatiza tarefas operacionais, reduz falhas e elimina a necessidade de servidores dedicados exclusivamente para banco.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado reduzir custos de forma imediata, otimizar o uso de recursos tecnológicos e melhorar a eficiência operacional aumentando a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Manual Básico de Utilização

## Amazon S3

### Objetivo
Armazenar arquivos, documentos e backups de forma segura, escalável e com baixo custo.

### Como acessar
1. Acessar o **AWS Management Console**
2. Selecionar o serviço **Amazon S3**
3. Escolher o bucket criado para o projeto

### Operações básicas
- **Upload de arquivos**
  - Clicar em *Upload*
  - Selecionar os arquivos desejados
- **Download de arquivos**
  - Selecionar o arquivo
  - Clicar em *Download*
- **Exclusão de arquivos**
  - Selecionar o arquivo
  - Clicar em *Delete*

### Boas práticas
- Utilizar o S3 apenas para arquivos e dados estáticos
- Excluir arquivos que não são mais necessários para evitar custos adicionais

---

## Amazon EC2

### Objetivo
Fornecer capacidade computacional sob demanda, reduzindo custos com servidores físicos.

### Como acessar
1. Acessar o **AWS Management Console**
2. Selecionar o serviço **Amazon EC2**
3. Acessar a opção **Instâncias**

### Operações básicas
- **Iniciar instância**
  - Selecionar a instância
  - Clicar em *Start*
- **Parar instância**
  - Selecionar a instância
  - Clicar em *Stop*
- **Monitorar status**
  - Verificar o estado da instância (*running* ou *stopped*)

### Boas práticas
- Manter instâncias desligadas quando não estiverem em uso
- Utilizar apenas o tipo de instância necessário para a demanda atual

---

## Amazon RDS

### Objetivo
Gerenciar bancos de dados de forma automatizada, reduzindo esforço operacional e custos de manutenção.

### Como acessar
1. Acessar o **AWS Management Console**
2. Selecionar o serviço **Amazon RDS**
3. Selecionar a instância de banco de dados criada

### Operações básicas
- **Acessar o banco de dados**
  - Utilizar o endpoint fornecido pelo RDS
- **Monitorar desempenho**
  - Acompanhar métricas básicas no painel do serviço
- **Backups**
  - Os backups automáticos são gerenciados pelo Amazon RDS

### Boas práticas
- Utilizar o RDS apenas para dados estruturados
- Monitorar o uso para evitar dimensionamento excessivo

---

Assinatura do Responsável pelo Projeto:

Raíssa Assis
