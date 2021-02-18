# projeto_infra_codigo
Projeto Infraestrutura como código Terraform, Ansible e AWS.
## Objetivo:
1º Desafio - Crie um ambiente na AWS ( use o free-tier ) onde rode uma aplicação Magento/Wordpress (
qualquer versão de sua escolha ou pode escolher qualquer aplicação que tenha
familiaridade) - Requisitos :

● Proxy reverso utilizando Nginx para apontamento na aplicação

● Utilização de certificado SSL

2º Desafio - Montar uma esteira de CI/CD para entrega de atualização da versão da sua aplicação (
exemplo versão 1 para 2 , release 1 para 2 , etc ).
Dica: Pode usar docker para subir sua aplicação

3º Desafio -  Montar documentação no Github ou no Bitbucket para apresentação do desafio.

### Apresentação desafio 01
1 - Deploy do servidor de aplicação WORDPRESS na estrutura AWS utilizando automação via TERRAFORM.

Recursos utilizados:

Servidor linux CentOS (VPN)

Acesso a conta AWS

-- Overview dos script utilizando virtual code.

Execução:

● Cd /desafio-01/terraform-aws-wordpress/

● terraform init

●terraform plan

● terraform apply -auto-approve

2 - Apresentação do Servidor Wordpress

-- Apagar estrutura

● terraform destroy -auto-approve


