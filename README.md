Ter info: een Laravel app die je van Github haalt werkt niet gelijk. Je moet eerst een aantal dingen doen:

Clone de app vanaf Github (Open with Github Desktop)

Open de app in je IDE

Open een Terminal

Run het commando: composer install

Maak een copy van . env.example en verander de naam in .env

Run het commando: php** artisan key:generate** Hiermee krijgt de sleutel in je .env een correcte waarde.

Open het .env bestand Check of de database gegevens kloppen, en pas aan indien nodig.

Run het commando: php artisan migrate

Run het commando: npm install

Run het commando: npm run dev

Run het commando: php artisan migrate

Run het commando: php artisan serve
