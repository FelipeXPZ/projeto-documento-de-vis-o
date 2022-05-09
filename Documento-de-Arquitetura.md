# 1. Introdução
## 1.1 Finalidade
Este documento possui como finalidade a elucidação das questões relacionadas à implementação arquitetural do projeto Escola-X, desenvolvido nas disciplinas de Métodos de Desenvolvimento de Software e Gestão de Portfólios e Projetos de Software, que possui como cliente principal a diretoria da escola CEM 01 do Gama.
## 1.2 Escopo
Este artefato documenta assuntos relacionados a visões de casos de uso e de lógica do projeto.

# 2. Visão dos Casos de Uso
![](https://raw.githubusercontent.com/wiki/fga-gpp-mds/2017.1-Escola-X/images/Casos_de_usov8.jpg)

## 2.1 Atores de Casos de Uso
|Ator|Descrição|
|---|---|
|Adm(Diretor)|O adm irá manter os dados do corpo docente, dos alunos e poderá consultar os dados dos alunos|
|Aluno|O aluno irá registrar sua entrada e saída e poderá consultar seus dados|
|Responsável|O responsável pode consultar os dados do aluno e será notificado da sua entrada e saída|
|Professor|O professor pode consultar dados dos alunos e gerar notificação|
|Secretário|O secretário pode registrar nota e consultar dados dos aluno|

## 2.2 Descrições de Casos de Uso
|Caso de Uso|Descrição|
|---|---|
|UC01 - Manter alunos|Criar, alterar ou deletar um aluno.|
|UC02 - Registrar advertência|Registrar uma nova advertência para um aluno.|
|UC03 - Registrar suspensões|Registrar uma nova suspensão para um aluno.|
|UC04 - Registrar notificação|Registrar notificação para aluno.|
|UC05 - Manter Responsáveis|Criar, alterar ou deletar um responsável de um aluno|
|UC06 - Consultar aluno|Fazer a busca pelo o histórico de um aluno.|
|UC07 - Visualizar número de faltas|Acessar o número de faltas de um determinado aluno.|
|UC08 - Visualizar Boletim|Acessar o boletim de um determinado aluno.|
|UC09 - Visualizar advertências/suspensões|Acessar o número de advertências/suspensões de um determinado aluno.|
|UC10 - Dar nota|Adicionar notas dos alunos.|
|UC11 - Registrar entrada/saída|Registrar a hora de entrada ou saída do aluno.|
|UC12 - Notificar os Responsáveis|Mandar SMS para os responsáveis após entrada/saída do aluno.|
|UC13 - Manter corpo docente|Criar, alterar ou deletar um membro do corpo docente.|
|UC14 - Fazer login|Acessar funcionalidades do sistema.|