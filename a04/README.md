# Ficha de Identificação

Nome completo : Diogo Cezar Teixeira Batista
Sistema Avaliado : PicPay (Mobile)
Técnica(s) aplicada(s) : Heurísticas de Nielsen
Tempo de avaliação: 52 minutos
Total de problemas encontrados: 12

# Descrição dos principais problemas, severidade e sugestões

#1 Ajuda sem ajuda

Descrição: Na tela de login, ao tocar no botão de ajuda se é redirecionado para o assistente virtual. Na tela não se tem informações sobre o que é possível fazer. Apenas um campo de texto com o placeHolder "Digite sua mensagem..."

Reprodução: Entrar no aplicativo pela primeira vez deve-se clicar no ícone com um caractere: ?

Severidade: 3

Heurísticas: 9. Ajude os usuários a reconhecerem, diagnosticarem e recuperarem-se de erros.

Proposta de melhoria ou correção: Um texto inicial apresentando o sistema e dando alguns exemplos de opções de ajuda.

---

#4 Campo de email com placeholder que confunde

Descrição: Ao realizar a autorização do dispositivo, um dos campos a serem preenchidos é o email. Este campo veio preenchido automaticamente com dio\*\*@diogocezar.com. Não fica intuitivo para o usuário o que deve ser feito. Depois de tentar alterar o texto, notei que era apenas um placeHolder para tentar "lembrar" qual era o e-mail cadastrado.

Reprodução: Entrar no fluxo de autorização do aplicativo e tentar preencher o e-mail.

Severidade: 3

Heurísticas: 9. Ajude os usuários a reconhecerem, diagnosticarem e recuperarem-se de erros.

Proposta de melhoria ou correção: Retirar o placeholder, ou colocar como uma sugestão abaixo do campo.

---

#5 A conta bancária não possui validação na autenticação do dispositivo

Descrição: No momento da inserção dos campos de conta bancária, não existe qualquer tipo de validação dos campos com relação a número de dígitos, letras ou números.

Reprodução: Entrar no fluxo de autorização do aplicativo seguir até ser necessário informar a conta bancária.

Severidade: 3

Heurísticas: 9. Ajude os usuários a reconhecerem, diagnosticarem e recuperarem-se de erros.

Proposta de melhoria ou correção: Validar os campos de acordo com os padrões de contas bancárias.

---

#6 É necessário preencher novamente todos os campos

Descrição: Ao sair do aplicativo no meio do fluxo de cadastro autenticação do dispositivo (necessário para obter a conta do banco cadastrado em outro aplicativo) foi necessário preencher novamente todas as informações anteriormente já digitadas.

Reprodução: Entrar no fluxo de autorização, fechar o aplicativo, abrir o aplicativo novamente.

Heurísticas: 1. Visibilidade de qual estado estamos no sistema e 3. Liberdade de controle fácil pro usuário.

Severidade: 3

Proposta de melhoria ou correção: Trazer os campos já preenchidos, ou pular etapas que já foram realizadas.

---

#7 Ícones não representativos

Descrição: Os ícones ao topo do aplicativo não são intuitivos. O presente? O que significa? A porcentagem? Os quadrados iniciais?

Reprodução: Chegar até a tela principal do aplicativo.

Severidade: 3

Heurísticas: 2. Correspondência entre o sistema e o mundo real

Proposta de melhoria ou correção: Utilizar algum tipo de label para sinalizar o que representa cada um dos ícones.

# Apreciação geral da qualidade do sistema com base nos resultados da sua avaliação individual

O sistema possui inconsistências de validações. Por exemplo, para validações do mesmo tipo, são entregues diferentes regras e estilos. Além disso, o aplicativo parece ter sido desenvolvido por times diferentes, cada "módulo" parece ter sido feito por uma equipe. Não há uma consistência de estilos para o aplicativo como um todo.

Quanto a usabilidade, as principais funções parecem ser bastante intuitivas, mas as menos utilizadas não parecem ter tido o mesmo cuidado.

Outro ponto negativo foi a tentativa de "incentivo" com call-to-actions no meio de funcionalidades comuns, como por exemplo a lista de transações efetuadas.

# Apreciação sobre a capacidade da técnica de revelar problemas

A técnica consegue fornecer um ótimo guia para orientar quais pontos podem ser observados. Ao encontrar um problema é muito fácil conseguir classificá-lo de acordo com as heurísticas de Nielsen.

As heurísticas aplicadas parecem ser bem adequadas na avaliação de sistemas para web e/ou aplicativos para smartphones. Pois analisam de fato quais podem ser as principais dificuldades dos usuários ao utilizarem estes sistemas.
