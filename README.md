# Progetto Finale - Epicode - Lorenzo Sijinardi

[![Test status](https://github.com/PHPMailer/PHPMailer/workflows/Tests/badge.svg)](https://github.com/PHPMailer/PHPMailer/actions)
[![Latest Stable Version](https://poser.pugx.org/phpmailer/phpmailer/v/stable.svg)](https://packagist.org/packages/phpmailer/phpmailer)
[![API Docs](https://github.com/phpmailer/phpmailer/workflows/Docs/badge.svg)](https://phpmailer.github.io/PHPMailer/)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/PHPMailer/PHPMailer/badge)](https://api.securityscorecards.dev/projects/github.com/PHPMailer/PHPMailer)

## Sommario

- In questa repository è presente l'insieme delle pagine necessarie alla creazione di una dashboard per un CRM dove l'amministratore può disporre di varie dashboards per avere sempre sott'occhio la situazione del sistema.
- Il progetto è live anche seguendo il link  >> https://bit.ly/capstone-hp <<
- Il sistema di gestione ticket prevede una landing con 3 smistamenti principali: un primo per inviare un ticket di richiesta assitenza, un secondo per operatori ed admin ed un terzo per ricercare un ticket inviato avendo numero di ticket ed email.
- Accedendo come operatore (credenziali fornite in HP) si avrà accesso a tutti i ticket assegnati dall'Admin per il quale occorre dare assistenza;
- Accedendo come Admin (credenziali fornite in HP) si avrà accesso a tutti i ticket ricevuti, chiusi o lavorati .

## Tecnologie usate

```
* Bootstrap
* Chart.js
* Dashboard.js
* Workbench
```


## Funzionalità

```
* Invio ticket con generazione codice univoco progressivo
* Pagina di log in identica per Operatori ed Admin ma all'invio del login si verrà reindirizzati in base al proprio ruolo con i privilegi corrispondenti
* Assegnazione ticket all'operatore discriminando competenze, ruoli e privilegi
* Gestione ticket con invio automatico di mail al cliente
* Esportazione liste ticket in formati pdf, excel, word, csv e json filtrabili per numero ticket, operatore, stato del ticket, data, topic


```
