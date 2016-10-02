# javaelekter

Laeb alla homse tunnipõhise elektri hinna.
Arvestades homset elektrihinda lülitab tarbijaid sisse välja siis kui on odavaim.
Lisa1: saadab kasutajale SMS-si emaili kui otustesse tuleks sekkuda.
Lisa2: kasutaja saab üle veebi teha manuaalset sisse/välja lülitamist.

1. leida moodus kuidas lugeda andmeid nt csv formaadist.
Andmed hinna kohta saab:
http://www.nordpoolspot.com/api/marketdata/page/47
http://www.nordpoolspot.com/Market-data1/Elspot/Area-Prices/EE/Hourly/?view=table

2. andemete põhjal ning max hinna alusel leida millal elektrit tarbida.

weekly 1 kommentaarid:
Kompileerimise käsud.
javac main.java
java -cp . main
