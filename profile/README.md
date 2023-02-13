# Open Pokémon (UD)

## What is it?

Open pokemon is a generic open backend.

Everyone can download it, modify it, use it as wanted.

## What 'UD' means?

Under development. Do not use it right now. But you can follow the
project and help :D

## How can I use it?

You must download and run at least:

 - Service Discovery;
 - API Gateway;
 - Third parties;
 - Main module.

Every basic information about pokémons, types, abilities... will
be found in **Main Module**. But, due to a microservice 
architecture, API Gateway pattern was used and this will need 
to use **Service Discovery** (Eureka) module.

**Main module** information are stored in a database, 
conveniently created in the **Third Parties** module.

## Precautions

**Third Parties** was configured with generic values (for usernames, 
passwords, ports...). 

If you wanna use it, you **MUST** replace this values by your own
values.
