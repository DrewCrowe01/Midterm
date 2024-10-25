# Pokemon Overview Dashboard

## Reproducibility and Code
This dashboard presents a visually compelling and data-driven overview of key Pokémon statistics

[View the Dashboard on Tableau Public](https://public.tableau.com/app/profile/drew.crowe/viz/Midterm_17298818593900/PokemonOverview?publish=yes) 

## Readme

### Introduction
This dashboard is ideal for Pokémon enthusiasts, competitive players, or analysts who want to compare and rank Pokémon based on their stats. Users can dynamically filter Pokémon based on their desired attributes, helping them identify the best candidates for battles or strategic play.

### Problem to Solve
The primary purpose of your Pokémon dashboard is to provide an interactive tool for analyzing and comparing Pokémon based on their key battle stats. It offers an intuitive way for users to explore and filter Pokémon data, making it useful for a variety of use cases. Without a dashboard, users would need to manually compare Pokémon by looking up stats one-by-one, which can be tedious. This dashboard streamlines the comparison process, enabling users to quickly find the best Pokémon for their needs based on customizable filters.

### Data/Operation Design
- **Data Source**: The data is from https://pokemondb.net/pokedex/all, I web scrapped the data using python, based on the lesson learned during class.
- **Prep**: web scrapped, mulitple calculated fields
- **Visuals**: 
  - A bar chart showing showing the Pokemon Rank by Attack.
  - A table showing the Pokemon Type.
  - A Table showing HP, Attack, Defense, Speed, Sp. Attack, and Sp. Defense.
  - A donut graph comparing Total Attack, Defense, Speend and Avg Attack, Defense, and Speed

### Future Work
I am going to transform my Pokémon dashboard into a more interactive, feature-rich battle simulator. Improve the experience by adding layers of realism, complexity, and strategic depth, making it not just a data visualization tool but a full-fledged Pokémon battle simulation platform. 
