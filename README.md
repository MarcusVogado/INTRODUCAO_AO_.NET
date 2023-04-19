 <h1><b>INTRODUÇÃO AO .NET RESUMO - MARCUS VOGADO</b></h1>
           <h2><b>HISTÓRICO DO .NET RESUMIDO RETIRADO DA DOCUMENTAÇÃO EM <a href="https://learn.microsoft.com/pt-br/training/modules/dotnet-introduction/2-what-is-dotnet" target="_blank">INTRODUÇÃO AO .NET </a></b></h2> 
            O .NET Framework original foi lançado no início de 2002. Desde então, muitas atualizações e diversas outras funcionalidades foram introduzidas. Depois de anos de aprimoramentos e novos recursos, o .NET Framework original, especialmente as bibliotecas de código-chave, cresceu significativamente.

Depois de 2002, a Microsoft trabalhou para criar uma versão do .NET com compatibilidade entre plataformas. O objetivo era permitir que os desenvolvedores escrevessem uma base de código e a usassem em sistemas operacionais macOS, Linux e Windows.

Por meio desses esforços, o .NET Core foi introduzido por volta de 2014. A Microsoft manteve o .NET Framework original, mas novos recursos e aprimoramentos foram reservados para o .NET Core. O Core foi posteriormente descartado do nome. As versões principais seguintes foram .NET 5, .NET 6, .NET 7 e assim por diante. As versões geralmente são lançadas em novembro.

Por que é relevante mencionar o histórico do .NET? Porque você provavelmente encontrará postagens no blog, vídeos e código-fonte direcionados ao .NET Framework original. Em alguns casos, as instruções ou o código ainda funcionam, porém, em outros, talvez seja necessário fazer ajustes para se adequar ao novo .NET.<br>
            
<h4><b>OQUE É O .NET? </b></h4>
            
.NET(DOT NET) PODE SER RESUMIDO COMO UM ECOSSISTEMA QUE É COMPOSTO POR MUITAS PARTES E PESSOAS
 QUE FORMAM UM AMBIENTE DE DESENVOLVIMENTO DE APLICATIVOS.<br> 
 
<b>USAR OS COMPLILADORES E AS LINGUAGENS . NET PARA EXECUTAR APLICATIVOS NO RUNTIME DO .NET</b><br>

Compilador do .NET é um programa que converte o código fonte  em uma linguagem especial chamada IL -linguagem intermediaária.<br>
Runtime do .NET é uma abiente de execução para o seu assembly do .NET compilado, em resumo o runtime é o que executa e gerencia o seu aplicativo<br>

<h4>IMPORTANTE</h4><br>

C#(CSharp) não é a mesma coisa do .NET erroneamente as pessoas acham que se trata da mesma coisa,<br>
intenda que C# é uma sintaxe de linguagem de programção.<br>
Que você pode referenciar e chamar métodos definos em assemblies, ou bibliotecas de código do .NET.<br>


<h4><b>USAR BIBLIOTECAS E ESTRUTURAS DE APLICATIVOS DO .NET PARA APROVEITAR A FUNCIONALIDADE PRÉ CRIADA</b></h4>
Todos os softwares são criados em camadas, o que significa que são executados em vários níveis de abstração em um computador:

No nível mais baixo, o software se comunica diretamente com o hardware do computador. Ele controla o fluxo de dados na placa-mãe, nos processadores, na memória e nos discos rígidos.<br>
No nível seguinte, o software permite que o usuário final forneça instruções por meio de um sistema operacional.<br>
No próximo nível, um software como o .NET fornece uma maneira para você desenvolver e executar aplicativos.<br>
No nível seguinte, as estruturas de aplicativo e as bibliotecas de funcionalidade permitem criar rapidamente aplicativos avançados usando menos esforço do que os métodos de desenvolvimento mais antigos permitiam.

<h4><b>PRINCIPAIS MODELOS DE APLICATIVOS</b></h4>

<b>Web	ASP.NET Core</b>	A estrutura para a criação da lógica do lado do servidor.<br>
<b>Web	ASP.NET Core MVC</b>	A estrutura para a criação da lógica do lado do servidor para páginas da Web ou APIs Web.<br>
<b>Web	Razor Pages do ASP.NET</b> Core	A estrutura para a criação de HTML gerado pelo servidor.<br>
<b>Cliente Web	Blazor</b>	O Blazor é uma parte do ASP.NET Core. Os dois modos dele permitem a manipulação de DOM (Modelo de Objeto do Documento) por meio de soquetes como um veículo de comunicação para a execução de código do lado do servidor ou como uma implementação do WebAssembly para a execução do C# compilado no navegador.<br>
<b>Desktop	WinForms</b>	Uma estrutura para criar aplicativos no estilo "acinzentado" do Windows.<br>
<b>Desktop	Windows Presentation Foundation (WPF)</b>	Uma estrutura para criar aplicativos da área de trabalho dinâmicos em conformidade com diferentes fatores forma. O WPF permite que os elementos da forma realizem movimentos, esmaecimentos, deslizamentos e outros efeitos com a ajuda de uma biblioteca de animações avançada.<br>
<b>Móvel	Xamarin</b>	Permite que os desenvolvedores do .NET criem aplicativos para dispositivos iOS e Android.<br>
E também temos o <b>.NET MAUI</b> para desenvolvimento Móvel<br>
 
<h4><b>Como os desenvolvedores usam o .NET para criar aplicativos</b><h4>
Esta seção descreve o fluxo de trabalho de desenvolvimento de aplicativos no .NET. Ela inclui detalhes sobre como começar a criar um aplicativo no .NET.

 <h4><b>Configurar seu ambiente de desenvolvimento</b></h4>
A primeira decisão tomada pelos desenvolvedores é selecionar as ferramentas que usarão para criar os aplicativos. Em outras palavras, eles selecionam o ambiente de desenvolvimento. Normalmente, a decisão é baseada na preferência por um fluxo de trabalho mais visual com uma interface gráfica do usuário ou por uma interface de linha de comando na qual eles dependerão quase exclusivamente do teclado para navegar no ambiente de desenvolvimento e emitir comandos.

 <h5><b>Observação</b></h5>

No final deste módulo, você encontrará links que ajudarão a configurar seu ambiente de desenvolvimento. Você pode escolher o Visual Studio 2022 ou o Visual Studio Code e o SDK (Software Development Kit) do .NET.

Para os desenvolvedores que preferem um ambiente visual, o Visual Studio 2022 é a melhor opção. Como você pode imaginar, devido à natureza abrangente e visual do Visual Studio 2022, ele requer mais tempo, largura de banda e espaço em disco para baixar e instalar o programa. No entanto, alguns iniciantes consideram essa a maneira mais fácil de começar. Dependendo da velocidade da conexão com a Internet, a instalação pode levar 15 minutos ou mais.

O Instalador do Visual Studio no Visual Studio 2022 oferece opções na forma de cargas de trabalho. Uma carga de trabalho é uma coleção de estruturas, bibliotecas e outras ferramentas que trabalham em conjunto para criar um modelo de aplicativo específico. Com base no que aprendeu na unidade anterior, verifique se você instalou a carga de trabalho .NET Core para desenvolvimento multiplataforma para criar aplicativos.

A carga de trabalho .NET Core para desenvolvimento multiplataforma instala o SDK do .NET. O SDK do .NET contém todas as bibliotecas, ferramentas e modelos necessários para começar a escrever código.

Se você preferir um ambiente de linha de comando, baixe e instale o Visual Studio Code e o SDK do .NET separadamente. Essa opção é popular entre iniciantes que desejam começar rapidamente. Ambas as ferramentas exigem menos largura de banda para serem baixadas.

<h4><b>Introdução</b></h4>
Normalmente, os projetos de desenvolvimento de software começam com um conjunto de requisitos. Esses requisitos afetam as escolhas do modelo de aplicativo. O modelo de aplicativo escolhido pode ser um aplicativo Web, de área de trabalho ou móvel ou um processo em segundo plano, por exemplo.

Ao usar o Visual Studio 2022 ou a CLI do .NET, você normalmente começa criando um projeto com base em um modelo. É possível escolher entre muitos modelos de projeto. Modelos de projeto:

Gere pastas e arquivos com base em modelos e no nome do projeto que você definir.
Adicione referências a bibliotecas usadas normalmente e a bibliotecas exigidas pela estrutura do modelo de aplicativo.
Forneça o código necessário para executar o aplicativo e ver uma pequena amostra a fim de confirmar que o código é compilado.
Em algumas ocasiões, inclua instruções no código. Essas instruções mostram como modificar o aplicativo de exemplo e fazer o seu.
No Visual Studio 2022, a caixa de diálogo Novo Projeto ajuda você a escolher visualmente um modelo de aplicativo entre um conjunto de modelos instalados ou a escolher entre muitas contribuições da comunidade. Na CLI do .NET, escolha um novo modelo de projeto usando uma combinação de comando e sinalizadores.

<h4><b>Criar uma funcionalidade</b></h4>
Em seguida, comece a escrever a lógica do seu aplicativo. Adicione referências a bibliotecas de código quando precisar realizar tarefas especiais, como:

Conectar-se a recursos de rede
Acessar um banco de dados para armazenar ou recuperar dados
Converter dados de um formato para outro
Adicionar registros em log para diagnosticar problemas com seu aplicativo
Em alguns casos, as bibliotecas de código que você deseja usar já existem no disco rígido local porque foram instaladas junto com o SDK do .NET.

Em outros casos, os desenvolvedores usam o gerenciador de pacotes do NuGet para baixar e criar referências às bibliotecas de assembly. Para recuperar esses recursos – dependendo do ambiente de desenvolvimento –, você pode usar a caixa de diálogo Gerenciador de Pacotes NuGet do Visual Studio ou a interface de linha de comando da CLI do .NET.

<h4><b>Compilar e executar seu aplicativo</b></h4>
Ao criar uma funcionalidade, você cria seu código e o executa com frequência. Esse fluxo de trabalho permite avaliar o que funciona corretamente e o que precisa de revisão. A abordagem visual e a abordagem de linha de comando usam comandos simples que tornam o fluxo de trabalho mais fácil de seguir.

A sintaxe do código é considerada incorreta quando a sintaxe não segue as regras do idioma. Quando a sintaxe está errada, o compilador do .NET para sua linguagem gera um erro de compilação. O compilador não continuará até que você corrija o problema de sintaxe.

Às vezes, o código pode ser compilado porque segue as regras de sintaxe, mas a lógica do aplicativo tem problemas. Se a lógica impedir que o tempo de execução do .NET execute um comando, o programa "trava". O tempo de execução do .NET remove o programa da memória do computador. Esses erros são chamados de erros de runtime ou exceções.

 <h5><b>Dica</b></h5>

Felizmente, é possível evitar de forma programática que mensagens de erro ruins cheguem aos usuários. Saiba mais pesquisando os tutoriais e a documentação sobre "manipulação de exceção estruturada".

Alguns erros lógicos não resultam em uma "falha". Mas eles também não produzem os resultados esperados pelos seus usuários. Você pode corrigir esses erros apenas testando e depurando seu aplicativo.

 <h4><b>Depurar seu aplicativo</b></h4>
Durante a criação do software, você executará o aplicativo para avaliar se ele atende às suas necessidades e expectativas. Talvez você descubra um bug no seu aplicativo, mas não tenha certeza do porquê de ele está ocorrendo ou de como consertá-lo.

Ao depurar, observe a execução do seu aplicativo para entender o que está acontecendo. Você pode definir pontos de interrupção que pausam o aplicativo e permitem que você siga o código conforme ele é executado. Observe o valor armazenado nas variáveis, controle o roteiro de execução por meio do código para ignorar ou executar novamente algumas linhas, altere o valor das variáveis e assim por diante.

As ferramentas de depuração de linha de comando e visuais permitem observar e controlar a execução do aplicativo. Use essa funcionalidade para ver o que está acontecendo em seu aplicativo enquanto ele está em execução.

<h4><b>Distribuir o aplicativo</b></h4>
Quando o aplicativo estiver pronto para ser liberado, você criará uma versão de lançamento do build. Em uma versão de lançamento, você remove o código necessário para depuração. Novamente, nas ferramentas de linha de comando e visuais, você pode compilar uma versão de lançamento.

Para executar a versão de lançamento, instale o runtime do .NET no computador de destino. Esse computador executará o assembly do .NET compilado.

<h4><b>Como o .NET funciona no runtime</b></h4>
Após a instalação do assembly do .NET e do runtime do .NET do aplicativo no computador de destino, você poderá executar o aplicativo.

O runtime do .NET é como uma bolha protetora que fornece um ambiente de execução para seus aplicativos. O runtime do .NET:

Compila o código intermediário em um formato binário na primeira vez que o programa é executado. O formato binário é específico para a plataforma e a arquitetura (por exemplo, Windows de 64 bits) no computador em que ele está sendo executado.
Localiza o ponto de entrada do programa e começa a executar cada instrução na sequência apropriada.
Gerencia os recursos do computador, como memória e acesso à rede. Quando você ouve que o runtime do .NET "gerencia memória", isso significa que ele funciona com o sistema operacional para provisionar memória para seu aplicativo. Quando o aplicativo não precisar mais dos dados armazenados na memória, um recurso de coleta de lixo liberará essa memória de volta para o sistema operacional sem nenhuma instrução do desenvolvedor de software.
Protege o computador do usuário de softwares potencialmente mal-intencionados. Ele também fornece uma camada de isolamento entre aplicativos.<br>
 
 <h4><b>O .NET é para projetos grandes e pequenos</b></h4>
Você pode se perguntar se o .NET é o ecossistema certo para investir seu tempo. Milhões de desenvolvedores usam o .NET todos os dias para fazer coisas incríveis. Ele fornece ferramentas para criar os tipos de aplicativos que são importantes para eles.

<h4><b>Escolha o .NET quando a produtividade for importante</b></h4>
Depois de aprender a criar um aplicativo baseado em um modelo de aplicativo, você poderá aplicar facilmente o que aprendeu para criar outro item, mesmo que seja algo baseado em um modelo de aplicativo diferente. Por exemplo, depois que você aprender a criar um aplicativo Web, suas habilidades em .NET possibilitam a criação de um aplicativo móvel.

A reutilização do seu conhecimento reduz o tempo e o estresse envolvidos no aprendizado de um novo modelo ou linguagem de programação. Assim, sua empresa poupa tempo e dinheiro quando você recebe tarefas com novos desafios.

<h4><b>Escolha o .NET para aplicativos de escala corporativa</b></h4>
O .NET é popular nas empresas por vários motivos. As vantagens incluem o ecossistema dele e a integração com outros produtos da Microsoft, incluindo os serviços de nuvem do Azure e os produtos para servidores locais. Além disso, o .NET é um sistema fortemente tipado, o que evita muitos dos bugs que podem surgir em sistemas sem rigidez de tipos. Os desenvolvedores podem escolher entre um paradigma baseado em objeto em C# ou um paradigma baseado em funcionalidade em F#. Eles usam a linguagem que melhor se adapta aos tipos de problemas que precisam resolver.

<h4><b>Escolher o .NET para aplicativos de protótipo, de inicialização e de pequena escala</b></h4>
O .NET também é popular para projetos menores devido a um longo histórico de aprimoramentos no design das linguagens, APIs e ferramentas com base na telemetria e nos comentários dos clientes. Você pode usá-lo para desenvolver softwares completos rapidamente para fins de protótipo. Além disso, o .NET pode ser executado em serviços de nuvem e hardware de baixo custo. Ele também tem desempenho superior ao de outras plataformas populares, o que o torna uma ótima opção para empresas startup.

<h4><b>Escolha o .NET para aplicativos de nuvem e de IA</b></h4>
O SDK do Azure para .NET permite que os desenvolvedores provisionem e gerenciem recursos do Azure. Como alternativa, o Serviço de Aplicativo do Azure e o Azure Functions podem hospedar aplicativos criados usando linguagens .NET.

O ML.NET é uma biblioteca de aprendizado de máquina gratuita para linguagens .NET. Ele habilita recursos baseados em modelo para análise e previsão de aprendizado de máquina.

<h4><b>Escolha o .NET para criar aplicativos de IoT</b></h4>
Você pode usar o .NET para criar aplicativos de IoT para dispositivos e cenários de IoT. Os aplicativos de IoT geralmente interagem com sensores, telas e dispositivos de entrada que exigem o uso de pinos GPIO (entrada/saída para uso geral), portas seriais ou hardware semelhante. Por exemplo, você pode encontrar bibliotecas que funcionam com painéis populares, como Raspberry Pi e HummingBoard.
 
 
 
