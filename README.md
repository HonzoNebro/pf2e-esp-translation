<div align="center">
<h3 align="center">PF2E-es Honzo</h3>

</div>

<!-- ABOUT THE PROJECT -->

## Proyecto

Traduccion independiente al español del sistema Pathfinder Segunda Edicion para Foundry VTT 14.

Este repositorio se mantiene como paquete separado. El identificador del modulo es `pf2e-es-honzo`, por lo que puede instalarse y publicarse sin ocupar el identificador de otro modulo.

## Compatibilidad

- Foundry VTT: 14.360 o superior dentro de la generacion 14.
- Pathfinder 2E System: 8.1.2 dentro de la generacion 8.
- Requiere Babele y libWrapper.

## Desarrollo

Los commits deberian seguir [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

Para regenerar las fuentes inglesas desde la version configurada de PF2e:

```bash
npm install
npm run pack-extractor
```

## Nota

Este proyecto conserva historial y codigo derivados del trabajo comunitario previo, pero sus manifiestos, releases y automatizaciones apuntan a este repositorio independiente.
