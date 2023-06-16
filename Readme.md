# Entrega prática de prog prova 2
## Arquivos 
### Image_publisher 
- Este arquivo faz a publicação dos frames do video que foi passado no tópico em um periodo de tempo utilizando o timer e através de uma função de callback ele faz a leitura desses frames e informar o envio pelo getlogger
#### Image_subscriber
- Este arquivo faz a leituras so frames enviados pelo image_publisher no tópico aplicando o modelo treinado para identificar rostos do YOLO V8 através da sua função de callback e devolvendo um video de saida com a identificação aplicada. 
## Video funcionando
![Alt text](assets/praticap2.gif)