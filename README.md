# shellscript-challenge
[![GitHub last commit](https://img.shields.io/github/last-commit/google/skia.svg)](https://github.com/helcorin/shellscript-challenge/commits/master) [![Fiap](https://img.shields.io/badge/Fiap-2018-ff0080.svg)](https://www.fiap.com.br/) [![Linkedin](https://img.shields.io/badge/Linkedin-hpinfo-00BFFF.svg)](https://www.linkedin.com/in/hpinfo/)

NAC 20 para a Disciplina Soluções em Redes para Sistemas Linux da turma 2TRCR

![shell](images/shell-1847458_640.jpg)

**Objetivo:** Testar a aplicação dos primeiros processos de automação de tarefas por enquanto usando apenas shell script; 

## Formato: 

Construir um script em shell com o seguinte objetivo: Execução de backup de uma solução de webserver (Apache/HTTPD): 

Logs (Do diretório default de Logs com base na FHS);
Configurações: Diretório de configuração da solução dentro do /etc;
DocumentRoot: Diretório responsável pelo conteúdo do servidor, código JavaScript,  HTML e CSS; 

## Pré-requisitos: 

- Considere que o sistema operacional poderá ser da Família Red Hat ou Centos, seu script deverá tratar ambas as possibilidades;
- O Backup gerado pelo script deve utilizar empacotamento com tar, zip ou rar e preferencialmente compressão de dados; 
- O script deverá gerar um backup com data, essa informação pode ser gerada no arquivo criado, diretório, etc. 
- O script deve ser persistido em GIT utilizando versionamento de código, caso o repositório seja privado autorizar o acesso para o usuário: [helcorin](https://github.com/helcorin)
- O script pode ser interativo, mas  DEVE contemplar a possibilidade de execução automática (com  passagem  de parâmetros, por exemplo) o que permitirá o seu agendamento em Cron ou SystemD Timer; 
- Como se trata de um script automatizado é necessário prover algum tipo de LOG para auditoria de execução; 
A execução deve ser intuitiva ou possuir uma boa documentação, utilizar o README file do GIT com esta finalidade; 


## Extras: 

1. Não é necessário que o script execute a restauração dos arquivos automaticamente mas este diferencial valerá 1 ponto extra; 

2. Na documentação criar instruções sobre como agendar a execução do script usando crontab ou systemD (fica a escolha do analista qual das soluções utilizar), este item valerá 1 ponto extra; 

## Entrega: 

Publicar a **versão ZIP do código extraída do github** na sessão de trabalhos com o **Link para o repositório GIT como comentário**; 

---

**Free Software, Hell Yeah!**
