## Zadanie2
---
### Część obowiązkowa

Proszę uruchomić przygotowaną aplikację na platformie AWS, usługa EBS. W tym celu należy wykorzystać przykład przedstawiony na laboratorium nr 3 (pliki: Lab3_AWS.pdf oraz Lab3_AWS_sources.zip). 

Link do aplikacji na AWS: http://zadanie2zadrag-env.eba-jmgt2mw5.eu-central-1.elasticbeanstalk.com/ <br>
Link do konsoli: https://eu-central-1.console.aws.amazon.com/elasticbeanstalk/home?region=eu-central-1#/welcome <br>
Link do repozytorium DockerHub: https://hub.docker.com/repository/docker/michalzadrag/fullstack-zad2

#### Wykonanie krok po kroku
1. Założyć konto na https://www.travis-ci.com/
2. Założyć konto na AWS
3. Założyć S3 oraz Elastic Beanstalk na AWS
4. Dodaj usera poprzez IAM na AWS
5. Uzyskane tokeny zapisz i dodaj jako secrety na konkretnym repozytorium w Travisie i Githubie
6. Dodaj folder .github/workflows oraz plik yml z konfiguracją Github Actions
7. Dodaj plik travis.yml z konfiguracją Travisa

**Ważne:** Gdy skonfigurwane jest zarówno Github Actions i Travis. Jedno z tych rozwiązań nie zdeployuje aplikacji ponieważ niemożliwy jest równoczesny deploy

![image](https://user-images.githubusercontent.com/52106343/172451500-e0aadd54-febd-49b4-b5e3-6324b655ffb7.png)

![image](https://user-images.githubusercontent.com/52106343/172451802-744dd551-0e5f-4fa8-b4b1-270695770b8c.png)

![image](https://user-images.githubusercontent.com/52106343/172451927-b616beb4-a2fa-47ff-9f1e-2165d72aee27.png)

![image](https://user-images.githubusercontent.com/52106343/172451993-6501bd89-0750-46da-ba09-2fdfd902e618.png)

### Część dodatkowa

Zadanie w tej części polega na rozbudowaniu pliku wdrożenia w GitHub Action. W ramach tego rozszerzenia: 
- a) GitHub Ations ma zbudować obraz aplikacji i przesłać go na repozytorium DockerHub. Proszę w tym celu wykorzystać wiedzę i konfigurację przygotowaną w ramach zadania nr 1. 

W celu wykonania tego zadania należało zmodyfikować plik yml w katalogu .github/workflows dodając do niego znane już predefiniowany actiony. Dodatkowo należy pamiętać o zdefiniowaniu sekretów

![image](https://user-images.githubusercontent.com/52106343/172452875-7d4e51b8-659c-46d4-9caa-bf5d268dcc22.png)

![image](https://user-images.githubusercontent.com/52106343/172452962-aeb43adc-d72f-45f2-a730-0950d61b01de.png)

**Link do repozytorium DockerHub znajduje się w części obowiązkowej**
