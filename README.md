# Ubuntu_Hadoop_Pig_With_Interfaces

Pig e Hadoop sono stati eseguiti all’interno di un container Docker. L’immagine manudf/ubuntu_pig contiene al suo interno l’installazione di pig-0.17.0 che esegue a sua volta su hadoop-2.10.0 (immagine rebdiluca/ubuntu_hadoop). 
Per impostare l’ambiente basta eseguire il comando ‘docker-compose up -d’.
Per accedere alla bash all’interno del container bisogna eseguire il comando ‘docker exec -it ubuntu_pig_UbuntuBigData_1 /bin/bash’
Al primo avvio del container, bisogna eseguire lo script start.sh per avviare il servizio ssh.

Link docker hub manudf/ubuntu_pig: https://hub.docker.com/r/manudf/ubuntu_pig
Link docker hub rebdiluca/ubuntu_hadoop: https://hub.docker.com/r/rebdiluca/ubuntu_hadoop

Link github per il dockerfile di ubuntu_pig: https://github.com/emdifiore22/Ubuntu_Hadoop_Pig.git 
Link github per il dockerfile di ubuntu_hadoop: https://github.com/emdifiore22/Ubuntu_Hadoop.git 
Link github per il docker-compose.yml: https://github.com/emdifiore22/Ubuntu_Hadoop_Pig_With_Interfaces.git