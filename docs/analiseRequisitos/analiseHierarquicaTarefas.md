# Análise Hierarquica de Tarefas

## 1. Introdução

<p style="text-indent: 20px; text-align: justify"> 
Uma análise de tarefas é utilizada para se ter um entendimento sobre qual é o trabalho dos usuários, como eles o realizam e por quê. Nesse tipo de análise, o trabalho é definido em termos dos objetivos que os usuários querem ou precisam atingir (Barbosa S.; Silva, B. 2021).
</p>

## 2. O Método

<p style="text-indent: 20px; text-align: justify"> 
A Análise Hierárquica de Tarefas (HTA – Hierarchical Task Analysis) foi criada para entender habilidades e competências exibidas em tarefas não repetitivas e complexas, e ajudar na identificação de problemas de desempenho. Relaciona o motivo, como e consequências das ações dos usuários. Baseada na psicologia funcional. A HTA examina os objetivos de alto nível decompondo-os em subobjetivos, com a intenção de encontrar subobjetivos que limitem o alcance de objetivos maiores. 
</p>

<p style="text-indent: 20px; text-align: justify"> 
Elementos de um diagrama HTA:
</p>
- Objetivo;
- Operação;
- Relações;
- Plano.

## 3. Resultados

### HTA01: Agendar Serviço

#### Diagrama HTA
<img src="../../assets/analiseRequisitos/HTA/hta01.png" width="700px;" alt=""/>

#### Tabela HTA
| Objetivo/Operações | Problemas e Recomendações |
| -- | -- |
| 0. Agendar Serviço <br/> <center>1+2+3>4</center> | input: formulário com dados do cidadão, dados do agendamento e data e hora.<br/> plano: informar os dados e agendar serviço.|
| 1. Informar dados do Cidadão | ação: informar CPF, E-mail, Nome e Telefone.|
| 2. Informar Tipo de Serviço | ação: selecionar Tipo de Serviço <br/> problema: serviços indisponíveis|
| 2.1 Selecionar Serviço(s)| ação: selecionar os serviços desejados|
| 3. Informar data e hora | ação: informar dia do atendimento e horário do atendimento. <br/> problema: somente alguns dias e horários disponíveis.|
| 4. Agendar | ação: apertar botão de agendar.|

### HTA02: Consultar Débitos Veículo

#### Diagrama HTA
<img src="../../assets/analiseRequisitos/HTA/hta02.png" width="600px;" alt=""/>

#### Tabela HTA
| Objetivo/Operações | Problemas e Recomendações |
| -- | -- |
| 0. Consultar Débitos Veículo <br/> <center>1+2>3</center> | input: formulário com placa e renavam do veículo. <br/> plano: Consultar todos os débitos do veículo. |
| 1. Informar placa e renavam | ação: Informar placa e renavam. |
| 2. reCAPTCHA | ação: clicar em "Não sou um robô" |
| 3. Consultar| ação: clicar em Consultar |
| 3.1 Emitir boleto de débito | ação: clicar no botão Emitir do débito correspondente|

### HTA03: Solicitar CHN Definitiva

#### Diagrama HTA
<img src="../../assets/analiseRequisitos/HTA/hta03.png" width="500px;" alt=""/>

#### Tabela HTA
| Objetivo/Operações | Problemas e Recomendações |
| -- | -- |
| 0. Solicitar CNH Definitiva <br/> <center>1>2</center> | input: formulário com código, registro, nome e data de nascimento. <br/> plano: obter borderô de taxa de troca de habilitação. |
| 1. Preencher formulário | ação: informar código da imagem, número de registro, nome e data de nascimento. <br/> problema: é preciso recarregar a página para o formulário ficar visível. <br/> recomendação1: incorporar formulário ao HTML da página. <br/> recomendação2: seguir guia de estilo do site/sistema.|
| 2. Enviar | ação: clicar no botão enviar |
| 2.1 Baixar borderô | ação: baixar borderô |

## Referências bibliográficas
> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação.

## Versionamento
| Versão | Data | Modificação| Autor |
|--|--|--|--|
| 1.0 | 23/08/2021 | Criação do documento | Carlos e Matheus |
| 1.1 | 23/08/2021 | Adição dos resultados | Carlos e Matheus |