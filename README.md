# Pong with VisualScript

jogo Pong simples. Esta demonstração mostra as práticas
[signals](https://docs.godotengine.org/en/latest/getting_started/step_by_step/signals.html).

Language: [VisualScript](https://docs.godotengine.org/en/latest/tutorials/scripting/visual_script/index.html)

Renderer: GLES 2


## Como funciona?

The walls, paddle, and ball are all
[`Area2D`](https://docs.godotengine.org/en/latest/classes/class_area2d.html)
nodes. When the ball touches the walls or the paddles,
they emit signals and modify the ball.

## Screenshots

![Screenshot](screenshots/pong.png)
