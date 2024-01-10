# Electro-WorkBoard

Em termos simples, “Um super multimetro que emite e recebe qualquer sinal, com base na eletricidade”. Uma super ferramenta de trabalho, voltado a eletrônica.

Electro-WorkBoard é uma mesa de trabalho(WorkBench) portátil(Board) para eletrônica. Basicamente um bracelete com um microcontrolador poderoso, que possa processar um compilado de sensores e emissores para medir, alterar, e enviar qualquer sinal elétrico, e através dele, magnéticos, sonoros, radioativos, mecânicos e afins…

Ele conta com medidor de Voltagem, Resistência, Amperes, Frequência, Capacitância, Indutância, 

Um exemplo dele em ação é, você tem três bobinas, um regulador de tensão, ligados separadamente ao microcontrolador central por um CI, você pode combiná-los pelo software, para criar um eletroimã interno, um transformador, ou uma PEM(máquina de pulso eletromagnético), e o raspberry irá unir os componentes de acordo com a sua configuração do software.

Outro exemplo dele em ação é, você tem um circuito completo de transformação de energia com filtro passivo, e pode medir cada componente, como capacitores, Transistores, transformadores, etc… 

O projeto base é baseado em Raspberry Pi. Modelo Electro-Ocky Mark 0.0.0 

**Descrição**

Ele é um bracelete pequeno, com sensores e emissores, em escala micro, que possuem condutores retráteis(Bastões retráteis moles) para amplificar seu poder, de elétrica, luz, radiofrequência.

Ele pode possui um sistema operacional comum, como um Raspbian Lite, ou Arch Linux, com configurações básicas para fornecer gráficos simples, como função de osciloscópio.  

Possui uma PCB simples para juntar todos os sensores e emissores de forma organizada, conectados entre si por CIs especializados, que garantam a flexibilidade interna do sistema.

**Fotos/Vídeos de Inspiração/demonstração**

[Incrivel substitui 3 aparelhos e preço de 1! (Multímetro + Osciloscópio + Gerador ) Mustcool MDS9208](https://www.youtube.com/watch?v=nVxdAXNXWJQ)

[ReTrak by Emerge Technologies](https://www.youtube.com/watch?v=upeoTtmaWG0&pp=ygUPY2FibGUgcmV0cmFjdG9y)

[1pc Ponteiro Retrátil Vara De Leitura De Dedo Para Leitura, Bastão De Dedo Retrátil Auxiliar De Ensino, Bastão De Condutor Especial Do Professor Caneta De Leitura Quadro Negro Guia De Piano Leitura Bastão De Casa](https://www.google.com/url?sa=i&url=https://www.temu.com/pt/1pc-ponteiro-retr%C3%A1til-vara-de-leitura-de-dedo-para-leitura-bast%C3%A3o-de-dedo-retr%C3%A1til-auxiliar-de-ensino-bast%C3%A3o-de-condutor-especial-do-professor-caneta-de-leitura-quadro--guia-de-piano-leitura-bast%C3%A3o-de-casa-g-601099525030708.html&psig=AOvVaw1_tmeFzJVWoP1OBSuDNPWd&ust=1704937966675000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCIip7-3b0YMDFQAAAAAdAAAAABAD)

[Raspberry Pi RP2040 Pip-Boy is Apocalypse Ready](https://www.tomshardware.com/news/raspberry-pi-rp2040-pip-boy)

**Perguntas frequentes**

- Como isso é economicamente viável?
    - Os sensores utilizados podem ser fabricados facilmente, reciclados, e custam alguns centavos para serem comprados…
    - Ao todo se gastaria cerca de 1.000 R$ no projeto para se construir, e se poderia reutilizar as partes em várias coisas, como uma tela HDMI.
    - Com um pouco de engenharia simples, você pode criar sistemas como um micro sensor infravermelho, com uma antena de fibra ótica.
- Vocês vendem?
    - Com a versão 3.0.0 sendo lançada, e o projeto dando certo e sendo financiado, trabalharíamos em uma versão para se vender, com PCB e impressões 3D de qualidade e baixo custo. Talvez consigamos um investimento pela comunidade DIY e Open Source, Raspberry, Ubuntu entre outros... Também lançaríamos um financiamento coletivo para publicar isso, mas precisaríamos de engenheiros, marketeiros e designers.
    - Mas não, esse não é nosso objetivo, e sim criar um dispositivo DIY.
- Como tantos sensores serão colocados na GPIO?
    - Usamos CI que a partir de um único pino dão o efeito desejado de acordo com a intenção dele. Mandamos um código de 01234 e ativa o CI infravermelho de um jeito, enviamos 04321 e ativa o sensor de osciloscópio.

**Expansões e módulos**

Há várias expansões do projeto:

- Software - FlipperBoy, que adiciona ferramentas/API/Softwares hackers a ele, inspirado pelo dispositivo Flipper, e PipBoy(item do jogo Fallout).
- Software - RPG SmartchWatch, adiciona monitoramentos informativo sobre os vitais do indivíduo e seus itens (batimentos cardíacos, mapa/localização, passos, velocidade, tamanho de pulo, lista de tarefas, diários, inventário pessoal, e próximo, estado dos itens do inventário, temperatura, radar).
- Hardware - LeveUp, adiciona mais potêntes/maiores/melhores antenas(condutores de luz, magnetismo, condutores elétricos), baterias externas.
- Modelo - All time, adiciona recursos para tornar possível o uso em várias situações, como maior leveza, recurso aprova de água, materiais resistêntes a temperaturas extremas, isolamento a descargas elétricas.
- E todos podem criar sua própria incrementação do projeto base, de acordo com sua necessidade.

Há também módulos extra(pequenos cubos de bolso):

- Modulo de Temperatura(Gera/Recebe Calor, Frio).
- Módulo Magnético(Gera/Recebe campos eletromagnéticos).
- Módulo Luz(Gera/Recebe Luz).
- Módulo Entradas e Saídas(Gera/Recebe em saídas padronizadas como USB diversos como o USB-C, Lightning, P diversos, como P1 e P2 e P10).

**Nosso sistema de versionamento**

Resumindo: Autor Mark Versão Hardware . Versão Software . Versão Design

Exemplo: Ocky Mark 1.2.3

Cada versão do projeto(modelo) Mark e o número da versão em números com ponto para dividir as seções, num total de 2 secções extra, e Letras começando por B para cada variação. Por exemplo: Mark 1.0.0, Mark 1.0.2B, Mark 2.5F.0C. E podem ter um nome popular. O primeiro número é sobre mudanças no hardware, a segunda no software, a terceira na aparência/desing, e as letras indicam variações do mesmo modelo. Quando alguém diferente dos modelos oficiais cria algo, se coloca o nome artístico do usuário primeiro, como “Ocky Mark 2.0.0B”. O significado do número 0 é para versões caseiras sem acabamento, a 1 é para modelos sólidos e neutros, 2 para inspirações no PipBoy(item do jogo Fallout), 3 para modelos pequenos baseados em SmartchWatchs.

 
**Itens para comprar**

[Raspberry Pi Zero 2 W Anatel - MakerHero](https://www.makerhero.com/produto/raspberry-pi-zero-2-w/?src=raspberrypi)

[Monitor Touch 7 Polegadas Para Raspberry Pi3 E Pi4 1024x600](https://produto.mercadolivre.com.br/MLB-3211483654-monitor-touch-7-polegadas-para-raspberry-pi3-e-pi4-1024x600-_JM)

[Bateria Externa Pineng Power Bank 10000 Mah Slim Preto/verm.](https://www.mercadolivre.com.br/bateria-externa-pineng-power-bank-10000-mah-slim-pretoverm/p/MLB21342307?pdp_filters=item_id:MLB3857169844)
