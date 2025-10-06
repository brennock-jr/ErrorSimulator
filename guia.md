#Guia de Uso
Caso não tenha javafx em seu computador [aprenda a instalar neste link](https://dev.java/learn/javafx/install/)

1 - Baixe o arquivo Jar.

2 - Abra o terminal de sua distribuição (Powershell para Windows, Terminal para Linux) e navegue até a localização do arquivo jar.

3 - Insira o comando segundo a sua distribuição

	Windows:
 
java --module-path "C:\caminho\ate\javasdk\lib" ^ --add-modules javafx.controls,javafx.fxml ^ -jar ErrorSimulator0.1.jar

	Linux:

java --module-path ~/caminho/javasdl/lib \ --add-modules javafx.controls,javafx.fxml \ -jar ErrorSimulator0.1.jar

