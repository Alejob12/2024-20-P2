# Parcial práctico 2024-20 (sección 1) — Entrenadores Pokémon en Angular

Repositorio con el código base del parcial práctico 2024-20 del curso de Desarrollo de Software (Universidad de los Andes). Es un fork de [Maldinho18/2024-20-P2](https://github.com/Maldinho18/2024-20-P2); el código base fue preparado por los autores del original.

## Qué contiene

Aplicación **Angular 18** que lista entrenadores Pokémon en una tabla (nombre, imagen y resumen). Al hacer clic en uno se muestra su detalle y su lista de Pokémon (nombre, tipo, nivel y habilidades).

- `TrainerListComponent`: tabla de entrenadores y selección.
- `TrainerDetailComponent`: ficha del entrenador seleccionado.
- `PokemonListComponent`: lista de Pokémon del entrenador (recibe los datos por `@Input`).
- Modelos `Trainer` y `Pokemon`, y datos de ejemplo en `dataTrainers.ts`.

## Cómo ejecutarlo

Requisitos: Node.js 18.19 o superior.

```bash
git clone https://github.com/Alejob12/2024-20-P2.git
cd 2024-20-P2/pokemon
npm install
npm start            # http://localhost:4200
```

## Estructura

```
pokemon/src/app/
  trainer/    Modelo, datos y componentes de lista y detalle
  pokemon/    Modelo y componente de lista
```

## Notas

- Este repositorio se conserva como referencia de un parcial; el código base no es de mi autoría.
- Se actualizó `package-lock.json` para que `npm install` funcione.
