# 🚧 ARDUINO/ESP COMECE POR AQUI 🚧

Então, pessoal, se você chegou até aqui, provavelmente viu alguma placa, alguém utilizando ou ouviu falar sobre o Arduino/Esp em algum lugar, em algum momento. Eu mesmo só fui conhecer quando entrei no ensino médio, porém sem ter conhecimento algum de elétrica, robótica e áreas afins... assim entrei nesse mundo.
Não preciso dizer se gostei ou se aprendi alguma coisa; conheci a plataforma em 2018 e hoje (atualmente em 2024) estou criando um repositório para vocês, totalmente público, totalmente livre e acessível.

SEM MAIS DELONGAS, LET'S GO! (VAMOS LÁ!)

* QUAL O OBJETIVO DO REPOSITÓRIO: O repositório é destinado as pessoas que nunca tiveram contato com essa </br> plataforma (ARDUINO, ESP) ou que queiram reforçar os conhecimentos iniciais. De início, o entendimento de ESP e ARDUINO é igual (conhecimentos avançados em breve aqui nesses outros repositórios: [TECNICAS_AVANCADAS_COM_ESP](https://github.com/well1ngt0nso/arduino_comece_aqui?tab=readme-ov-file#ok-mas-o-que-posso-fazer-com-isso) e [TECNICAS_AVANCADAS_COM_ARDUINO](https://pages.github.com/))

* REQUISITOS: NENHUM! Conhecimentos iniciais de eletrônica, elétrica no geral ajudariam, mas faremos voltado para quem conhece pouco ou nada. Para você que já conhece em um nível maior, basta pular as pequenas explicações

* SUPORTE: Sempre que possível estarei respondendo aqui na comunidade

* PRECISO COMPRAR UMA PLACA: Se poder adquirir é interessante, mas a maior parte pode ser feita em simulador (terá uma aula só para isso)

* COMO SE DARÁ OS ESTUDOS: A medida que o tempo passa eu vou publicando as aulas, pode ser que você chegue agora e só tenha duas aulas e um projeto, enquanto outra pessoa pode chegar mais tarde e já encontrar 30 aulas e 10 projetos

* TERÁ SÓ CÓDIGOS?: NÃO! Gosto de visualizar as coisas, dissecar o entendimento, então vai ter comentários, imagens, tabelas, vídeos, os arquivos usados na explicação e etc, o objetivo é descomplicar

_**⚠️OBS:**_
Todas as "aulas" são numeradas em sequência de estudo no final desse arquivo, por exemplo: "#AULA 1 - INTRODUÇÃO_ONDE_ENTRA_A_PLACA_NO_PROJETO",  #"AULA 2 - CONHECENDO A PLACA".... estarei separando em pastas

# O QUE É UM ESP? O QUE É UM ARDUINO?🤔
Ambas são placas baseadas em microcontroladores (chips),de início tenha um microcontrolador como um dispositivo de controle, ou seja, essas placas eletrônicas possibilitam a criação, desenvolvimento, a implementação de uma ampla variadade de projetos, ideias desde os mais simples até os mais avançados, desde projetos para seu próprio uso como também projetos para uso comercial, por exemplo uma ideia que você desenvolveu e que decidiu vender, é totalmente possível, acessível e barato
Usar essas placas é colocar a ideia em prática, seja uma ideia que antes não era possível devido a complexibilidade de montar todo um circuito eletrônico ou devido ao preço de dispositivos um pouco semelhantes no mercado antes do desenvolvimento desses microcontroladores 

## OK, MAS O QUE POSSO FAZER COM ISSO?
Acionamento e Controle de: Lâmpadas, Motores, Leds, Relés, Displays (e muito, mas muito mais coisas)... 
Envio e Recebimento de dados: Comunicação com telas para visualização de dados, monitoramento de sensores (temperatura, umidade, pressão, velocidade....), comunicação coom outras placas, 
Comunicação com telefone, comunicação com a internet...
Palavras chaves: Controlar dispositivos, processar dados, enviar dados, coletar dados.


### Alguns poucos exemplos: 

| ATUADORES | SENSORES |
|---|---|
| MOTORES | LUMINOSIDADE |
| LÂMPADAS | GÁS |
| VÁLVULAS | PRESSÃO |
| LASERS | NÍVEL |
| ALTOFALANTES | UMIDADE |
| DISPLAYS | TOQUE |
| TRANSMISSORES | RECEPTORES |
| WIFI | DISTÂNCIA |



O MAIS IMPORTANTE É QUE A IDEIA NÃO PRECISA SER RESTRITA A ÁREA ELETRÔNICA, VOCÊ PODE FAZER ALGO PARA UMA ESCOLA, ALGO PARA UMA PADARIA, ALGO PARA UM SALÃO DE BELEZA, ALGO PARA UMA BARBEARIA, ALGO PARA SEU QUARTO, ALGO PARA A EMPRESA ONDE TRABALHA.... SÃO MUITAS AS APLICAÇOES E ÁREAS DE INCORPORAÇÃO

Já adianto que a partir do momento que começamos a desenvolver, qualquer ideia que apareça nos pensmentos vai fazer você querer usar uma dessas placas hehe😅 

## VARIANTES:
Existem vários modelos, várias variantes de ESP e ARDUÍNO no mercado, cada um com suas características, bastando a você escolher a melhor opção, abaixo listo alguns modelos, MAS NÃO SE PREOCUPE, ABORDAREMOS DETALHES DE CADA UM AO PASSAR DAS AULAS, O INTUITO É APENAS MOSTRAR QUE EXISTE, ALGO VISUAL...

### ESSE É O ARDUINO UNO:
<p align="center">
  <img src="https://github.com/well1ngt0nso/arduino_comece_aqui/assets/58373332/c2575ef1-14e5-493f-ad2e-eac07ca04e20" alt="Descrição da imagem" width="50%" />
</p>

### ESSE É O ARDUINO MEGA:
<p align="center">
  <img src="https://github.com/well1ngt0nso/arduino_comece_aqui/assets/58373332/2b0b2fdb-f39a-4904-923b-6c695f13bb8b" alt="Descrição da imagem" width="50%" />
</p>

### ESSE É O ESP32 WROOM-32:
<p align="center">
  <img src="https://github.com/well1ngt0nso/arduino_comece_aqui/assets/58373332/0a4bf166-60a1-48f9-8166-6e92b2081d2a" alt="Descrição da imagem" width="50%" />
</p>

### ESSE É O ESP 8266MOD:
<p align="center">
  <img src="https://github.com/well1ngt0nso/arduino_comece_aqui/assets/58373332/f58282cf-cd18-44e2-ab30-0ae419b3fadb" width="50%" />
</p>

Como citei, são muitos os modelos, bastando ver qual é mais apropriado para a ideia:

* Baixo custo?</br>
* Tamanho pequeno?</br>
* Alta velocidade de processsamento?</br>
* Conexão wifi?</br>
* Conexão Bluethohft?</br>
* Número de pinos?</br>
* Conector de comunicação USB-C, USB-B..?</br>
* Com tela? </br>
* São muitas as características e que pretendo analisar cada uma com vocês...

Sem mais atrasos, vamos para a primeira aula "#AULA 1 - INTRODUÇÃO_ONDE_ENTRA_A_PLACA_NO_PROJETO"

## LISTA DE AULAS EM SEQUÊNCIA 

