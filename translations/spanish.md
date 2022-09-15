<img width="1282" alt="image" src="https://user-images.githubusercontent.com/17634377/189934612-2b0365b3-ac96-4637-a31a-92692e23f0b0.png">

# 🧩 Commit Driven Development

> Repo para compartir algunas ideas presentadas en la Git Merge 2022 Chicago by Carlo Gilmar.

[🔗 Git Merge 2022 Talk Slides](https://www.slideshare.net/CarloGilmarPadillaSa/git-merge-2022)

# 🚀 Commit Driven Development 

1. Piensa primero en cómo vas a implementar un nuevo feature en pasos antes de escribir código.
2. Escribe una lista con las descripciones de estos pasos. Sé muy puntual con cada paso.
3. Escribe las líneas de código suficientes para completar ese paso. Realiza commit de cada paso escrito. No importa si vas descubriendo pasos nuevos.
4. Al terminar tu feature, mira el log de tus commits, deberás ser capaz de leer la historia de cómo construiste y pensaste ese feature paso a paso.

# ❤️ Valores 

- Orden y claridad antes de escribir código.
- Comunicación eficiente para transmitir cómo estás construyendo software.
- Apertura al feedback, a realizar preguntas y pedir apoyo.
- Invierte tiempo en tus herramientas, invierte tiempo en aprender git.

# 🤝 Quién debería usar este enfoque

- Desarrolladores buscando nuevas formas de trabajar.
- Reclutadores que quieren entender cómo sus candidatos piensan y construyen software.
- Líderes de equipo cuya intensión es construir y mejorar la cultura de colaboración en sus equipos.
- Compañías de software que necesitan mejorar sus experiencias de onboarding para nuevos miembros.
- Educadores y promotores de tecnologías de software que necesitan nuevas dinámicas de aprendizaje.
- Developers novatos.

# Ejemplos

Lista inicial antes de escribir código:

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

# 🏆 Logros

- Serás capaz de leer tu propia forma de pensar y construir software solo leyendo el log de tus commits.
- Serás capaz de reproducir y reconstruir tu proceso de construcción de software a través de los commits.
- Cualquier persona de tu equipo será capaz de entender y seguir tu forma de escribir software.
- Cualquier persona de tu equipo será capaz de reproducir tu proceso de construcción de software.
- Cualquier persona fuera de tu equipo pero con contexto de tus herramientas será capaz de entender y seguir tu forma de escribir software.
- Cualquier persona fuera de tu equipo pero con contexto de tus herramientas será capaz de reproducir tu proceso de construcción de software.

<img width="1095" alt="image" src="https://user-images.githubusercontent.com/17634377/189939435-aa321529-bd0e-49e5-977d-8a5d9fe36b8a.png">

# 🤔 ¿Cuándo debo usar este enfoque?

- Usar este enfoque antes de escribir cualquier línea de código te ayudará a tener mucha claridad y también te hará preguntarte sobre cuestiones que quizá tendrás que preguntarle a tu equipo. Orden y claridad.
- Construir features de esta forma te ayuda a construir una bitácora de tus propios procesos de creación, esto ayuda a conocerte y confrontarte de forma personal. También puede servir para compartir tu visión y perspectiva con tu equipo.
- Si tu equipo sigue este enfoque, podrás aprender mucho de los procesos creativos de tus colegas.
- Puedes incorporar esto a tu proceso de onboarding para nuevos miembros para mostrarles cómo trabajan y habilitarlos de forma más eficiente.
- Puedes usar este enfoque al resolver ejercicios o code challenges y así mostrarle a tu entrevistador cómo estás construyendo software.
