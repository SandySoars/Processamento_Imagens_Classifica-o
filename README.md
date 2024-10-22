Descrição do Projeto:
O projeto consiste em treinar um modelo de machine learning para classificação de objetos utilizando a plataforma Teachable Machine. O modelo será treinado com 5 diferentes classes de objetos, e, após o treinamento, será exportado no formato labes.Txt e keras.model.h5 para uso em um código Python. No ambiente Python, o modelo será aplicado para classificar os 5 objetos que aprecerão na filmagem e, em seguida, será realizada a verificação da acurácia, comparando as previsões feitas com as classes reais dos objetos. O objetivo final é avaliar o desempenho do modelo, calculando o percentual de acertos das classificações.
Instruções de Innstalação:
Após o treinamento do modelo no Teachable Machine, exporte os arquivos labels.txt e keras_model.h5, que contêm, respectivamente, os rótulos das classes e o modelo treinado. Esses arquivos devem ser salvos na mesma pasta onde estará o código Python que será usado para carregar o modelo e realizar a classificação de objetos. Certifique-se de que ambos os arquivos estejam no mesmo diretório que o código, para garantir que o Python possa acessá-los corretamente durante a execução.
Instruções de Uso:
O código incluído no repositório utiliza a Iriun Webcam como fonte de vídeo, que transforma o celular em uma webcam. Para usar, basta instalar o aplicativo Iriun no celular e no computador, conectá-los na mesma rede Wi-Fi ou via cabo USB, e então executar o código Python. O código carregará automaticamente o modelo treinado (keras_model.h5) e usará a câmera para capturar imagens em tempo real e classificá-las. Foram criadas 5 classes de objeto: calculadora, caneta, mouse, prato e bloco de notas.
Caso você queira utilizar uma webcam diferente, como a do seu laptop ou outra câmera externa, será necessário alterar o índice da câmera no código Python. Normalmente, o índice 0 é para a webcam padrão do laptop, e 1, 2, etc., são para câmeras externas. Você pode ajustar essa numeração no método cv2.VideoCapture(), alterando o número conforme a câmera que deseja usar.
Créditos:
Edilson Souza da Silva 
Nicole Souza da Silva
Sandyella Silva Soares
Atividade realizada pelos alunos graduandos do curso de Sistemas de Informação da UFOPA- Oriximiná na disciplina de Processamento de Imagens com o docente Danilo Azevedo no Laboratório de Informatica 02 da universidade.
