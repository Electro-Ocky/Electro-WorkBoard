# Electro-WorkBoard

Uma bancada de eletrônica portátil.

**Descrição**

Ele é um bracelete/caixa pequena, com sensores e emissores, em escala micro, que possuem condutores retráteis(Bastões retráteis moles) para amplificar seu poder, de elétrica, luz, radiofrequência.

Ele pode possui um sistema operacional comum, como um criado para ele, nas versões que usam RPI Pico/ Arduino, ou para Raspberry Pi Raspbian Lite, ou Arch Linux, com configurações básicas para fornecer gráficos simples, como função de osciloscópio. 

**Fotos/Vídeos de Inspiração/demonstração**

[Incrivel substitui 3 aparelhos e preço de 1! (Multímetro + Osciloscópio + Gerador ) Mustcool MDS9208](https://www.youtube.com/watch?v=nVxdAXNXWJQ)

[ReTrak by Emerge Technologies](https://www.youtube.com/watch?v=upeoTtmaWG0&pp=ygUPY2FibGUgcmV0cmFjdG9y)

[1pc Ponteiro Retrátil Vara De Leitura De Dedo Para Leitura, Bastão De Dedo Retrátil Auxiliar De Ensino, Bastão De Condutor Especial Do Professor Caneta De Leitura Quadro Negro Guia De Piano Leitura Bastão De Casa](https://www.google.com/url?sa=i&url=https://www.temu.com/pt/1pc-ponteiro-retr%C3%A1til-vara-de-leitura-de-dedo-para-leitura-bast%C3%A3o-de-dedo-retr%C3%A1til-auxiliar-de-ensino-bast%C3%A3o-de-condutor-especial-do-professor-caneta-de-leitura-quadro--guia-de-piano-leitura-bast%C3%A3o-de-casa-g-601099525030708.html&psig=AOvVaw1_tmeFzJVWoP1OBSuDNPWd&ust=1704937966675000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCIip7-3b0YMDFQAAAAAdAAAAABAD)

[Raspberry Pi RP2040 Pip-Boy is Apocalypse Ready](https://www.tomshardware.com/news/raspberry-pi-rp2040-pip-boy)

**Perguntas frequentes**

- Como isso é economicamente viável?
    - Os sensores utilizados podem ser fabricados facilmente, reciclados, e custam alguns centavos para serem comprados…
    - Ao todo se gastaria cerca de 1.000 R$ no projeto para se construir, e se poderia reutilizar as partes em várias coisas, como por exemplo a tela dele.
    - Com um pouco de engenharia simples, você pode criar sistemas como um micro sensor infravermelho, com uma antena de fibra ótica.
- Vocês vendem?
    - Com a versão 3.0.0 sendo lançada, e o projeto dando certo e sendo financiado, trabalharíamos em uma versão para se vender, com PCB e impressões 3D de qualidade e baixo custo. Talvez consigamos um investimento pela comunidade DIY e Open Source, Raspberry, Ubuntu entre outros... Também lançaríamos um financiamento coletivo para publicar isso, mas precisaríamos de engenheiros, marketeiros e designers.
    - Mas não, esse não é nosso objetivo, e sim criar um dispositivo DIY.
- Como tantos sensores serão colocados na GPIO?
    - Usamos CI que a partir de um único pino dão o efeito desejado de acordo com a intenção dele. Mandamos um código de 01234 e ativa o CI infravermelho de um jeito, enviamos 04321 e ativa o sensor de osciloscópio.

**Expansões e módulos**

Há várias expansões do projeto:

- Software - FlipperBoy, que adiciona ferramentas/API/Softwares hackers a ele, inspirado pelo dispositivo Flipper, e PipBoy(item do jogo Fallout).
- Modelo - RPG SmartchWatch, tem adaptações para ser um bracelete; adiciona monitoramentos informativo sobre os vitais do indivíduo e seus itens (batimentos cardíacos, mapa/localização, passos, velocidade, tamanho de pulo, lista de tarefas, diários, inventário pessoal, e próximo, estado dos itens do inventário, temperatura, radar).
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
