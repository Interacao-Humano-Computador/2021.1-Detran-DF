# G.O.M.S

## O Método

<p style="text-indent: 20px; text-align: justify"> 
O método propõe um conjunto de modelos chamado GOMS (<b>Goals, Operators, Methods e Selection rules</b>) e é usado para descrever/analisar uma tarefa e o conhecimento do usuário sobre como realizá-la sem cometer erros.
</p>

## A escolha do método

<p style="text-indent: 20px; text-align: justify"> 
O método GOMS foi escolhido por conta do contexto do nosso projeto, considerando que este é realizado sobre uma plataforma já desenvolvida e (considera-se que seja) conhecida pelo usuário. Desta forma, o que se busca aqui é uma análise básica das tarefas, afim de uma representação formal que seja usada para prever o desempenho e melhorar a eficácia de procedimentos frequentemente realizados. 
</p>

## Objetivos escolhidos para análise

### Consultar parcelamento de dívida ativa
  - **Goal 0**: Acessar no menu de [Detran-DF](detran.df.gov.br) a opção "Dívida Ativa"
    - OP 0.1 → Deslocar o mouse até o menu ao centro da página inicial carregada
    - OP 0.2 → Deslizar o mouse em cima de "Serviços"
    - OP 0.3 → Deslizar o mouse em cima de "Informações"
    - OP 0.4 → Deslocar o mouse até "Dívida ativa"
    - OP 0.5 → Clicar com o botão esquerdo do mouse 
  - **Goal 1**: Acessar consulta do processo
    - OP 1.1 → Deslocar o mouse até o link "Para consultar processo clique aqui" abaixo do título "Dívida ativa"
    - OP 1.2 → Clicar com o botão esquerdo do mouse 
    - OP 1.3 → Deslocar o mouse até as caixas de preenchimento dispostas na tela "Consulta parcelamento de dívida ativa"
    - OP 1.4 → Deslocar o mouse até o botão "Consultar" ao centro da tela
    - OP 1.5 → Clicar com o botão esquerdo do mouse

--- 
  
### Agendar horário para coleta de biometria
  - **Goal 0**: Acessar no menu de [Portal Detran-DF](https://portal.detran.df.gov.br) a opção "Agendamento de Biometria"
    - OP 0.1 → Deslocar o mouse até o botão de "Agendamento" no menu header da página
    - OP 0.2 → Clicar com o botão esquerdo do mouse 
    - OP 0.3 → Deslocar o mouse até o card "Agendamento de Biometria"
    - OP 0.4 → Clicar com o botão esquerdo do mouse
  - **Goal 1**: Acessar página de agendamento biométrico
    - OP 1.1 → Deslocar o mouse até próximo do fim da paǵina
    - OP 1.2 → Deslocar o mouse até o link "Agendamento Biométrico" 
    - OP 1.3 → Clicar com o botão esquerdo do mouse
  - **Goal 2**: Acessar conta para atendimento a serviços
    - Method 2.A: Acessar já possuindo cadastro
      - OP 2.A.1 → Deslocar mouse até o campo identificado para CPF 
      - OP 2.A.2 → Clicar com o botão esquerdo do mouse
      - OP 2.A.3 → Digitar o número do CPF
      - OP 2.A.4 → Deslocar mouse até o campo identificado para senha 
      - OP 2.A.5 → Clicar com o botão esquerdo do mouse
      - OP 2.A.6 → Digitar a senha
      - OP 2.A.7 → Deslocar o mouse até o botão "Entrar"
      - OP 2.A.8 → Clicar com o botão esquerdo do mouse
    - Method 2.B: Criar conta para acessar
      - OP 2.B.1 → Deslocar o mouse até o canto inferior no link "Registre-se"
      - OP 2.B.2 → Clicar com o botão esquerdo do mouse
      - OP 2.B.3 → Deslocar o mouse até o campo identificado para preenchcimento de CPF
      - OP 2.B.4 → Clicar com o botão esquerdo do mouse
      - OP 2.B.5 → Preencher CPF
      - OP 2.B.6 → Deslocar o mouse até o botão "Avançar"
      - OP 2.B.7 → Clicar com o botão esquerdo do mouse
      - OP 2.B.8 → Deslocar o mouse até os campos a serem preenchidos no formulário de criação de conta
      - OP 2.B.9 → Clicar nos campos com o botão esquerdo do mouse
      - OP 2.B.10 → Preencher os campos com as informações pedidas
      - OP 2.B.11 → Deslocar o mouse até o botar "Cadastrar"
      - OP 2.B.12 → Clicar com o botão esquerdo do mouse
  - **Goal 3**: Realizar agendamento
    - OP 3.1 → Deslocar mouse até botão de "Ok" na caixa de pergunta sobre criação de novo agendamento 
    - OP 3.2 → Clicar com o botão esquerdo do mouse
    - OP 3.3 → Deslocar o mouse até os campos de preenchimento (Posto de Atendimento/ Data do Agendamento/ Horário do Agendamento)
    - OP 3.4 → Escolher a opção de preferência em cada campo de preenchimento
    - OP 3.5 → Clicar com o botão esquerdo do mouse
    - OP 3.6 → Deslocar mouse até o botão "Cadastrar"
    - OP 3.7 → Clicar com o botão esquerdo do mouse

---
  
### Consultar débitos relacionados a um veículo
  - **Goal 0**: Acessar no menu de [Portal Detran-DF](https://portal.detran.df.gov.br) a opção "Consulta veículo - Débitos"
    - OP 0.1 → Deslocar o mouse até o botão de "Veículos" no menu header da página
    - OP 0.2 → Clicar com o botão esquerdo do mouse 
    - OP 0.3 → Deslocar o mouse até o card "Consulta veículo - Débitos"
    - OP 0.4 → Clicar com o botão esquerdo do mouse
  - **Goal 1**: Acessar página de consulta de débitos por veículo
    - OP 1.1 → Deslocar o mouse até os campos de preenchimento (Placa/Renavam)
    - OP 1.2 → Clicar com o botão esquerdo do mouse nos campos de preenchimento
    - OP 1.3 → Preencher os campos com as informações pedidas
    - OP 1.4 → Deslocar o mouse até o botão "Consultar"
    - OP 1.5 → Clicar com o botão esquerdo do mouse

---

## Referências bibliográficas
> Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021) Interação Humano-Computador e Experiência do usuário. Autopublicação.

## Versionamento
| Versão | Data | Modificação| Autor |
|--|--|--|--|
| 1.0 | 25/08/2021 | Criação do documento | Sara Campos |
| 1.1 | 26/08/2021 | Adição do modelo GOMS | Sara Campos |