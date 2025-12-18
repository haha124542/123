from robot_lib import World, AnimatedRobot
w = World(10, 10)
r = AnimatedRobot(w, 1, 1)
def turn_right():
    for i in range(3):
        r.turn_left()
r.turn_left()
def e04():
    for i in range(4):
        r.move(9)
        turn_right()
        r.move(1)
        turn_right()
        r.move(9)
        r.turn_left()
        r.move(1)
        r.turn_left()
e04()
r.move(9)
turn_right()
r.move(1)
turn_right()
r.move(9)
