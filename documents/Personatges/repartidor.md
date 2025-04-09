# **Personatge: Repartidor**

- ### **Versió:**
> 1.0

- ### **Data:**
> 6-4-2025

- ### **Autor:** 
> Lluc Aymerich

- ### **Descripció:**
> El repartidor és l’actor encarregat de transportar els plats des de la cuina fins al client, mantenint una comunicació contínua amb l'aplicació per mostrar l'estat de l'entrega i seguir la ruta assignada.

- ### **Actors relacionats:** 
> Client, cuiner, Google Maps.

- ### **Flux principal:** 
> 1. Rebre notificació d’una nova comanda assignada.
> 2. Acceptar i iniciar l'entrega.
> 3. Utilitzar Google Maps per navegar cap al destí.
> 4. Actualitzar l’estat de l’entrega en temps real.
> 5. Confirmar l’entrega un cop feta.

- ### **Subfluxos:** 
> - Possibilitat d’escollir entre diferents tipus d’entrega (autònom, per part del cuiner, recollida pel client).
> - Visualització de les comandes pendents i historial d’entregues.

- ### **Fluxos alternatius:** 
> - En cas d’impossibilitat de fer l’entrega --> Derivar a un altre repartidor o contactar amb el suport.

- ### **Prioritat:** 
> Alta. És una part fonamental en l’experiència de l’usuari final i en el compliment dels terminis d’entrega.

- ### **Comentaris:** 
> Caldria definir millor els criteris de pagament segons el tipus de repartiment i implementar un sistema de notificacions clar.
