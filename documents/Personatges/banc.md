# **Personatge: Banc**

- ### **Versió:**
> 1.0

- ### **Data**
> 6-4-2025

- ### **Autor** 
> Arnau Casals

- ### **Descripció**
> El banc és el sistema encarregat de gestionar els pagaments dins l'aplicació, assegurant transaccions segures entre els clients, cuiners i repartidors.

- ### **Actors relacionats:** 
> Client, cuiner, repartidor.

- ### **Flux principal:** 
> 1. Rebre el pagament del client a través de la plataforma de pagaments.
> 2. Processar l'autenticació de la transacció de manera segura.
> 3. Distribuir els fons corresponents als cuiners i repartidors segons la comanda.

- ### **Subfluxos:** 
> - Gestió de reintents en cas d'error en la transacció.
> - Confirmació i notificació del pagament als usuaris implicats.

- ### **Fluxos alternatius:** 
> - En cas de fallida en el pagament --> Es mostra un missatge d'error i s'ofereix la possibilitat de reintentar la transacció.

- ### **Prioritat:** 
> Normal. És qui s'encarrega de realitzar les transaccions entre client, cuiner i repartidor.

- ### **Comentaris:** 
> Es podrien implementar diversos mètodes de pagament a escollir segons vulgui el client.
