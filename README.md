# Dungeon Generation
Some toys to play with generating dungeons for Roguelikes.

# Basic Dungeon Generator
## Sample Output
```





         #####
         #...#
         #...#
         #...#
         #####

  #####
  #...#
  #...#
  #...#
  #####                 ########
                        #......#
   #########            #......#
   #.......#            #......#
   #.......#            #......#
   #.......#            #......#
   #.......#            #......#
   #.......#            #......#
   #.......#            ########
   #########








```


# BSP Generator
## Sample Output
### Rooms-Fill-Nodes = True:
```
################################################################################
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
#..............##.........##............##.........##.............##...........#
############################............##.........#############################
############################............########################################
#............##...........###########################.............##...........#
#............##...........################.........##.............##...........#
#............##...........##............##.........##.............##...........#
#............##...........##............##.........##.............##...........#
#............##...........##............##.........##.............##...........#
#............##...........##............##.........##.............##...........#
#............##...........##............##.........##.............##...........#
#............##...........##............##.........##.............##...........#
#............##...........##............##.........##.............##...........#
#............##...........##............##.........##.............##...........#
#............##...........##............##.........##.............##...........#
################################################################################
```

### Rooms-Fill-Nodes = False:
```
#############   #############                                   ################
#...........#   #...........#                       #############..............#
#...........#   #...........#  ##################   #..........##..............#
#...........#   #...........#  #................#   #..........##..............#
#...........#   #...........#  #................#   #..........##..............#
#...........#   #...........#  #................#   #..........##..............#
#...........#   #...........#  #................#   #..........##..............#
#...........#   #...........#  #................#   #..........##..............#
#...........#   #...........#  #................#   #..........##..............#
#############   #...........#  #................#   #..........##..............#
                #############  #................#   #..........#################
                               #................#   #..........#
                               #................#   ############
                               #................#   ############
                #############  #................#   #..........#
  ############  #...........#  #................#   #..........#
  #..........#  #...........#  #................#   #..........###############
  #..........#  #...........#  #................#   #..........##............#
  #..........#  #...........#  #................#   #..........##............#
  #..........#  #...........#  #................#   #..........##............#
  #..........#  #...........#  #................#   #..........##............#
  #..........#  #...........#  #................#   #..........##............#
  ############  #...........#  ##################   #############............#
                #############                                   ##############
```