# **Personatge: Client**

- ### **Versió:**
> 1.0

- ### **Data**
> 6-4-2025

- ### **Autor** 
> Arnau Casals

- ### **Descripció**
> El client és l'usuari principal de l'aplicació QueMenges. Pot consultar menús, fer comandes a cuiners segons les seves preferències alimentàries i la seva ubicació, fer el seguiment dels seus encàrrecs i valorar el servei rebut. També pot gestionar el seu perfil i subscriure's a serveis especials.

- ### **Actors relacionats:** 
> Cuiner, Google Maps, banc.

- ### **Flux principal:** 
> 1. El client es registra amb correu o compte de Gmail/Outlook.
> 2. Introdueix dades de perfil: direcció, restriccions alimentàries, nom d'usuari i contrasenya.
> 3. Accedeix a l’aplicació i consulta menús filtrats per preferències.
> 4. Fa una comanda seleccionant plats i opcions d’enviament.
> 5. Realitza el pagament a través de l’aplicació.
> 6. Fa seguiment del lliurament del plat en temps real.
> 7. Rep el plat i valora l’experiència.

- ### **Subfluxos:** 
> - Modificació de perfil.
> - Consulta i repetició de comandes anteriors.
> - Comunicació amb el cuiner mitjançant el xat.
> - Reserva amb cuiners no disponibles.
> - Subscriure's al pla de punts i enviaments gratuïts.

- ### **Fluxos alternatius:** 
> - Error en el pagament --> El sistema mostra un missatge i permet reintentar.
> - El cuiner rebutja la comanda --> Es notifica al client i se li ofereixen alternatives.
> - El repartidor no està disponible --> S'ofereix recollida o cuiner com a alternativa.

- ### **Prioritat:** 
> Alta. El client és la peça central del servei i una bona experiència és necessària per l'èxit de la plataforma.

- ### **Comentaris:** 
> Seria útil oferir recomanacions personalitzades basades en l'historial del client.
