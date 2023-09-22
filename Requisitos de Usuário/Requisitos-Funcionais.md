# Requisitos Funcionais

|Identificador | Descrição                                                                                                                | Prioridade | Depende de |
|-------|-------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|----|
| RF01 |        O sistema deve permitir o cadastro de estudantes de faculdade interessados em vagas de estágio.                        | Alta|
|      |        Os campos obrigatórios para o cadastro devem incluir nome, e-mail, faculdade, curso e ano de ingresso.                  | 
| RF02 |        O sistema deve permitir o cadastro de empresas que oferecem vagas de estágio.                                           | Alta |
|      |        Os campos obrigatórios para o cadastro devem incluir nome da empresa, e-mail de contato e área de atuação.             | 
| RF03 |        As empresas cadastradas devem poder publicar vagas de estágio disponíveis.                                              | Alta| RF02|
|      |        As informações necessárias para a publicação devem incluir título da vaga, descrição, requisitos e localização.         |
| RF04 |        Os estudantes devem poder pesquisar vagas de estágio disponíveis com base em critérios como área de atuação, cidade e requisitos. | Alta| RF01, RF02|
|      |        Os resultados da pesquisa devem ser apresentados de forma clara e organizada.                                          |
| RF05 |        Os estudantes devem poder se candidatar a vagas de estágio que atendam aos seus interesses e requisitos.                | Alta | RF01, RF02, RF03, RF04 |
|      |        O sistema deve permitir o envio de currículo e carta de apresentação como parte da candidatura.                           |
| RF06 |        As empresas devem poder visualizar e gerenciar as candidaturas recebidas para suas vagas de estágio.                     | Média | RF01, RF02, RF03, RF04, RF05 |
|      |        O sistema deve permitir a comunicação entre empresas e estudantes durante o processo de seleção.                        |
| RF07 |        As empresas devem poder avaliar os candidatos e registrar suas análises no sistema.                                      | Média|   RF01, RF02, RF03, FR04, RF05, RF06 |
|      |        O sistema deve permitir a classificação dos candidatos de acordo com critérios pré-definidos.                           |
| RF08 |        O sistema deve enviar notificações e alertas para os estudantes sobre novas vagas de estágio e atualizações nas suas candidaturas. | Baixa| RF01, RF02, RF03, RF04,RF05, RF06, RF07 |
| RF09 |        O sistema deve gerar relatórios e estatísticas sobre o número de vagas, candidaturas, empresas cadastradas e outros dados relevantes. | Baixa| RF01, RF02, RF03, RF04, RF05, RF06, RF07, RF08 |


