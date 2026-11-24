# Reglas del equipo

## Git
- Prohibido hacer push directo a `main`. Todo va por Pull Request.
- Una rama por tarea: `feature/nombre`, `fix/nombre`, `docs/nombre`.
- Antes de empezar a trabajar: `git checkout main && git pull`.
- Commits pequeños y con mensaje claro (ej: "Agrega formulario de login").
- Todo PR debe ser revisado por al menos 1 compañero antes del merge.
- Nunca subir `.env`, contraseñas ni `node_modules`.

## Carpetas (cada quien trabaja en lo suyo)
- `frontend/` → Frontend A y B
- `backend/` → Backend A y B
- `database/` → Backend A (avisa al grupo si cambia el esquema)
- `docs/` → Product Owner

## Scrum
- Daily de 10 minutos, rotando moderador cada semana.
- Cada tarea debe estar en el tablero, asignada y movida de columna.
- Al final: retrospectiva (qué salió bien, qué mejorar) en `docs/retrospectiva.md`.

## Comunicación
- Si vas a tocar un archivo compartido (App.jsx, rutas, index.js, package.json), avisa en el grupo.
- Si cambias el esquema de la BD o un endpoint, actualiza `docs/acuerdos-api.md` y avisa.
- Un bloqueo se avisa el mismo día, no se espera a la daily.

## Importante para la nota
- Los 5 deben tener commits y tareas asignadas.
- Todos deben entender todo el sistema: la defensa oral es individual.