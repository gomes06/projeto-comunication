# projeto-comunication
Desenvolvimento de um projeto de comunicação client-server simulada em linguagem C;
Este projeto simula três elementos: um sensor genérico, um computador central e uma interface com o usuário, para monitoramento da condição da bateria do sensor;
O sensor assume a característica única de servidor que alimenta o cliente Computador central com dados sobre conexão e nível da bateria;
A interface do usuário tem a função de cliente em relaçao ao servidor Computador central, sendo alimentada pelo mesmo com dados processados sobre a condição genérica da bateria do sensor;
O computador central possui personalidade híbrida, pois recebe dados como cliente do servidor Sensor, processa-os e alimenta o cliente Interface do usuário.

# Modo de execução
Este projeto foi desenvolvido baseado em bibliotecas Linux, portanto é incompatível com qualquer outro sistema operacional;
Após a compilação de cada arquivo, a execução deve ser iniciada pelo SENSOR, logo após o COMPUTADOR CENTRAL e, por fim, a interface de usuário;
Esta, por sua vez, deve ser executada da seguinte forma: 
    *supondo que o nome escolhido na compilação foi 'user_interface'...*
    ./user_interface CICLO-DE-TEMPO LIMITE-BATERIA
