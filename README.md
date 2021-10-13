# Pong com VisualScript

jogo Pong simples. Esta demonstração mostra as práticas
[signals](https://docs.godotengine.org/en/latest/getting_started/step_by_step/signals.html).

Language: [VisualScript](https://docs.godotengine.org/en/latest/tutorials/scripting/visual_script/index.html)

Renderer: GLES 2


## Como funciona?

As paredes, remo e bola são todos
[`Area2D`] (https://docs.godotengine.org/en/latest/classes/class_area2d.html)
nós. Quando a bola toca as paredes ou as pás,
eles emitem sinais e modificam a bola.

## imagens

![Screenshot](screenshots/pong.png)
