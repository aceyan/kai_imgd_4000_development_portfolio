# IMGD 4000 Development Portfolio
**Website Link**: https://zhouck0811.wixsite.com/irongoat   
**Repository Link**: https://github.com/czhou2822/GitProjectGoat   

## My Role in the project
### Design
I've always wanted the opportunity to explore the implementation of interactive terrain in games. Especially after being impressed by the [interactive snow scene of rise of the tomb raider](https://www.youtube.com/watch?v=QSYkwdlDN8s), I try to take this opportunity of this course to explore the implementation of deformable snow. In order to implement this technical attempt, we designed the core gameplay of tower defense in the snow in combination with the art's expectation of the game art style in our project.   
To combine snow deformation with the core gameplay, we designed a game mechanism that can collect snow from the the snowy ground and use it to slow down the enemy. This not only demonstrates my technical goals, but is also a mechanism to make the game unqiue and fun.

### Game logic programmer
I used c++ code and animation blueprint to implement the basic control of TPS characters, such as over-shoulder aiming and shooting, the character's running, jumping and so on. 

### Graphics programmer 
I was responsible for the development of graphics and related functions of the game.
1. We chose a borderland-like cartoon style for our art style. I was responsible for the development of cel shading post process and outline post process to achieve this graphical effect.
2. I also take the responsibility of the implementation of materials and snow deformation mechanism.
3. I implemented the freezing effect when the enemy is slowed down.
4. I developed landscape material so that designers and our artists can use the built-in landscape tools to easily paint the landscape. The mechanism of snow deformation can be automatically applied on where the terrain is mapped with snow. This gives us a lot of freedom in the design of the terrain and the scene.

### Version control consultant
Because I have some experience on git, I often solve the problem of using git for my teammates. For example, resolving conflicts, reverting versions, etc.

### Technical goals
#### Individual goals
1. The implementation ofsnow deformation in UE4.
2. Use unreal c++ and animation state machine to implement TPS character control.
3. Toon shading post proccess (Cel shading + silhouette outline).
4. Landscape material development.
5. Learn to use unreal material editor and material blueprint.
6. Learn how to customize shader in unreal
7. Explore the way unreal C++ interacts with blueprints.

#### Team goals
1. Implementation of TPS game mechanics, including over-shoulder shooting and collision testing.
2. Tower defender game mechanic implementation, including tower building, tower placement, various defense tower behaviors, enemy AI, etc.
