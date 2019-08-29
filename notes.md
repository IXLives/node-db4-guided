# Requirements

A client has hired you to track zoo animals.
For each animal, you must track that their name, species, and all zoos in which they have resided (including zoo name and address).

Determine the database tables necessary to track this information.

Label any relationships between table.
### Solution
Animal, Species, Zoos
Animals (many) <==> Species (one)
Animals (many) <==> Zoos (many)

### Table Details
zoos 
    - zoo_id
    - zoo_name
    - address
species 
    - species_id 
    - species_name
animals 
    - animal_id
    - name
    - species_id
zoo_animals
    - zoo_id
    - animal_id


