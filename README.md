# Graalvm - Projeto Spring Native

Instale a maquina virtual JAVA com Graalvm na sua maquina e o docker.
Verifique que o docker está ativo na sua maquina.

No terminal rode o comando
mvn -Pnative native:compile

Ao finalizar as 8 etapas, verifique se na pasta target gerou um arquivo chamado
graalvm-demo

e execute o projeto com
./target/graalvm-demo
