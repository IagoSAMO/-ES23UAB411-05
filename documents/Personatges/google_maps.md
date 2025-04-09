# **Personatge: Google Maps**

- ### **Versió:**
> 1.0

- ### **Data:**
> 6-4-2025

- ### **Autor:** 
> Lluc Aymerich

- ### **Descripció:**
> Google Maps és el sistema integrat que permet visualitzar en temps real la ubicació del repartidor i la ruta d’entrega, millorant el seguiment i la comunicació amb el client.

- ### **Actors relacionats:** 
> Client, repartidor.

- ### **Flux principal:** 
> 1. Mostrar la ubicació actual del repartidor.
> 2. Traçar la ruta més eficient des de la cuina fins al client.
> 3. Permetre al client seguir el repartiment en directe.

- ### **Subfluxos:** 
> - Actualització dinàmica del trànsit i la ruta.
> - Notificació d’aproximació al destí.

- ### **Fluxos alternatius:** 
> - Si no es pot accedir a la ubicació en temps real --> Mostrar informació estimada d’entrega basada en la comanda i l’hora prevista.

- ### **Prioritat:** 
> Alta. Millora la transparència i confiança del client durant el procés de repartiment.

- ### **Comentaris:** 
> Es podria considerar una integració més profunda per mostrar també la previsió meteorològica o alertes de trànsit.
