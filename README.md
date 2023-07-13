# Lab_7_Devtitans
Laboratório 7: MQTT

Baseado no material de aula sobre MQTT, e considerando o circuito desenvolvido para o laboratório  06, use o protocolo MQTT para que o ESP32 assine um tópico, onde, se a mensagem recebida for "1L" ele ligue o LED1; se for "1D" ele desligue o LED1; se for "2L" ele ligue o LED2; e se for "2D" ele desligue o LED2. Qualquer outra mensagem recebida deve ser só impressa na serial.

Este mesmo ESP32 deve publicar a cada DOIS segundos uma mensagem "Hello World #XXX", onde XXX é um número que é incrementado automaticamente pelo ESP32. 

Para facilitar a correção, por favor mantenha o broker test.mosquitto.org, que está disponível gratuitamente, e foi o o broker utilizado nas aulas. Da mesma forma, mantenha os mesmos tópicos que foram utilizado nas aulas, isto é, "inInTopic" e "outOutTopic".

