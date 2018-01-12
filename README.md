課題２

ROSによるプログラミング

対象（亀）が自動で動く

$ rostopic type /turtle1/cmd_vel

geometry_msgs/Twist

$ rostopic pub -r 1 /turtle1/cmd_vel geometry_msgs/Twist -- '[2.0, 0.0, -1.0]'
