# Introdução à pesquisa em IHC

Na Leitura 1, Hornbæk e Oulasvirta levantam uma pergunta que, embora pareça trivial, não é fácil de ser respondida: "O que é interação?"

Apresentando 7 possíveis formas de entender o conceito de interação, os autores discutem cada conceito em termos de 4 pontos (Tabela 1 do artigo): i) do modo como cada conceito nos permite enxergar a interação; ii) fenômenos chave envolvidos; iii) características de uma boa interação; e iv) formas de apoio ao design e avaliação.

Considerando o seu trabalho (pode ser TCC, Dissertação, Tese, ou trabalho/uso de um sistema computacional interativo), escolha o conceito de Interação que mais se aplica, exemplificando-o nos 4 pontos acima. Se nenhum dos conceitos se aplica, então apresente um conceito alternativo e discuta seu trabalho sob a luz desse conceito nos mesmos 4 pontos.

Explique porquê o conceito escolhido é o mais representativo, apontando suas possibilidades e limitações.

Compartilhe seu texto criando um novo tópico neste fórum. O texto deve estar no corpo do post.

Não há nenhuma outra exigência: apenas faça o texto refletindo o melhor de sua capacidade de entendimento e reflexão!

---

Olá a todos, meu nome é Diogo Cezar, estou cursando Doutorado no programa colaborativo entre UFPR e UTFPR Campus Cornélio Procópio.

Fiz meu mestrado também na UFPR em IA, lessionei em períodos diferentes na UTFPR de Cornélio Procópio e atualmente atuo também como Tech Lead no Banco Neon.

O tema da minha pesquisa está relacionado com a exploração de métodos, técnicas ou ferramentas de Engenharia de Software para o desenvolvimento de sistemas de monitoramento de plantações e de colaboração entre usuários no contexto da Agricultura 4.0. Estas inovações da agricultura exploram a utilização das mais recentes tecnologias computacionais tais como: a automação, a robótica agrícola, big data, a Internet das Coisas, entre outras. Com essa exploração, busca-se uma produção agrícola eficiente e sustentável, além de ferramentas que apoiem as tomadas de decisão por parte dos envolvidos em toda a cadeia agrícola.

Entretanto, o acesso aos recursos necessários, como sensores, para a exploração dessas tecnologias não é a realidade de grande parte do setor agrícola. Adicionalmente, a resistência na adoção de novas tecnologias é um problema ainda em aberto. Por isso, a exploração de métodos, técnicas ou ferramentas para a elaboração de um sistema que possa aproximar os agricultores da tecnologia, bem como, mostrar os benefícios da tomada de decisão de forma colaborativa são temas a serem abordados pelo trabalho.

Desta forma, o conceito que mais se aplica ao trabalho é o de Interação como Transmissão. Um dos grandes objetivos é possibilitar a inclusão de ferramentas tecnológicas de forma inclusiva, colaborativa, eficiente e eficaz a um baixo custo. Para isso, uma das possibilidades do trabalho é direcionar a exploração de métodos, técnicas ou ferramentas para o desenvolvimento soluções de dispositivos móveis. Estes dispositivos, já estão inseridos no dia a dia de grande dos usuários que compõem a cadeia agrícola, por isso, a interação através da transmissão de informações entre o computador e o usuário final parecem fazer bastante sentido, principalmente quando o foco pode estar justamente nas particularidades que realizam a geração de informações relevantes, através utilização de IA ou através de sistema de inferência colaborativa, por exemplo.

Também é possível notar certa intercessão com a técnica de Interação relacionada a Experiência, principalmente nos tópicos relacionados a colaboração.

## Modo como o conceito nos permite exergar a interação

Um dos principais objetivos do trabalho, também destacado pelo texto de Hornbæk, é propor uma solução que tenha o foco no design da solução de interação, principalmente nos pontos relacionados a usabilidade e experiência do usuário. Tornar o processo de interação fácil, amigável, inclusivo é parte fundamental para incluir e converter os usuários que eventualmente se matém distantes da tecnologia.

## Fenômenos chave envolvidos

Não basta focar na interação se não houver uma informação relevante e que realmente contribua. Por este motivo, procura-se considerar como premissas do trabalho a geração de informações relevantes, e que possam ser apresentadas e entendidas de maneira eficiênte.

## Características de uma boa interação

Neste caso, identificar uma boa interação está relacionado com a satisfação do usuário ao utilizar a tecnologia de apoio a sua decisão.

## Formas de apoio ao projeto e avaliação

Pode-se utilizar alguns métodos para a validação da solução, que buscam analisar métricas e performance dos usuários tais como:

- Testes A/B;
- Análise de Abandono;
- Avaliação do Aplicativo;
- Análise de Usuários Ativos do Aplicativo;
- Análise de Engajamento;

## Definição de um cenário possível

Para ilustrar as possibilidades a serem exploradas, descreve-se a utilização de um aplicativo em um cenário hipotético, no qual:

- Um fazendeiro, motivado pelo desconhecimento de uma praga, captura uma imagem de um inseto em uma planta de soja usando seu \textit{smartphone};
- A imagem pode receber informações adicionais no próprio \textit{smartphone}, tais como: anotações da quantidade, nome do inseto, enfatizando o tamanho do inseto e o estádio fenológico da planta;
- Ainda na imagem, pode ser possível a inclusão de anotações ou destaques em pontos que pudessem ser circulados, pelo fazendeiro, demonstrando pontos de atenção que pudessem ser analisados;
- Um engenheiro agrônomo, parceiro deste fazendeiro, analisa a mesma imagem em seu próprio perfil do aplicativo, de forma remota, inserindo e/ou complementando informações sobre o cenário investigado;
- Todas as imagens poderiam servir de fonte de dados: a original, a com as anotações do fazendeiro e do engenheiro agrônomo;
- Por conta de uma possível dificuldade de conexão (muito comum no cenário rural) o envio das informações poderia não acontecer imediatamente. Mas a operação pode ser marcada como sucesso, deixando essa atividade uma fila de execução em \textit{background};
- O próprio sistema registra as coordenadas de geolocalização bem como o momento (horário/dia) desta captura ou oferece a possibilidade de inserção manual destas informações (prevendo a instabilidade da conexão);
- Ao receber as informações, um sistema computacional em nuvem, pode relacionar as imagens recebidas com uma ou mais imagens aéreas, capturadas por veículos aéreos não tripulados da mesma região onde está a planta, ou regiões adjacentes em um ou mais momentos anteriores, buscando por insetos. O sistema computacional pode registrar dia e horário de captura da imagem, de modificação, de envio com sucesso;
- O sistema computacional pode ainda utilizar utilizar bases de informações compartilhadas entre diferentes regiões e usuários aumentando o refinamento na inferência das informações de apoio a decisão.
