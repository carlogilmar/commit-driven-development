<img width="1282" alt="image" src="https://user-images.githubusercontent.com/17634377/189934612-2b0365b3-ac96-4637-a31a-92692e23f0b0.png">

# 馃З Commit Driven Development

> Repo para compartir algunas ideas presentadas en la Git Merge 2022 Chicago by Carlo Gilmar.

[馃敆 Git Merge 2022 Talk Slides](https://www.slideshare.net/CarloGilmarPadillaSa/git-merge-2022)

# 馃殌 Commit Driven Development 

1. Piensa primero en c贸mo vas a implementar un nuevo feature en pasos antes de escribir c贸digo.
2. Escribe una lista con las descripciones de estos pasos. S茅 muy puntual con cada paso.
3. Escribe las l铆neas de c贸digo suficientes para completar ese paso. Realiza commit de cada paso escrito. No importa si vas descubriendo pasos nuevos.
4. Al terminar tu feature, mira el log de tus commits, deber谩s ser capaz de leer la historia de c贸mo construiste y pensaste ese feature paso a paso.

# 鉂わ笍 Valores 

- Orden y claridad antes de escribir c贸digo.
- Comunicaci贸n eficiente para transmitir c贸mo est谩s construyendo software.
- Apertura al feedback, a realizar preguntas y pedir apoyo.
- Invierte tiempo en tus herramientas, invierte tiempo en aprender git.

# 馃 Qui茅n deber铆a usar este enfoque

- Desarrolladores buscando nuevas formas de trabajar.
- Reclutadores que quieren entender c贸mo sus candidatos piensan y construyen software.
- L铆deres de equipo cuya intensi贸n es construir y mejorar la cultura de colaboraci贸n en sus equipos.
- Compa帽铆as de software que necesitan mejorar sus experiencias de onboarding para nuevos miembros.
- Educadores y promotores de tecnolog铆as de software que necesitan nuevas din谩micas de aprendizaje.
- Developers novatos.

# Ejemplos

Lista inicial antes de escribir c贸digo:

```
Step 1: Creating an empty elixir project with mix tool
Step 2: Adding simple http server
Step 3: Adding model account with his unit test
Step 4: Adding genserver for manage the account creation flow with his unit test
Step 5: Set ExUnit for running tests in order
Step 6: Adding function for get the current state of the account
Step 7: Running mix formatter
```

Commit log history `git log --pretty=oneline`:

```
* 499a51e  2 years, 9 months ago Carlo Gilmar Adding function for try to initialize again an account
* 74e7343  2 years, 9 months ago Carlo Gilmar Running mix formatter
* 7ba0030  2 years, 9 months ago Carlo Gilmar Adding function for get the current state of the account
* 3c13c47  2 years, 9 months ago Carlo Gilmar Set ExUnit for running tests in order
* f6f6866  2 years, 9 months ago Carlo Gilmar Adding genserver for manage the account creation flow with his unit test
* b0c4164  2 years, 9 months ago Carlo Gilmar Adding model account with his unit test
* fd86455  2 years, 9 months ago Carlo Gilmar Adding simple http server
* fe0ceeb  2 years, 9 months ago Carlo Gilmar Creating an empty elixir project with mix tool
```

<img width="1088" alt="image" src="https://user-images.githubusercontent.com/17634377/189939119-735248c5-d31d-4e20-a053-c68a9defc26e.png">

# 馃弳 Logros

- Ser谩s capaz de leer tu propia forma de pensar y construir software solo leyendo el log de tus commits.
- Ser谩s capaz de reproducir y reconstruir tu proceso de construcci贸n de software a trav茅s de los commits.
- Cualquier persona de tu equipo ser谩 capaz de entender y seguir tu forma de escribir software.
- Cualquier persona de tu equipo ser谩 capaz de reproducir tu proceso de construcci贸n de software.
- Cualquier persona fuera de tu equipo pero con contexto de tus herramientas ser谩 capaz de entender y seguir tu forma de escribir software.
- Cualquier persona fuera de tu equipo pero con contexto de tus herramientas ser谩 capaz de reproducir tu proceso de construcci贸n de software.

<img width="1095" alt="image" src="https://user-images.githubusercontent.com/17634377/189939435-aa321529-bd0e-49e5-977d-8a5d9fe36b8a.png">

# 馃 驴Cu谩ndo debo usar este enfoque?

- Usar este enfoque antes de escribir cualquier l铆nea de c贸digo te ayudar谩 a tener mucha claridad y tambi茅n te har谩 preguntarte sobre cuestiones que quiz谩 tendr谩s que preguntarle a tu equipo. Orden y claridad.
- Construir features de esta forma te ayuda a construir una bit谩cora de tus propios procesos de creaci贸n, esto ayuda a conocerte y confrontarte de forma personal. Tambi茅n puede servir para compartir tu visi贸n y perspectiva con tu equipo.
- Si tu equipo sigue este enfoque, podr谩s aprender mucho de los procesos creativos de tus colegas.
- Puedes incorporar esto a tu proceso de onboarding para nuevos miembros para mostrarles c贸mo trabajan y habilitarlos de forma m谩s eficiente.
- Puedes usar este enfoque al resolver ejercicios o code challenges y as铆 mostrarle a tu entrevistador c贸mo est谩s construyendo software.
