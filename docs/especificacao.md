# 3. DOCUMENTO DE ESPECIFICAÇÃO DE REQUISITOS DE SOFTWARE

Neste documento você verá documentação dos requisitos do sistema Conecta.

## 3.1 Objetivos deste documento
Descrever e especificar as necessidades para o desenvolvimento do sistema web que facilitará a conexão entre ONGs e voluntários.

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
Como observado no diagrama de casos de uso da Figura 1, a secretária poderá gerenciar as matrículas e professores no sistema, enquanto o coordenador, além dessas funções, poderá gerenciar os cursos de aperfeiçoamento.

#### Figura 1: Diagrama de Casos de Uso do Sistema.

![dcu](https://github.com/user-attachments/assets/41f6b731-b44e-43aa-911f-423ad6198f47)
 
### 3.4.2 Descrições de Casos de Uso

#### Gerenciar o acesso das ONGs (CSU01) ALICE

**Sumário**: Este caso de uso permite que o representante da ONG gerencie seu acesso na plataforma, incluindo a criação, modificação e exclusão de acesso. O objetivo principal é garantir que o representante da ONG tenha controle sobre suas informações dentro do sistema.

**Ator Primário**: Representante da ONG.

**Ator Secundário**: Administrador.

**Pré-condições**: Não exsitem.

**Fluxo Principal**: Cadastro da ONG.

1)  O representante da ONG acessa a página de login do sistema..
2)  Insere seus dados.
3)  O cadastro da ONG é criado.
4)  O representante da ONG acessa o sistema.

**Fluxo Alternativo**: Alteração de senha.

a)  O representante da ONG acessa a página de editar perfil. <br/>
b)  Seleciona a opção de alterar senha. <br/>
c)  Insere a senha atual e a nova senha.<br/>
d)  A senha do representante da ONG é alterada.<br/>

**Fluxo Alternativo**: Exclusão de acesso.

a)  O representante da ONG acessa a página de editar perfil. <br/>
b)  Seleciona a opção de excluir conta. <br/>
c)  Confirma a exclusão. <br/>
d)  Conta do representante da ONG é excluída do sistema. <br/>

**Pós-condições**: Conta do representante da ONG deve existir ou ser excluída.

#### Gerenciar acesso do voluntário (CSU02) GABRIEL

**Sumário**: Um breve resumo do que o caso de uso faz e qual o seu objetivo principal.

**Ator Primário**: Adicione o ator principal.

**Ator Secundário**: Adicione o ator secundário.

**Pré-condições**: Condições que devem ser atendidas antes que o caso de uso possa ser executado.

**Fluxo Principal**:

1)  Coloque aqui o fluxo.
2)  Coloque aqui o fluxo.
3)  Coloque aqui o fluxo.
4)  Coloque aqui o fluxo...

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Pós-condições**: O que deve ser verdade depois que o caso de uso é concluído com sucesso.

#### Gerenciar acesso do patrocinador (CSU03) OMAR

**Sumário**: Um breve resumo do que o caso de uso faz e qual o seu objetivo principal.

**Ator Primário**: Adicione o ator principal.

**Ator Secundário**: Adicione o ator secundário.

**Pré-condições**: Condições que devem ser atendidas antes que o caso de uso possa ser executado.

**Fluxo Principal**:

1)  Coloque aqui o fluxo.
2)  Coloque aqui o fluxo.
3)  Coloque aqui o fluxo.
4)  Coloque aqui o fluxo...

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Pós-condições**: O que deve ser verdade depois que o caso de uso é concluído com sucesso.

#### Gerenciar perfil das ONGs (CSU04) LEONARDO

**Sumário**: Um breve resumo do que o caso de uso faz e qual o seu objetivo principal.

**Ator Primário**: Adicione o ator principal.

**Ator Secundário**: Adicione o ator secundário.

**Pré-condições**: Condições que devem ser atendidas antes que o caso de uso possa ser executado.

**Fluxo Principal**:

1)  Coloque aqui o fluxo.
2)  Coloque aqui o fluxo.
3)  Coloque aqui o fluxo.
4)  Coloque aqui o fluxo...

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Pós-condições**: O que deve ser verdade depois que o caso de uso é concluído com sucesso.

#### Gerenciar perfil do voluntário (CSU05) JOÃO

**Sumário**: Um breve resumo do que o caso de uso faz e qual o seu objetivo principal.

**Ator Primário**: Adicione o ator principal.

**Ator Secundário**: Adicione o ator secundário.

**Pré-condições**: Condições que devem ser atendidas antes que o caso de uso possa ser executado.

**Fluxo Principal**:

1)  Coloque aqui o fluxo.
2)  Coloque aqui o fluxo.
3)  Coloque aqui o fluxo.
4)  Coloque aqui o fluxo...

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Pós-condições**: O que deve ser verdade depois que o caso de uso é concluído com sucesso.

#### Gerenciar perfil do patrocinador (CSU06) ALICE

**Sumário**: Este caso de uso permite que o patrocinador gerencie as informações do seu perfil no sistema. O objetivo principal é garantir que o patrocinador possa atualizar seus dados de contato, informações da empresa, e acompanhar seu envolvimento em projetos de suporte a ONGs.

**Ator Primário**: Patrocinador.

**Ator Secundário**: Adminstrador.

**Pré-condições**: O patrocinador deve estar cadastrado no sistema com um login e senha válidos.

**Fluxo Principal**: Criar perfil do patrocinador.

1)  O patrocinador faz login no sistema e acessa a área de perfil.
2)  O sistema exibe as informações atuais do perfil do patrocinador.
3)  O patrocinador pode editar as informações de contato, como endereço de e-mail, número de telefone e dados da empresa.
4)  O patrocinador confirma as alterações clicando em "Salvar".
5)  O sistema valida as informações e salva as alterações.

**Fluxo Alternativo**: Edição de dados inválidos.

a)  O patrocinador insere dados inválidos, como um formato de e-mail incorreto ou um número de telefone incompleto. <br/>
b)  O sistema exibe uma mensagem de erro informando quais campos precisam ser corrigidos. <br/>
c)  O patrocinador ajusta as informações e tenta salvar novamente. <br/>

**Pós-condições**: O perfil do patrocinador é atualizado com sucesso no sistema.

#### Gerenciar as demandas (CSU07)

**Sumário**: O Representante da ONG realiza a gestão (inclusão, remoção, alteração e consulta) dos dados sobre as demandas. O objetivo principal é garantir que o Representante tenha controle sobre suas demandas dentro do sistema.

**Ator Primário:** Representante da ONG.

**Ator Secundário:** Não possui.

**Pré-condições:** O Representante deve estar autenticado e validado pelo sistema.

**Fluxo Principal**:
1) 	O Representante requisita gestão de demandas.
2) 	O Sistema apresenta as operações que podem ser realizadas: inclusão, alteração, exclusão e consulta de dados de uma demanda.
3) 	O Representante seleciona a operação desejada: Inclusão, Exclusão, Alteração ou Consulta, ou opta por finalizar o caso de uso.
4) 	Se o Representante desejar continuar com a gestão de demandas, o caso de uso retorna ao passo 2; caso contrário o caso de uso termina.

**Fluxo Alternativo:** Inclusão
a) O Representante requisita a inclusão de uma nova demanda. <br/>
b) O Sistema apresenta um formulário solicitando o nome, tipo e descrição da demanda. <br/>
c) O Representante preenche o formulário com as informações solicitadas. <br/>
d) O Sistema valida os dados fornecidos e uma nova demanda é incluída no sistema. <br/>
    
O Sistema retorna ao início do fluxo principal.

**Fluxo Alternativo:** Consulta
a) O Representante requisita a consulta de uma demanda, podendo buscar pelo tipo e status. <br/>
b) O Sistema apresenta a lista de demandas que atendam aos critérios de busca. <br/>
C) O Representante seleciona uma demanda da lista. <br/>
d) O Sistema exibe os detalhes da demanda selecionada. <br/>

O Sistema retorna ao início do fluxo principal.

**Fluxo Alternativo:** Alteração
a) O Representante seleciona uma demanda existente para alterar e solicita a edição dos seus dados. <br/>
b) O sistema exibe as informações atuais do perfil da demanda. <br/>
c) O Representante altera os dados desejados. <br/>
d) O sistema valida as informações e salva as alterações da demanda.
     
O Sistema retorna ao início do fluxo principal.

**Fluxo Alternativo:** Remoção

a) O Representante seleciona uma demanda existente e requisita a sua remoção. <br/>
b) O Sistema valida se a demanda pode ser excluída. <br/>
c) A demanda existente é removida do sistema. <br/>
   
O Sistema retorna ao início do fluxo principal.

**Pós-condições:** Uma demanda foi inserida, removida, alterada ou consultada com sucesso, de acordo com a operação escolhida pelo Representante. <br/>

#### Gerenciar feedback (CSU08) GABRIEL

**Sumário**: Um breve resumo do que o caso de uso faz e qual o seu objetivo principal.

**Ator Primário**: Adicione o ator principal.

**Ator Secundário**: Adicione o ator secundário.

**Pré-condições**: Condições que devem ser atendidas antes que o caso de uso possa ser executado.

**Fluxo Principal**:

1)  Coloque aqui o fluxo.
2)  Coloque aqui o fluxo.
3)  Coloque aqui o fluxo.
4)  Coloque aqui o fluxo...

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Pós-condições**: O que deve ser verdade depois que o caso de uso é concluído com sucesso.

#### Gerenciar trabalhos voluntários (CSU09)

**Sumário:** O Voluntário de TI realiza a gestão (inclusão, remoção, alteração e consulta) dos dados sobre os trabalhos candidatados.  O objetivo principal é garantir que o Voluntário tenha controle sobre suas candidaturas dentro do sistema.

**Ator Primário:** Voluntário de TI.

**Ator Secundário:** Não possui.

**Pré-condições:** O Representante deve estar autenticado e validado pelo sistema.

**Fluxo Principal:**

1) 	O Voluntário de TI requisita gestão de trabalhos voluntários.
2) 	O Sistema apresenta as operações que podem ser realizadas: inclusão, alteração, exclusão e consulta de dados de uma candidatura.
3) 	O Voluntário seleciona a operação desejada: Inclusão, Exclusão, Alteração ou Consulta, ou opta por finalizar o caso de uso.
4) 	Se o Voluntário desejar continuar com a gestão de candidaturas, o caso de uso retorna ao passo 2; caso contrário o caso de uso termina.

**Fluxo Alternativo:** Inclusão
A) O Voluntário requisita a inclusão de uma nova candidatura. <br/>
B) O Sistema apresenta um formulário solicitando o nome, CPF, e-mail, telefone e descrição de suas capacidades para a candidatura. <br/>
C) O Voluntário preenche o formulário com as informações solicitadas. <br/>
D) O Sistema valida os dados fornecidos e uma nova candidatura é incluída no sistema.
    
O Sistema retorna ao início do fluxo principal.

**Fluxo Alternativo:** Consulta
A) O Voluntário requisita a consulta de uma candidatura, podendo buscar pelo tipo e status.
B) O Sistema apresenta a lista de demandas que atendem aos critérios de busca. <br/>
C) O Voluntário seleciona uma candidatura da lista. <br/>
D) O Sistema exibe os detalhes da demanda selecionada. <br/>

O Sistema retorna ao início do fluxo principal.

**Fluxo Alternativo:** Alteração
A) O Voluntário seleciona uma candidatura existente para alterar e solicita a edição dos seus dados. <br/>
B) O Sistema apresenta os dados atuais da candidatura para edição. <br/>
C) O Representante altera os dados desejados. <br/>
D) O Sistema valida as informações e salva as alterações.
     
O Sistema retorna ao início do fluxo principal.

**Fluxo Alternativo:** Remoção
A) O Voluntário seleciona uma candidatura existente e requisita a sua remoção. <br/>
b) O Sistema valida se a demanda pode ser excluída. <br/>
c) A demanda existente é removida do sistema. <br/>
     
O Sistema retorna ao início do fluxo principal.

Pós-condições:  Uma candidatura foi inserida, removida, alterada ou consultada com sucesso, de acordo com a operação escolhida pelo Voluntário de TI.

#### Gerenciar patrocínios (CSU010) OMAR

**Sumário**: Um breve resumo do que o caso de uso faz e qual o seu objetivo principal.

**Ator Primário**: Adicione o ator principal.

**Ator Secundário**: Adicione o ator secundário.

**Pré-condições**: Condições que devem ser atendidas antes que o caso de uso possa ser executado.

**Fluxo Principal**:

1)  Coloque aqui o fluxo.
2)  Coloque aqui o fluxo.
3)  Coloque aqui o fluxo.
4)  Coloque aqui o fluxo...

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Pós-condições**: O que deve ser verdade depois que o caso de uso é concluído com sucesso.

#### Gerenciar conteúdo de páginas informativas (CSU011) LEONARDO

**Sumário**: Um breve resumo do que o caso de uso faz e qual o seu objetivo principal.

**Ator Primário**: Adicione o ator principal.

**Ator Secundário**: Adicione o ator secundário.

**Pré-condições**: Condições que devem ser atendidas antes que o caso de uso possa ser executado.

**Fluxo Principal**:

1)  Coloque aqui o fluxo.
2)  Coloque aqui o fluxo.
3)  Coloque aqui o fluxo.
4)  Coloque aqui o fluxo...

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Pós-condições**: O que deve ser verdade depois que o caso de uso é concluído com sucesso.

#### Enviar notificação do trabalho voluntário (CSU012) JOÃO

**Sumário**: Um breve resumo do que o caso de uso faz e qual o seu objetivo principal.

**Ator Primário**: Adicione o ator principal.

**Ator Secundário**: Adicione o ator secundário.

**Pré-condições**: Condições que devem ser atendidas antes que o caso de uso possa ser executado.

**Fluxo Principal**:

1)  Coloque aqui o fluxo.
2)  Coloque aqui o fluxo.
3)  Coloque aqui o fluxo.
4)  Coloque aqui o fluxo...

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Fluxo Alternativo**: Coloque aqui o nome fluxo alternativo caso houver.

a)  Descreva o fluxo alternativo caso houver. <br/>
b)  Descreva o fluxo alternativo caso houver. <br/>
c)  Descreva o fluxo alternativo caso houver... <br/>

**Pós-condições**: O que deve ser verdade depois que o caso de uso é concluído com sucesso.

#### Enviar recomendação de demanda (CSU013)

**Sumário**: O sistema envia recomendações de demandas voluntárias para o Voluntário de TI, com base no perfil e nas candidaturas anteriores registradas no sistema. O objetivo é facilitar o acesso a novas oportunidades de trabalho voluntário.

**Ator Primário**: Sistema.

**Ator Secundário**: Voluntário de TI.

**Pré-condições**: O Voluntário de TI deve estar autenticado e possuir candidaturas ou informações de perfil relevantes registradas no sistema.

**Fluxo Principal**:

1)  O Sistema analisa as candidaturas e o perfil do Voluntário de TI.
2)  O Sistema gera uma lista de demandas que se alinham ao perfil do Voluntário.
3)  O Sistema envia uma notificação para o Voluntário de TI com as recomendações de demandas disponíveis.
4)  O Voluntário de TI recebe a notificação e acessa as demandas recomendadas.

**Fluxo Alternativo**: Nenhuma demanda disponível.
a)  Se o Sistema não encontrar nenhuma demanda correspondente, ele notifica o Voluntário de TI informando que não há novas demandas disponíveis no momento. <br/>
b)  O Sistema retorna ao início do fluxo principal e permanece aguardando novas demandas. <br/>

**Fluxo Alternativo**: Voluntário ignora a recomendação.
a)  Se o Voluntário optar por não visualizar as recomendações no momento, o Sistema mantém as recomendações no histórico de notificações para consulta posterior. <br/>
b)  O Voluntário pode acessar as recomendações quando desejar. <br/>

**Pós-condições**: O Voluntário de TI recebe as recomendações de novas demandas, podendo consultar as oportunidades que melhor correspondem ao seu perfil. Caso não haja demandas disponíveis, o Voluntário é notificado da ausência de recomendações no momento.

#### Sair do sistema (CSU014) ALICE

**Sumário**: Este caso de uso permite que o usuário saia do sistema de forma segura. O objetivo principal é garantir que as sessões de usuário sejam encerradas adequadamente.

**Ator Primário**: Todos os usuários.

**Ator Secundário**: Nenhum.

**Pré-condições**: O usuário deve estar autenticado no sistema, com uma sessão ativa.

**Fluxo Principal**: Sair da aplicação.

1)  O usuário clica no botão "Sair" disponível no menu do sistema.
2)  O sistema exibe uma mensagem de confirmação perguntando se o usuário deseja realmente sair.
3)  O usuário confirma que deseja sair clicando em "Sim".
4)  O sistema encerra a sessão do usuário e redireciona para a página de login.
5)  O sistema exibe uma mensagem informando que o logout foi realizado com sucesso.

**Fluxo Alternativo**: Cancelar logout.

a)  O usuário clica no botão "Cancelar" após a mensagem de confirmação. <br/>
b)  O sistema mantém a sessão ativa e retorna ao menu principal. <br/>
c)  O usuário continua a interagir com o sistema normalmente. <br/>

**Pós-condições**: A sessão do usuário é encerrada e não pode mais ser acessada até que um novo login seja realizado.

### 3.4.3 Diagrama de Classes 

A Figura 2 mostra o diagrama de classes do sistema. A Matrícula deve conter a identificação do funcionário responsável pelo registro, bem com os dados do aluno e turmas. Para uma disciplina podemos ter diversas turmas, mas apenas um professor responsável por ela.

#### Figura 2: Diagrama de Classes do Sistema.
 
![dcu](https://github.com/user-attachments/assets/97ab1aa8-eb03-4b58-9ad5-1697d414a451)

### 3.4.4 Descrições das Classes 

| # | Nome | Descrição |
|--------------------|------------------------------------|----------------------------------------|
| 1 |   Aluno | Cadastro de informações relativas aos alunos. |
| 2 | Curso |   Cadastro geral de cursos de aperfeiçoamento. |
| 3 |   Matrícula | Cadastro de Matrículas de alunos nos cursos. |
| 4 |   Turma | Cadastro de turmas.
| 5 |   Professor | Cadastro geral de professores que ministram as disciplinas. |
| ... | ... |   ... |
