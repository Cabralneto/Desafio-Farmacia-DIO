# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 31/03/2026
Empresa: Abstergo Industries
Responsável: Neto Silva

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Neto Silva. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

---

### Etapa 1: Amazon S3 (Simple Storage Service)

- **Foco:** Armazenamento de baixo custo para documentos e arquivos da farmácia
- **Caso de uso:** A Abstergo Industries gerava altos custos com servidores físicos para armazenar notas fiscais, receitas digitalizadas, laudos e documentos regulatórios. Com a migração para o Amazon S3, os arquivos passaram a ser armazenados em nuvem com cobrança apenas pelo volume utilizado, eliminando gastos com hardware, manutenção e energia elétrica. A funcionalidade de classes de armazenamento (S3 Intelligent-Tiering) permite mover arquivos acessados com menos frequência para camadas mais baratas automaticamente, reduzindo ainda mais os custos operacionais.

---

### Etapa 2: Amazon EC2 (Elastic Compute Cloud) com Auto Scaling

- **Foco:** Infraestrutura de servidores elástica e sob demanda
- **Caso de uso:** O sistema de gestão de estoque e vendas da farmácia rodava em servidores físicos dimensionados para o pico de demanda, gerando ociosidade e custo elevado nos períodos de baixo movimento. Com a adoção do Amazon EC2 combinado com Auto Scaling, a capacidade computacional passa a escalar automaticamente conforme a demanda real — crescendo nos horários de pico e reduzindo nos períodos ociosos. O modelo de pagamento por uso (pay-as-you-go) elimina o desperdício com capacidade subutilizada, gerando economia imediata na conta de infraestrutura.

---

### Etapa 3: Amazon RDS (Relational Database Service)

- **Foco:** Banco de dados gerenciado para redução de custos operacionais de TI
- **Caso de uso:** A Abstergo Industries mantinha um banco de dados relacional local para controle de estoque, cadastro de clientes e histórico de compras, exigindo um profissional dedicado para administração, backups manuais e atualizações. Com a migração para o Amazon RDS, toda a gestão do banco de dados (backups automáticos, atualizações de segurança, failover e monitoramento) passa a ser responsabilidade da AWS. Isso elimina custos com licenciamento de software de banco de dados e reduz a necessidade de mão de obra especializada para tarefas operacionais repetitivas.

---

## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado **redução significativa de custos operacionais de TI**, eliminação de gastos com infraestrutura física, maior disponibilidade dos sistemas e escalabilidade conforme a demanda do negócio. O conjunto dos três serviços — Amazon S3, Amazon EC2 com Auto Scaling e Amazon RDS — forma uma base sólida de nuvem que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias AWS que possam melhorar ainda mais os processos da empresa, como o uso de AWS Lambda para automação de processos e Amazon CloudWatch para monitoramento centralizado.

## Anexos

- [relatorio.md](./relatorio.md) — Relatório de implementação de serviços AWS
- [README.md](./README.md) — Descrição do projeto no GitHub

---

Assinatura do Responsável pelo Projeto:

**Neto Silva**
