# Implementación de chats de mensajería instantánea

### Chat-P2P

Implementación de una aplicación de mensajería Peer to Peer (P2P). Para iniciar una conversación con un usuario determinado se debe ingresar el _nickname_ del mismo. 

Se implementó un canal de multritransmición de manera tal que cuando un usuario quiera comunicarse con otro, se enviará un mensaje de consulta a través del canal multicast con el nombre del usuario con el que quiere iniciar una sesión de chat. El usuario que tenga ese nickname responderá por ese mismo canal multicast con su direccipon IP y puerto al que está conectado escuchando. El otro usuario, que se quedá escuchando el canal recibe la dirección IP y el puerto e inicia una sesión para tener una comuniación privada con este. 





