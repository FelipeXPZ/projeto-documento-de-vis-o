# 1. Introdução

## 1.1 Propósito
Este documento tem como objetivo definir e organizar as características sobre o desenvolvimento da solução Escola X.

## 1.2 Escopo
Este projeto tem como finalidade suprir a necessidade de controle e gerenciamento da diretoria referente a vida acadêmica dos alunos da escola Centro de Ensino Médio 01 do Gama.

A direção busca uma solução em software para substituir um sistema previamente implementado, sendo que, deve possuir como característica fundamental a confiabilidade.

O software, a ser implementado, deve monitorar a presença e atividades escolares dos alunos mantendo os responsáveis informados.

## 1.3 Visão geral
Este documento descreve os detalhes sobre as características do software Escola X a ser desenvolvido, especificando os problemas que estimularam a criação dessa solução em software. O documento é dividido da seguinte maneira: inicialmente é especificado qual problema motivou o desenvolvimento da solução, em seguida as partes interessadas são descritas, e por fim todos os recursos, restrições e requisitos do produto são apresentados.

# 2. Posição
## 2.1 Oportunidade de Negócios
A forma como se dá o controle e gestão da vida acadêmica dos docentes, principalmente nas escolas públicas, não se adequa às necessidades das coordenações. Isso ocorre devido a um controle rudimentar e, em alguns casos, ineficiente em manter os dados relacionados e informar os responsáveis.

Nosso projeto visa solucionar este problema por meio da informatização do sistema de identificação dos alunos e notificação dos pais.

## 2.2 Instrução do problema
| O problema seria | a dificuldade no controle das informações quanto à vida acadêmica dos alunos|
|--|--|
| **que afeta** | a diretoria, professores, alunos e responsáveis |
| **cujo impacto é** | evasão escolar, falta de controle dos responsáveis e da direção |
| **e uma boa solução seria** | um controle informatizado da vida acadêmica dos alunos com maior integração dos responsáveis.|

## 2.3 Instrução de posição do produto
| Para | o corpo docente e responsáveis |
| --- | --- | 
| **que** | necessitam de uma ferramenta para o controle da vida acadêmica dos alunos |
| **o(a)** | Escola X é uma aplicação web |
| **que** | faz o controle e informatiza a vida acadêmica dos alunos mantendo os responsáveis cientes e aumentando o controle da direção |
| **diferente do** | método tradicional feito manualmente e do aplicativo Acadêmico Total Pais e Filhos |
| **nosso produto** | é um alternativa gratuita e funcional para o problema existente. |

# 3 Descrições da parte interessada e do usuário
## 3.1 Resumo da parte interessada
| Nome| Descrição | Responsabilidade |
| --- | --- | --- |
| **Equipe de desenvolvimento** | Estudantes da Universidade de Brasília da disciplina de MDS. | Desenvolver e Implementar o software. |
| **Equipe de Gestão de Projeto** | Estudantes da Universidade de Brasília da disciplina de GPP. | Gerir o desenvolvimento do produto identificando o problema e apontando caminhos e soluções. |
| **Clientes** | Centro de Ensino Médio 01 do Gama. | Disponibilizar informações sobre os alunos .|

## 3.2 Resumo do usuário
| Nome | Descrição |
| --- | --- |
| **Aluno** | Utilizará o software para validação de entrada e saída. |
| **Responsáveis** | Serão notificados sobre a frequência dos alunos e comunicados em geral da direção. |
| **Diretoria** | Poderá comunicar os responsáveis sobre alterações na entrada/saída, advertências, suspensões e boletim dos alunos. |

## 3.3 Ambiente de usuário
O software será usado em todos os navegadores, tendo seu uso otimizado para o Google chrome versão 56.0.2924.87 devido a sua performance e por ter a maior base instalada dentre os outros navegadores WEB.

## 3.4 Perfis dos usuários
### 3.4.1 Corpo docente
| **Representantes**| Macário dos Santos Neto |
| --- | --- |
| **Descrição**| Representante do CEM 01 que busca uma forma eficiente de gerir a vida acadêmica dos alunos da instituição e manter os responsáveis informados. |
| **Tipo**| Diretor do CEM 01. |
| **Responsabilidades** | Fornecer as informações dos alunos matriculados na instituição. |
| **Critérios de sucesso** | Diminuir a evasão escolar, gerir e informar os responsáveis sobre a vida acadêmica dos alunos. |
| **Envolvimento**| Alto |
|**Comentário/Problemas** | - |

### 3.4.2 Alunos
| Representantes | alunos |
| --- | --- |
| **Descrição**| Estudante matriculado regularmente no CEM 01 do Gama. |
| **Tipo**| Alunos do CEM 01 do Gama. |
| **Responsabilidades**| Utilizar a carteirinha da escola para validar sua entrada/saída. |
| **Critérios de sucesso** | Manter o sistema de frequência funcionando sem maiores dificuldades. |
| **Envolvimento** | Baixo |
| **Comentário/Problemas** | Por não ser uma obrigatoriedade, alguns alunos podem não usar o software e diminuir a adesão do sistema. |

## 3.5 Principais necessidades da parte interessada ou do Usuário
|Necessidade|Prioridade|Interesses|Solução atual|Solução proposta|
|---|---|---|---|---|
|Gerir a vida acadêmica dos alunos.|Alta|Manter o controle diário de entrada/saída dos alunos e controlar as atividades acadêmicas.|Método manual e ineficiente, utilizando também o aplicativo Acadêmicos Total Pais e Filhos.|Exercer uma gerência mais eficiente da vida acadêmica dos alunos com o auxílio de um software com maior confiabilidade que o sistema anterior.|
|Notificar os responsáveis.|Alta|Informar os responsáveis sobre entrada/saída e vida acadêmica dos alunos|Os responsáveis recebem um SMS sobre a entrada dos alunos, mas não possuem uma forma digital de acessar o histórico do alunos.|Os responsáveis receberão um SMS informando a entrada e saída do aluno, além de uma plataforma web para acessar o histórico escolar do estudante.|

# 4 Visão geral do produto
## 4.1 Perspectiva do Produto
O sistema irá oferecer uma maneira informatizada e eficiente de controlar a entrada e saída dos alunos utilizando um leitor de códigos de barra, existente na instituição. O leitor vai fazer a identificação de cada aluno através da carteirinha, dessa forma os respectivos responsáveis receberão um SMS informando o horário de entrada ou saída do aluno. Cada responsável terá acesso ao histórico escolar do aluno, que fornecerá informações como: número de faltas, boletim escolar e advertências ou suspensões.

## 4.2 Resumo das capacidades
|Benefício para o Cliente|Recursos de suporte|
|---|---|
|Possuir um controle da entrada/saída dos alunos.|A entrada/saída serão verificadas pelo Leitor Físico Solaris MS 7820(MK 7820) após a apresentação da carteirinha pelo aluno.|
|Manter os responsáveis sempre informados sobre os horários de entrada e saída dos estudantes na escola.|Envio de SMS para o(s) responsável(is) após o aluno utilizar a carteirinha na leitora de código de barras durante a entrada e saída na escola.|
|Obter informações referentes às atividades acadêmicas dos alunos, como: número de faltas, advertências, suspensões e boletim.|Uma aplicação WEB onde alunos e responsáveis podem se registrar e obter todo um histórico acadêmico dos estudantes.|

# 5. Recursos do produto
## 5.1 Manter Aluno, Responsável, Professor e Diretor
O sistema vai manter o cadastro dos alunos, responsáveis, professores e direção.
## 5.2 Controlar Entrada/Saída dos alunos
Controlar entrada e saída dos alunos, utilizando-se de cartão identificador e leitor de código de barras, e manter essa informação no sistema.
## 5.3 Notificar o responsável
Notifica o responsável cadastrado sobre a entrada e saída dos alunos, advertências e suspensões, reuniões e outras notificações em geral.
## 5.4 Armazenar notas
O sistema armazenará a nota de cada aluno nas determinadas disciplinas.
## 5.5 Consultar aluno
Os responsáveis terão acesso ao histórico escolar dos alunos, que fornecerá as seguintes informações: número de faltas, boletim escolar, advertências e suspensões.
