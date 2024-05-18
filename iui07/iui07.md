## Praktyczne zastosowanie usług w Chmurze (cz. 1)
Praktyczne zastosowanie usług w Chmurze na przykładzie Azure AI Health Bot

## Azure AI Health Bot
https://learn.microsoft.com/en-us/azure/health-bot/quickstart-createyourfirstscenario

## Enable communication using the Direct Line channel
https://learn.microsoft.com/en-us/azure/health-bot/channels/directline

## Authentication in Direct Line API 3.0
https://learn.microsoft.com/en-us/azure/bot-service/rest-api/bot-framework-rest-direct-line-3-0-authentication?view=azure-bot-service-4.0

### Stwórz Azure Health Bot (krok 1) 
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/1_hbot_create.jpg "Obraz")

### Stwórz Azure Health Bot (krok 2)
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/2_hbot_create2.jpg "Obraz")

### Azure Health Bot uruchomiony
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/3_hbot_deployed.jpg "Obraz")

### Health Bot Portal - zarządzanie scenariuszami
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/4_hbot_portal.jpg "Obraz")

### Dodaj nowy scenariusz
* Name: Hello world
* Scenario ID: hello
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/5_hbot_new_scenario.jpg "Obraz")

### Scenariusz "hello" stworzony
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/6_hbot_new_scenario2.jpg "Obraz")

### Dodaj element "Statement" do scenariusza (krok 1)
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/7_hbot_new_scenario3.jpg "Obraz")

### Dodaj element "Statement" do scenariusza (krok 2)
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/8_hbot_scenario_statement.jpg "Obraz")

### Wprowadź dane do elementu "Statement"
* Title: Greeting
* Display text: Hello, World!
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/9_hbot_statement_greetings.jpg "Obraz")

### Gotowy pierwszy element scenariusza
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/10_hbot_statement_greetings2.jpg "Obraz")

### Dodaj drugi element "Yes/No" do scenariusza (krok 1)
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/11_hbot_statement_yes_no.jpg "Obraz")

### Dodaj drugi element "Yes/No" do scenariusza (krok 2)
* Display text: Would you like to see a doctor?
* Input variable: ShouldScheduleDoctor
* Maximum number of retries: 1
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/12_hbot_statement_schedule_prompt.jpg "Obraz")

### Połącz elementy w scenariuszu
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/13_hbot_statement_schedule_prompt2.jpg "Obraz")

### Dodaj kolejne dwa elementy "Statement": "Good bye", "Start Scehdule"
* Połącz z poprzednimi elementami
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/14_hbot_statement_schedule_prompt3.jpg "Obraz")

### Przetestuj Health Bot w Web Chat
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/15_hbot_statement_scenario_run.jpg "Obraz")

### Przypisz scenariusz "hello" jako "Automatic welcome scenario"
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/16_hbot_automatic_scenario.jpg "Obraz")

### Skopiuj "DirectLine secret"
![Obraz](https://github.com/lukpaw/iui-lectures/blob/main/iui07/img/17_hbot_direct_line_secret.jpg "Obraz")

## Praktyczne zastosowanie Health Bot w programie Python
https://github.com/lukpaw/mslearn-ai-language/blob/main/Labfiles/10-health-bot/Python/health-bot/health-bot.py

