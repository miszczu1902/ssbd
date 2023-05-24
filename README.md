Aby uruchomić projekt należy uruchomić plik docker-compose.yml w katalogu w src/test/resources/docker.

Najpierw trzeba zainstalować maven. Następnie w katalogu główwnym projektu uruchomić w terminalu polecenie mvn clean package -DskipTests=true. W katalogu target będziemy mieć plik o rozszerzeniu .war.

Następnie w przeglądarkę wpisujemy localhost:4848. Może być problem z certyfikatem ale należy zaakceptować.

W login i hasło wpsiujemy: admin/admin

Następnie wchodzimy w Applications:
![image](https://github.com/BartekGit1/ssbd/assets/85065893/c81eedef-3908-48a4-bf4d-b9a2241367e7)

Potem deploy:
![image](https://github.com/BartekGit1/ssbd/assets/85065893/86957181-23e2-4510-b7f8-7a162bc55881)

I wrzucamy wara.
![image](https://github.com/BartekGit1/ssbd/assets/85065893/ba5ec9c4-33eb-433c-8c8e-e6d3897d33c0)


Jak się wszysko uda to w sekcji Applications będzie wdrożona aplikacja:
![image](https://github.com/BartekGit1/ssbd/assets/85065893/57dafa5a-f518-4bf3-9509-9c14bfb87e69)

