# Libras Detection :hand: :call_me_hand:

## Sobre o projeto
O Libras Project utilizará uma rede neural para traduzir as libras apresentadas em tempo real, visando para pessoas aprenderem a fazer e reconhecer libras. <br>
A IA foi treinada do zero por nós, desde as fotos (as quais usamos para aplicar o Euclidian e gerar o Dataset a partir do valor gerado pelo modelo matemático), até seu treinamento. Utilizamos apenas uma função pronta do mediapipe a qual cria um esqueleto quando uma mão é detectada, neste esqueleto possui pontos (os quais seriam articulações das mãos (que serão utilizados na aplicação do Euclidian))

#### Como funciona      
Através de uma câmera, o usuário fará a letra em libras com a mão, em que deseja que a IA identifique. <br>
A partir da letra em libras feito na câmera, a IA irá aplicar o que foi feito em seu treinamento e através das distâncias dos pontos (o ponto central (palma da mão) com as extremidades de cada dedo (a ponta dos dedos)) irá retornar a letra que ela reconheceu e o usuário irá perceber se a letra que o mesmo está fazendo corresponde ao que ele queria.

<hr>  
      
## Tecnologias utilizadas 
##### :snake: Python
<hr>  


## Objetivos
### IA
- [X] criação de DataSet
- [X] Aplicação de modelo matemático
- [X] Estudo dos dados
- [X] Treino e salvamento
- [X] Diferenciar letras a partir do modelo matemático
- [X] Printar na tela a letra detectada
- [ ] Acréscimo de frases

### Webserver
- [ ] Execução da Rede Neural


## Parte executada/feita por mim
- [X] Criação das imagens
- [X] Aplicação do modelo matemático(Euclidian)
- [X] Criação do Dataset
- [X] Mostrar na tela letra identificada


## Próximos objetivos
- [ ] Treinar a IA para detectar frases

## Autores
- Victor Matheus Silva Lima
- Higor Frade
- Jose Siqueira

## Orientador e Professor
Vandeir Aniceto Pinheiro @ UNIFAJ
