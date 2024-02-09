<h1 align="center">Modelo OSI</h1>
<h2 align="center">O que é uma rede?</h2>
Uma rede é um grupo de dois ou mais dispositivos conectados. 

Sub-redes: Uma sub-rede é uma grande rede dividida em partes menores, o que facilita o controle e a organização das informações que circulam pela rede.

Internet (rede de redes) os computadores estão conectados uns aos outros dentro de redes e essas redes se conectam a outras redes. Isso permite que esses computadores se conectem a outros computadores próximos e distantes.

<h2 align="center">O que é uma camada de rede?</h2> 
 A “camada de rede” é a parte do processo de comunicação da internet no qual as conexões ocorrem, enviando pacotes de dados entre diferentes redes.
 
Exemplo: suponha que duas pessoas estão conectadas à mesma rede local e uma queira enviar uma mensagem para a outra. Se estiverem na mesma rede, a mensagem pode ser enviada diretamente da rede para o computador. No entanto, se a pessoa estiver a vários quilômetros de distância, a mensagem terá que ser endereçada e enviada à rede da outra pessoa antes de chegar ao computador dela, que é um processo da camada de rede.

<h2 align="center">O que acontece na camada de rede?</h2>
Qualquer coisa que tenha a ver com conexões entre redes ocorre na camada de rede. 

Exemplo: configurar as rotas que os pacotes de dados vão seguir, verificar se um servidor em outra rede está funcionando e endereçar e receber pacotes de IP de outras redes. Este último processo é talvez o mais importante, já que a grande maioria do tráfego da internet é enviada por IP.

<h2 align="center">O que é um pacote?</h2>
Todos os dados enviados pela internet são divididos em pedaços menores chamados "pacotes". 

Exemplo: Quando uma pessoa envia uma mensagem para outra, a mensagem é dividida em pedaços menores e depois remontada no computador do remetente
Na camada de rede, o software de rede anexa um cabeçalho a cada pacote quando ele é enviado pela internet e, na outra extremidade, o software de rede pode usar o cabeçalho para entender como lidar com o pacote.

Um cabeçalho contém informações sobre o conteúdo, origem e destino de cada pacote (algo como carimbar um envelope com um destino e endereço de retorno). 

Exemplo: um cabeçalho IP contém o destino (endereço IP) de cada pacote, o tamanho total do pacote, uma indicação se o pacote foi fragmentado ou não (dividido em pedaços ainda menores), e uma contagem de por quantas redes o pacote viajou.
