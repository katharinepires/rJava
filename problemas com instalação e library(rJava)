# rJava
#Problemas com instalação e library(rJava) do pacote rJava 
#mensagem: "erro: JAVA_HOME cannot be determined from the Registry"
#mensagem: "erro: impossível carregar objeto compartilhamento 'C:/Users/Katharine/Documents/R/win-library/4.0/rJava/libs/x64/rJava.dll':"
#é necessário já ter instalado o Java Runtime e o JDK
#agora é só seguir os passos abaixo: 

> install.packages("rJava")
# será exibidada essa mensagem: <package ‘rJava’ successfully unpacked and MD5 sums checked

The downloaded binary packages are in
        C:\Users\Katharine\AppData\Local\Temp\RtmpKQJByy\downloaded_packages>
 
#para windows 10: procure por Variaveis de Ambiente -> Variaveis do Sistema e clica em "Novo"
#Nome da Variavel: JAVA_HOME and Valor da Variavel: C:\Program Files\Java\jre1.8.0_251
#agora é só seguir os comandos abaixo:

> Sys.setenv(JAVA_HOME="C:/Program Files/Java/jdk-14.0.1")
> library(rJava)
