# Pròsopon

![GitHub](https://img.shields.io/github/license/ouitoulia/prosopon?style=for-the-badge)
![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/ouitoulia/prosopon?sort=semver&style=for-the-badge)
![Packagist Dependency Version](https://img.shields.io/packagist/dependency-v/ouitoulia/prosopon/drupal/core-recommended?style=for-the-badge)
![Packagist Downloads](https://img.shields.io/packagist/dt/ouitoulia/prosopon?style=for-the-badge)

[Pròsopon](https://www.grecoantico.com/dizionario-greco-antico.php?parola=proswpon) è un modulo Drupal che gestisce gli utenti.

## Requisiti
- Drupal: >= 10
- Profilo Drupal: `minimal`
- Moduli Drupal: `user`, `path`

## Installazione
Per aggiungere il modulo alla tua installazione esegui:
```bash
$ composer require ouitoulia/prosopon
$ drush -y pm:install prosopon
```
Le dipendenze verranno installate automaticamente.

## Implementazione tipo Persona
| Architettura           | Implementazione      | Note                                                                                                                                                                    |
|------------------------|----------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Campi dell'entity user |                      | Riuso dei campi `entity:user`                                                                                                                                           |
| Codice fiscale         | field_codice_fiscale | **Campo aggiunto rispetto all'architettura** Necessario per collegare al tipo di contenuto `Persona` l'eventuale utente registrato e/o che fa login da un servizio SSO. |


## License

Copyright (C) 2023 https://github.com/ouitoulia

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 3 as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

Questo è un software libero: puoi ridistribuirlo e/o modificarlo secondo i termini della GNU General Public License versione 3 pubblicata dalla Free Software Foundation.

Questo programma è distribuito nella speranza che possa essere utile, ma SENZA ALCUNA GARANZIA; senza nemmeno la garanzia implicita di COMMERCIABILITÀ o IDONEITÀ PER UNO SCOPO PARTICOLARE. Vedere la GNU General Public License per maggiori dettagli.