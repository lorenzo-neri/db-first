<!-- 
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario
-->

# First DB Template
Boolean Class 104 exercise

## Table Name
Used Cars

## Table Columns

id | PRIMARY_KEY, INT, UNIQUE, AUTO_INCREMENT, NOT NULL

Company | VARCHAR(24), NOTNULL //Volkswagen Aktiengesellschaft

Model | VARCHAR(50), NOTNULL 

Fuel | VARCHAR(10), NOTNULL 

Transmission | VARCHAR(10), 

Horse_power | SMALLINT, NULL 

Km | MEDIUMINT, NULL //150.000km

Year | YEAR, NULL

Status | VARCHAR(20), NULL 

Color | VARCHAR(10), NULL

Description | TEXT, NULL

Notes | VARCHAR(255), NULL

Price | DECIMAL(6, 2), NULL //120.000,90 €