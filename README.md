after watched the teaching vedio by shunping han, i tried to writethis a im program writen using  java  language;

it uses c-s architecture:
in the server end ,it connects the sql-server;
in the  client  end ,it can send message transfered by the server with each other;

the message data structure is object ,which is serialized to flow  to the network;


overview function:

user can send message to other ;
user can receive offline message ;
user can get the  notification by the glint of words int thr sender when message comes ;


future work :

add:

multi-user chat like group chat;
message notification by shaking or audio;
user can send picture ,file;

link the im to the website like qq_zone


optimization:

optimize the socket in server end using nio(may be this ^_^) to support igh concurrent ;
redesign all the datebase tables; 


