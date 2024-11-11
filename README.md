# SGI 2024/2025 - TP1
----
## Project information

- Main strong points:
  - All objects are generated in a easy way to understand inside "MyContents.js" and all their properties and methods are separated in their own files;
  - The rendering of multiple objects paired with different shadow configurations and different light sources allows for a showcase of a potentially real room;
  - There is a lot of customization made available to the end user through the GUI that allows the manipulation of multiple objects;
  - All the main topics required were successfully completed.

- Scene:
  - The rendered scene represents a room furnished with:
    - a basic table, which contains:
      - a plate with a cake on it, that has a candle with a burning flame imitation, both in size and light animation rendering;
      - an open newspaper made of 3 curved surfaces on one side and mirrored for the other side that can be moved and rotated around almost one third of the table;
      - a jar with a flower inside it that can be moved and rotated in a small area of the table;
      - a fully-customizable spring;
    - a customizable spotlight source to highlight the cake, attached to a lamp that is installed on the ceiling;
    - a chair next to the table, that can be moved around on a small area;
    - 2 boards made of planes with textures applied containing the pictures of the group elements, attached to the back wall. These boards have wooden frames around them;
    - 2 static light sources illuminating the boards mentioned above;
    - a central board on the back wall that contains the drawing of a beetle through the use of cubic bézier curves;
    - a window that allows for light to enter from the outside of the room, simulating the world's natural light. This window has doors with customizable rotations to allow only the desired ammount of light to enter the room.
  - The scene also contains an ambient light which works as a source of illumination for everything in the scene, and a pointlight made with the purpouse of giving a different and more pleasant color to the room.

  - A print of the created scene with the controls minimized can be found in the relative link below:
    - https://github.com/daniel-nunes-03/FEUP_Sistemas_Graficos_Interativos_PW1/blob/main/scene/scene.png

  - The scene can be rendered with a local web server (in VSCode it could be an extension like "Live Server") by running the file described in the relative link below:
    - https://github.com/daniel-nunes-03/FEUP_Sistemas_Graficos_Interativos_PW1/blob/main/index.html
----
## Issues/Problems

- Unimplemented object features:
  - Curved surface pattern for the window doors to allow a more stylish object (similar to the visual of wooden curtains, but applied to doors);

- Small issues/features:
  - Since the mesh of the jar is a double-sided surface, when it receives shadows the texture gets a little weird. Since it allows for a effortless way to make an "expressive" texture to the jar, it was left as-is, but it can qualify as a small glitch if analysed taking into consideration only the coding/rendering quality of the mesh.

- Possible improvements:
  - Better optimized and standardized textures;
  - An even more configurable scene through the GUI allowing, for example, the manipulation of every rendered object;
  - A "dome" that contains the outside-world landscape and the natural light from a "sun";
  - Inclusion of more non-mandatory objects.
    - One of the ideas thought throughout the project was the addition of a sofa in front of the painting boards and a TV on the opposite wall, but there a shortage of time to implement them in a beautiful way. Simple geometries could've been used but they would just be a repetition of simple meshes and would not aggregate to the complexity of the scene, whereas for example, the extensive use of surfaces for the sofa would have.
    - Another idea was the addition of a door that lead to the outside world: that would only make sense if the world outside of the room was populated with interesting objects.
