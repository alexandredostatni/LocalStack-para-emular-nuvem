Simulação da Rotina de um Analista de Infraestrutura Cloud Júnior.

Este repositório contém uma simulação prática e completa da rotina diária de um analista de infraestrutura cloud júnior. O projeto utiliza o LocalStack para emular serviços de nuvem (baseados em AWS) localmente, eliminando a necessidade de contas em provedores de nuvem reais e evitando qualquer custo associado.

Objetivos:

• Compreender e praticar a rotina diária de um analista júnior: monitoramento, provisionamento de recursos, resolução de problemas e colaboração.

• Exercitar habilidades em ferramentas de IaC (Terraform) em um ambiente emulado.

• Simular cenários reais, como escalabilidade, segurança e otimização, sem depender de nuvem real.

• Desenvolver raciocínio em análise de logs, relatórios e versionamento com Git.

Funcionalidades Principais:

• Emulação Local: Todo o ambiente de "nuvem" roda via LocalStack em containers Docker.

• Rotina Estruturada: Dividida em fases que representam horários do dia (ex.: check-in matinal, deploy, troubleshooting).

• Scripts e Exemplos: Inclui códigos Python para automação, arquivos Terraform para IaC e exemplos de relatórios.

• Zero Custo: Sem necessidade de internet após instalação inicial; tudo executado localmente.

Requisitos:

• Sistema Operacional: Linux (Ubuntu WSL)

• Docker: LocalStack usa Docker para emular serviços.

• Terraform: (IaC).

• AWS CLI: Usado para interagir com o LocalStack.

• Python: Com bibliotecas boto3.

• Git: Para versionamento do código.

• Editor de Código: VSCode.
