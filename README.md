Ter info: een Laravel app die je van Github haalt werkt niet gelijk. Je moet eerst een aantal dingen doen:

1. Clone de app vanaf Github (_Open with Github Desktop_)

2. Open de app in je IDE

3. Open een Terminal

4. Run het commando: **composer install**

5. Maak een copy van  **.env.example** en verander de naam in **.env**

6. Run het commando: **php artisan key:generate**
 Hiermee krijgt de sleutel in je .env een correcte waarde.

7. Open het .env bestand
Check of de database gegevens kloppen, en pas aan indien nodig.

8. Run het commando: **php artisan migrate**

9. Run het commando: **npm install**

10. Run het commando: **npm run dev**

11. Run het commando: **php artisan migrate**

12. Run het commando: **php artisan serve**
