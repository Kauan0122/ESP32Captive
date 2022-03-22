## Disclamer
O uso indevido deste software pode resultar em atividades criminosas. O (s) autor (es) não serão responsabilizados por seu uso abusivo.

## Funções
Um portal cativo capaz de interceptar pesquisas de DNS e fornecer uma interface de login de acordo com a URL. Atualmente, ele implementa as máscaras de login do Google, Facebook, mas pode ser estendido. O modelo de login do Google é o padrão. <br>
Quando o usuário se conecta pela primeira vez de um smartphone, surge um portal de login solicitando a realização do login para iniciar a navegação e, após o envio dos dados, é recuperado um erro. <br>
Os dados de login são armazenados na memória flash do ESP32 e podem ser vistos em anydomain.com/logs <br>
O LED embutido piscará 10 vezes para confirmar a inicialização bem-sucedida e 5 vezes quando um usuário fizer login.

## Uso
Simplesmente instale o sketch usando o Arduino IDE em uma placa compatível com ESP32, use a configuração SPIFFS correta e o pino do LED. Nenhum hardware extra é necessário. <br>
Você pode configurar um portal catch all captive mais três sites únicos para hackear, de forma que, se o usuário acessar o site, uma página falsa seja apresentada para a coleta de credenciais. No ficheiro principal encontram-se todas as configurações, nomeadamente o SSID público WiFi e a página do portal cativo.


## Créditos
Baseado no * projeto ESPortal * de Corey Harding www.legacysecuritygroup.com <br>
