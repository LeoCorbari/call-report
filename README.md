# 📞 Retro-style Call Report Generator 📊

This is a simple web application that allows users to generate call reports from JSON data. The application features a retro-inspired user interface with a typing animation for the title and a table to display call details.

## Features:

- Users can input JSON data containing call details.
- The application processes the JSON data and populates a table with call information.
- A typing animation is displayed during the loading process.
- Retro-themed styling with customizable scrollbar.

## Technologies Used:

- HTML
- CSS
- JavaScript

## Usage:

1. Input the JSON data into the provided textarea. The expected JSON format is as follows:
   ```json
   {
     "extrato": [
       {
         "Data": "YYYY-MM-DD",
         "movel": [
           {
             "Hora": "HH:MM:SS",
             "Nro_Destino": "Destination Number",
             "Consumo_Segundos": "Consumed Seconds",
             "Valor_Ligacoes_Unitario": "Unit Value"
           }
           // Additional call objects...
         ]
       }
       // Additional entry objects...
     ]
   }
