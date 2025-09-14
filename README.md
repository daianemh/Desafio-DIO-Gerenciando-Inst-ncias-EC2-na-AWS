Desafio DIO: Gerenciando Instâncias EC2 na AWS

Este projeto foi desenvolvido como parte do desafio "Entendendo Desafio" da DIO, com o objetivo de consolidar conhecimentos práticos em gerenciamento de instâncias Amazon EC2 e documentação técnica usando o GitHub.

Objetivos

    Aplicar os conceitos de AWS EC2 em um ambiente prático.

    Documentar o processo de criação e gerenciamento de uma instância virtual.

    Utilizar o GitHub para criar um portfólio de documentação técnica.

Ferramentas Utilizadas

    Amazon Web Services (AWS): Para a criação e configuração da instância EC2.

    GitHub: Para hospedar o repositório e a documentação do projeto.

    Markdown: Para formatar o arquivo README.md.

Processo e Passo a Passo

1. Lançando uma Instância EC2

Para iniciar, naveguei até o serviço EC2 no console da AWS e cliquei em "Executar instância".

<p align="center">
<img src="images/13.jpg" alt="Painel do EC2 com a opção de executar instância.">
</p>

2. Escolha da Imagem e Tipo de Instância

Escolhi a Amazon Linux 2023 AMI, uma imagem fornecida e otimizada pela AWS. Para me manter dentro do plano de uso gratuito, selecionei o tipo de instância t2.micro.

<p align="center">
<img src="images/14.jpg" alt="Tela de escolha da AMI.">
</p>

<p align="center">
<img src="images/15.jpg" alt="Tela de escolha do tipo de instância t2.micro.">
</p>

3. Configuração do Par de Chaves e Rede

Criei um novo par de chaves para autenticação via SSH, chamado chave-ec2-dio. Em seguida, configurei o grupo de segurança (Security Group) para permitir o tráfego SSH na porta 22, utilizando "Meu IP" como origem para maior segurança.

<p align="center">
<img src="images/16.jpg" alt="Configuração do Security Group para acesso SSH.">
</p>

4. Lançamento e Status da Instância

Após revisar todas as configurações, lancei a instância. No painel de instâncias, pude acompanhar o status, que mudou de "Pendente" para "Executando".

<p align="center">
<img src="images/17.jpg" alt="Instância com status pendente.">
</p>

<p align="center">
<img src="images/18.jpg" alt="Instância com status executando e detalhes do IP público.">
</p>

5. Conectando via SSH

Uma vez que a instância estava em execução, usei o terminal para me conectar via SSH, utilizando o arquivo de chave que baixei e o endereço IP público da instância.

Conclusão e Próximos Passos

Este desafio foi fundamental para solidificar os conceitos de computação em nuvem com a AWS. O processo de documentação no GitHub, em paralelo à execução dos passos técnicos, reforçou a importância de manter registros claros para referência futura.

Nota: As imagens deste README.md estão salvas na pasta images deste repositório.
