# 3. DOCUMENTO DE ESPECIFICAÇÃO DE REQUISITOS DE SOFTWARE

Nesta parte do trabalho você deve detalhar a documentação dos requisitos do sistema proposto de acordo com as seções a seguir. Ressalta-se que aqui é utilizado como exemplo um sistema de gestão de cursos de aperfeiçoamento.

## 3.1 Objetivos deste documento
Descrever e especificar as necessidades da Coordenação do Curso de Sistemas de Informação da PUC Minas que devem ser atendidas pelo projeto SCCA – Sistema de Cadastro de Cursos de Aperfeiçoamento.

## 3.2 Escopo do produto

### 3.2.1 Nome do produto e seus componentes principais
O produto será denominado SCCA – Sistema de Cadastro de Cursos de Aperfeiçoamento. Ele terá somente um componente (módulo) com os devidos elementos necessários à gestão de cursos.

### 3.2.2 Missão do produto
Gerenciar informações sobre a oferta de cursos de aperfeiçoamento, gerenciar a composição das turmas, alunos, professores e matrículas. 

### 3.2.3 Limites do produto
O SCCA não fornece nenhuma forma de avaliação de alunos, pagamento de parcelas do curso, pagamento a professore e agendamentos. O SCCA não contempla o atendimento a vários cursos de Sistemas de Informação de outras unidades da PUC Minas.

### 3.2.4 Benefícios do produto

| # | Benefício | Valor para o Cliente |
|--------------------|------------------------------------|----------------------------------------|
|1	| Facilidade no cadastro de dados |	Essencial |
|2 | Facilidade na recuperação de informações | Essencial | 
|3 | Segurança no cadastro de matrículas | Essencial | 
|4	| Melhoria na comunicação com os alunos	| Recomendável | 

## 3.3 Descrição geral do produto

### 3.3.1 Requisitos Funcionais

| Código | Requisito Funcional (Funcionalidade) | Descrição |
|--------------------|------------------------------------|----------------------------------------|
| RF1 | Deve existir uma página inicial (_landing page_). | Esta página deve fornecer uma visão geral clara e atrativa dos objetivos da plataforma, destacar seus principais recursos e benefícios e direcionar os visitantes para ações específicas, como cadastro, exploração de demandas ou oferta de ajuda. |
| RF2 | A aplicação deve permitir que as ONGs se cadastrem. |	O processo de cadastro deve incluir o preenchimento de informações essenciais, como nome da ONG, CNPJ, endereço, telefone, e-mail e senha. |
| RF3 | A aplicação deve permitir que as ONGs acessem o sistema. | Fornecer um sistema de autenticação seguro, permitindo que as ONGs acessem suas contas por meio de um processo de login. |
| RF4 | A aplicação deve oferecer um processo de recuperação de senha. | O processo de recuperação de senha deve ser iniciado por meio de um link na tela de login, em que o usuário será solicitado a informar o e-mail cadastrado. Após a submissão, o sistema deve enviar um e-mail contendo um link seguro para redefinição da senha. |
| RF5 | A aplicação deve apresentar uma página de perfil para as ONGs. | Apresenta uma página exclusiva para cada ONG, contendo informações sobre a organização, depoimentos dos voluntários e últimas demandas. |
| RF6 | A aplicação deve permitir que as ONGs gerenciem suas informações de perfil. | As ONGs poderão visualizar, editar e atualizar dados como nome da organização, CNPJ, endereço, telefone, e-mail de contato, descrição da ONG, redes sociais, e outras informações relevantes. |
| RF7 | A aplicação deve possibilitar que as ONGs divulguem solicitações de ajuda técnica. | As ONGs poderão descrever suas necessidades específicas, como suporte em tecnologia, manutenção de sistemas, desenvolvimento de websites, entre outros. Cada solicitação deverá incluir informações detalhadas, como título, descrição e tipo de ajuda necessária. |
| RF8 | A aplicação deve permitir que as ONGs vejam e administrem suas demandas. | As ONGs devem poder acessar uma área dedicada onde todas as suas demandas ativas e anteriores sejam listadas, possibilitando a visualização do  status de cada solicitação, edição, exclusão e acompanhamento de respostas ou ofertas de ajuda recebidas. Poderá também filtrar pelo status (aberta ou finalizada) para facilitar a leitura. |
| RF9 | A aplicação deve permitir que as ONGs marquem as solicitações como concluídas ou encerradas. | Essa funcionalidade deve estar disponível no painel de administração de demandas da ONG, e o  status da solicitação deve ser atualizado na plataforma para que outros usuários saibam que ela já foi finalizada. |
| RF10 | A página da demanda cadastrada pela ONG deve exibir uma lista de todos os voluntários que tiveram a candidatura aceita. | Essa funcionalidade permitirá que a ONG visualize de forma clara os voluntários que foram aprovados e estão envolvidos na demanda. |
| RF11 | Os voluntários devem poder se voluntariar por meio de formulário de contato para trabalhar em projetos específicos das ONGs. | Cada projeto divulgado pela ONG deve ter um botão ou link para voluntariado, que redirecionará o voluntário para um formulário no qual poderá fornecer informações de contato, habilidades relevantes e uma breve mensagem de apresentação, indicando seu interesse e disponibilidade. |
| RF12 | Os voluntários devem receber um e-mail quando uma ONG expressa interesse em seu perfil. | Este e-mail deve informar o voluntário sobre o interesse da ONG e fornecer detalhes relevantes para que ele possa tomar ações apropriadas. |
| RF13 | Na página da demanda cadastrada pela ONG, deve ter um botão solicitando ao voluntário um feedback sobre sua experiência. | A página deve incluir um botão que permita enviar um link por e-mail aos voluntários solicitando que deixem um comentário sobre sua experiência com a demanda. Este recurso ajudará a ONG a obter um retorno valioso dos voluntários. |
| RF14 | A aplicação deve apresentar uma página para os depoimentos dos voluntários. | Esta página deve ser acessada exclusivamente por meio de um link recebido via e-mail e deve conter um formulário para o preenchimento do depoimento. |
| RF15 | Os depoimentos dos voluntários devem ser disponibilizados no perfil da ONG que fez a solicitação. | Esta funcionalidade permitirá que a ONG visualize e compartilhe o feedback dos voluntários sobre suas experiências com a demanda. |
| RF16 | A aplicação deve apresentar uma página contendo as últimas demandas criadas pelas ONGs. | Essa página deve listar as demandas com informações como o título e a descrição resumida. A página deve ser de fácil navegação e permitir que os usuários filtrem as demandas pela localização (presencial ou remota). |
| RF17 | A aplicação deve apresentar a página “Como Começar”. | Essa página deve conter instruções claras sobre os principais processos, como o cadastro de ONGs, publicação de demandas, voluntariado em projetos, e navegação geral da plataforma. |
| RF18 | A aplicação deve conter a página “Perguntas Frequentes”. | Esta página deve proporcionar aos usuários respostas para as dúvidas mais comuns relacionadas ao uso da aplicação e seus serviços. |
| RF19 | A aplicação deve apresentar a página “Sobre o Voluntariado”. | Esta página deve fornecer informações detalhadas sobre o programa de voluntariado, seus objetivos, e como os usuários podem se envolver. |
| RF20 | A aplicação deve apresentar a página “Por Que Ser Voluntário?”. | Esta página deve destacar as razões e benefícios de participar em atividades de voluntariado, incentivando os usuários a contribuirem e apoiarem a causa. |
| RF21 | A aplicação deve apresentar a página “Histórias de Sucesso”. | Esta página deve apresentar relatos e exemplos de casos bem-sucedidos relacionados ao uso da aplicação ou ao impacto positivo das ações apoiadas por ela. |

### 3.3.2 Requisitos Não Funcionais

| Código | Requisito Não Funcional (Restrição)                                                                                                                            |
|--------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| RNF1   | O sistema deve oferecer uma interface com design responsivo que se adapte aos dispositivos móveis e desktops.	                                                 |
| RNF2   | As senhas dos usuários devem ser criptografadas antes de serem armazenadas no banco de dados.	                                                                 |
| RNF3   | O sistema deve fornecer feedback visual claro para ações do usuário, como confirmações de envio e mensagens de erro.                                           |
| RFN4   | O sistema deve ser capaz de ser executado nas versões mais recentes dos principais navegadores do mercado, como: Chrome, Firefox, Edge e Safari.               |
| RNF5   | O sistema deve ter um tempo de resposta inferior a 3 segundos, como processamento de formulários e buscas.                                                     |
| RNF6   | O sistema deve ter um tempo de resposta inferior a 5 segundos para a renderização de páginas e navegação geral, para assegurar uma boa experiência do usuário. |
| RNF7   | O sistema deve ter um design modular que facilite a adição de novos recursos e funcionalidades sem a necessidade de reescrever código existente.               |


### 3.3.3 Usuários 

| Ator | Descrição |
|--------------------|------------------------------------|
| Representante da ONG |	Usuário que representa uma ONG e busca suporte técnico ou colaboração em projetos tecnológicos. É responsável por criar e gerenciar solicitações de suporte, acompanhar o progresso dos projetos e assegurar que as necessidades tecnológicas da ONG sejam atendidas. |
| Voluntário de TI |	Usuário que oferece suas habilidades e conhecimentos em tecnologia para apoiar as ONGs. Pode se inscrever em projetos, fornecer suporte técnico, desenvolver soluções para desafios específicos das ONGs, e compartilhar feedback sobre sua experiência por meio de depoimentos.

## 3.4 Modelagem do Sistema

### 3.4.1 Diagrama de Casos de Uso
Como observado no diagrama de casos de uso da Figura 1, O Representante poderá gerenciar as matrículas e professores no sistema, enquanto o coordenador, além dessas funções, poderá gerenciar os cursos de aperfeiçoamento.

#### Figura 1: Diagrama de Casos de Uso do Sistema.

![dcu](https://github.com/user-attachments/assets/41f6b731-b44e-43aa-911f-423ad6198f47)
 
### 3.4.2 Descrições de Casos de Uso

## Gerenciar Demandas (CSU01)

**Sumário:** O Representante da ONG realiza a gestão (inclusão, remoção, alteração e consulta) dos dados sobre as demandas.

**Ator Primário:** Representante da ONG.

**Ator Secundário:** Não possui.

**Pré-condições:** O Representante deve estar autenticado e validado pelo sistema.

### Fluxo Principal:

1) 	O Representante requisita manutenção de demandas.
   
2) 	O Sistema apresenta as operações que podem ser realizadas: inclusão de uma nova demanda, alteração de uma demanda, a exclusão de uma demanda e a consulta de dados de uma demanda.
   
3) 	O Representante seleciona a operação desejada: Inclusão, Exclusão, Alteração ou Consulta, ou opta por finalizar o caso de uso.
  
4) 	Se o Representante desejar continuar com a gestão de demandas, o caso de uso retorna ao passo 2; caso contrário o caso de uso termina.

### Fluxo Alternativo (3): Inclusão

A) O Representante requisita a inclusão de uma nova demanda.

B) O Sistema apresenta um formulário solicitando o nome, tipo e descrição da demanda.

C) O Representante preenche o formulário com as informações solicitadas.

D) O Sistema valida os dados fornecidos:
  * Se os dados estiverem corretos, o Sistema inclui a nova demanda e notifica o sucesso da operação.
  * Se houver erros, o Sistema solicita correções e repete a validação.
    
O Sistema retorna ao início do fluxo principal.

### Fluxo Alternativo (3): Remoção

A) O Representante seleciona uma demanda existente e requisita a sua remoção.

B) O Sistema verifica se a demanda pode ser removida:
   * Se a demanda puder ser removida, o Sistema a exclui e notifica o sucesso da operação.
   * Se a demanda não puder ser removida, o Sistema reporta o erro ao Representante.
     
O Sistema retorna ao início do fluxo principal.

### Fluxo Alternativo (3): Alteração

A) O Representante seleciona uma demanda existente para alterar e solicita a edição dos seus dados.

B) O Sistema apresenta os dados atuais da demanda para edição.

C) O Representante altera os dados desejados.

D) O Sistema verifica a validade dos novos dados:
   * Se os dados forem válidos, o Sistema atualiza a demanda e notifica o sucesso da operação.
   * Se houver erros, o Sistema reporta o problema e solicita correções.
     
O Sistema retorna ao início do fluxo principal.
 
### Fluxo Alternativo (3): Consulta

A) O Representante requisita a consulta de uma demanda, podendo buscar pelo tipo e status.

B) O Sistema apresenta a lista de demandas que atendem aos critérios de busca.

C) O Representante seleciona uma demanda da lista.

D) O Sistema exibe os detalhes da demanda selecionada.

E) O Sistema retorna ao início do fluxo principal.

**Pós-condições:** Uma demanda foi inserida, removida, alterada ou consultada com sucesso, de acordo com a operação escolhida pelo Representante.

## Gerenciar Trabalhos Voluntários (CSU01)

**Sumário:** O Voluntário de TI realiza a gestão (inclusão, remoção, alteração e consulta) dos dados sobre os trabalhos candidatados.

**Ator Primário:** Voluntário de TI.

**Ator Secundário:** Não possui.

**Pré-condições:** O Representante deve estar autenticado e validado pelo sistema.

#### Fluxo Principal:

1) 	O Voluntário de TI requisita manutenção de trabalhos voluntários.
  
2) 	O Sistema apresenta as operações que podem ser realizadas: inclusão de uma nova candidatura, alteração de uma candidatura, a exclusão de uma candidatura e a consulta de dados de uma candidatura.
  
3) 	O Voluntário seleciona a operação desejada: Inclusão, Exclusão, Alteração ou Consulta, ou opta por finalizar o caso de uso.
   
4) 	Se o Voluntário desejar continuar com a gestão de candidaturas, o caso de uso retorna ao passo 2; caso contrário o caso de uso termina.

### Fluxo Alternativo (3): Inclusão

A) O Voluntário requisita a inclusão de uma nova candidatura.

B) O Sistema apresenta um formulário solicitando o nome, CPF, e-mail, telefone e descrição de suas capacidades para a candidatura.

C) O Voluntário preenche o formulário com as informações solicitadas.

D) O Sistema valida os dados fornecidos:
  * Se os dados estiverem corretos, o Sistema inclui a nova candidatura e notifica o sucesso da operação.
  * Se houver erros, o Sistema solicita correções e repete a validação.
    
O Sistema retorna ao início do fluxo principal.

### Fluxo Alternativo (3): Remoção

A) O Voluntário seleciona uma candidatura existente e requisita a sua remoção.

B) O Sistema verifica se a demanda pode ser removida:
   * Se a demanda puder ser removida, o Sistema a exclui e notifica o sucesso da operação.
   * Se a demanda não puder ser removida, o Sistema reporta o erro ao Representante.
     
O Sistema retorna ao início do fluxo principal.

### Fluxo Alternativo (3): Alteração

A) O Voluntário seleciona uma candidatura existente para alterar e solicita a edição dos seus dados.

B) O Sistema apresenta os dados atuais da candidatura para edição.

C) O Representante altera os dados desejados.

D) O Sistema verifica a validade dos novos dados:
   * Se os dados forem válidos, o Sistema atualiza a demanda e notifica o sucesso da operação.
   * Se houver erros, o Sistema reporta o problema e solicita correções.
     
O Sistema retorna ao início do fluxo principal.
 
### Fluxo Alternativo (3): Consulta

A) O Voluntário requisita a consulta de uma candidatura, podendo buscar pelo tipo e status.

B) O Sistema apresenta a lista de demandas que atendem aos critérios de busca.

C) O Voluntário seleciona uma candidatura da lista.

D) O Sistema exibe os detalhes da demanda selecionada.

E) O Sistema retorna ao início do fluxo principal.

Pós-condições:  Uma candidatura foi inserida, removida, alterada ou consultada com sucesso, de acordo com a operação escolhida pelo Voluntário de TI.

### 3.4.3 Diagrama de Classes 

A Figura 2 mostra o diagrama de classes do sistema. A Matrícula deve conter a identificação do funcionário responsável pelo registro, bem com os dados do aluno e turmas. Para uma disciplina podemos ter diversas turmas, mas apenas uma demanda responsável por ela.

#### Figura 2: Diagrama de Classes do Sistema.
 
![dcu](https://github.com/user-attachments/assets/97ab1aa8-eb03-4b58-9ad5-1697d414a451)

### 3.4.4 Descrições das Classes 

| # | Nome | Descrição |
|--------------------|------------------------------------|----------------------------------------|
| 1	|	Aluno |	Cadastro de informações relativas aos alunos. |
| 2	| Curso |	Cadastro geral de cursos de aperfeiçoamento. |
| 3 |	Matrícula |	Cadastro de Matrículas de alunos nos cursos. |
| 4 |	Turma |	Cadastro de turmas.
| 5	|	Professor |	Cadastro geral de professores que ministram as disciplinas. |
| ... |	... |	... |
