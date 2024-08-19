# Godot

## sources:
> GODOT FROM ZERO TO PROFICIENCY (all the 4 books)


# introduction
I want to use this as a way to learn all the basics of Godot, in a clean way

```Gdscript
extends KinematicBody2D

var speed = 200

func _process(delta):
    var velocity = Vector2()

    if Input.is_action_pressed("ui_right"):
        velocity.x += 1
    if Input.is_action_pressed("ui_left"):
        velocity.x -= 1
    if Input.is_action_pressed("ui_down"):
        velocity.y += 1
    if Input.is_action_pressed("ui_up"):
        velocity.y -= 1

    velocity = velocity.normalized() * speed
    move_and_slide(velocity)
```

$$E = mc^2$$
# Learning-Godot
