# Hi there, I'm Hariiiy!
>**Video Game Programming / Video Game Designing / Digital Crafting**

</br>

🎮    **Video Game Programmer** trying to put all my effort in the **Video Game Industry** </br></br>
📝    **DEC - Computer Science Technology**, Lasalle College, Montreal, QC </br></br>
🚀    Main Game Engines: **Unity3d / UnrealEngine** </br></br>




## 💻 Skill Stack:

<summary><b>Languages</b></summary>

  <img src="https://img.shields.io/badge/c%23-%23239120.svg?style=flat&logo=csharp&logoColor=white" width="45">  <img src="https://img.shields.io/badge/c-%2300599C.svg?style=flat&logo=c&logoColor=white" width="60">
  <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white" width="85">
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white" width="100">
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E" width="130">
  <img src="https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54" width="110">
  



<summary><b>Engine</b></summary>

  <img src="https://img.shields.io/badge/unity-%23000000.svg?style=flat&logo=unity&logoColor=white" width="100">  <img src="https://img.shields.io/badge/unrealengine-%23313131.svg?style=flat&logo=unrealengine&logoColor=white" width="180">
  


<summary><b>Other</b></summary>

  <img src="https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white" width="120">  <img src="https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white" width="80">
  <img src="https://img.shields.io/badge/Itch-%23FF0B34.svg?style=flat&logo=Itch.io&logoColor=white" width="90">
</br>
</br>

<!-- BEGIN YOUTUBE-CARDS -->
<!-- END YOUTUBE-CARDS -->

## 👾 Projects:
<details>
<summary>
  
  #### <b>The Sunset</b> 

  >『Unity』『Indie』

</summary>

  ><p>『A 2D diablo like rpg game with multiple controllable characters, unique skills and 30+ perks that can be custom by player to boost up the battle. "Survive, Fight, and Build in a fungal apocalypse."』</p>

<a href = "https://patreon.com/user?u=52585742&utm_medium=unknown&utm_source=join_link&utm_campaign=creatorshare_creator&utm_content=copyLink"> View Dev logs on my Patreon </a>


<details>

<summary><b>Role</b></summary>

<b>Solo Game Developer</b>

 ><p>Overview: As the sole developer of this project, I am responsible for every part of game creation, from initial concepts to final implementation. Including programming, art and animation, level design, sound design, and functions testing.</p>


- **Programming:** Implemented game logic, physics, and user interfaces using Unity 3D and C#
- **2D Art and Animation:** Created character designs, environments, and characters' rigging animations using Adobe Photoshop, Sai2, Spine.
- **SFX:** Created Sound and background music with FL studio, Some source from: Artlist.io

<b>Technology Stack</b>
 
| Category          | Technologies               |
|-------------------|----------------------------|
| Engine            | Unity 3D                   |
| Programming       | C#                         |
| Version Control   | Git, GitHub                |
| Art and Design    | Adobe Photoshop, Spine, Sai 2     |
| Sound             | FL Studio                  |

<br>

<summary><b>Coding highLight</b></summary>
<br>

- **Save System:** Using .json files to save player's game data, Save Manager code with Singleton and Prototype, and can be called to save and load when needed by any game object script in the game.
- **Scriptable Objects:** Using scriptable objects to store perks' data, laying the foundation for adding more perks in future versions, making the perks better managed and making their mechanisms more diverse.
- **Object Pool:** Enemies are stored in a object pool, saving resources needed to generate each enemy and reducing the resources consumed by the monster group. Also preparing for future shooting mods character.

<br>

</details>


<details>

<summary><b>Key Challenges and Solutions</b></summary>

|Challenges       | Solutions             |
|-------------------|----------------------------|
| High perk count leads to loading delays        | Seprate the perk pool acooding to the perk type. Split the index numbers and assign meaning to each number,『Compared to 10001, 10002... Using a index to 13042, 1 represents the category of the perk, 3 represents the perk level, and 042 is the perk of the 42nd effect in category 1.』 This organization reduces the number of perks the system needs to search through, enhancing efficiency and minimizing resource consumption.  |
|Latin fonts lack Unicode support for certain languages       | Developed a manager script that searches for all in-game text upon startup or when the language setting is changed. This script automatically updates the text to use a stylized font that supports the selected language.          |


<br>

</details>




<details>

<summary><b>Screen Shots</b></summary>
 
</details>




---

</details>

<details>
<summary>
  
  #### <b>Fishin!</b> 

  >『Unreal 5』『Co-op』『Game Jam』

</summary>

  ><p>『3D top-down fishing game with a secret! "Everything will seem peaceful until the secret is discovered. Fish, store, sell, and upgrade! Discover the secret through the hint on the boat!"』</p>

<a href = "https://itch.io/jam/game-off-2024/rate/3147780"> Itch.io </a>


<details>

<summary><b>Role</b></summary>

<b>Programmer, Designer</b>


- **Programming:** Implemented Fishing Function and the interaction between player and fishes.
- **Visual:** Created the Water body effect with shader; numbers of particle effects.
- **Spawner** Method to randomly spawn fished and respawn after a catch.

<b>Technology Stack</b>
 
| Category          | Technologies               |
|-------------------|----------------------------|
| Engine            | Unreal 5                   |
| Programming       | Unreal BluePrint           |
| Version Control   | Git, GitHub                |


<br>


</details>



<details>

<summary><b>Screen Shots</b></summary>
 
</details>




---

</details>





<details>
<summary>
  
  #### <b>Neon Paradox</b> 

  >『Unity』『Co-op』

</summary>

  ><p>『3D Level-based FPS game, Complete scene construction, level building and 3D animation. "Run, shoot, and strengthen yourself in the cyber forest."』</p>

<a href = ""> Repo </a>


<details>

<summary><b>Role</b></summary>

<b>Programmer, Designer, Animator</b>

- **Programming:** Buff system, player movement, shooting and physical bullets, enemy spawing.
- **3D animation and Visual:** Particle effect for explosion effects, bullet effects, scene light baking，3D animation for weapon.

<b>Technology Stack</b>
 
| Category          | Technologies               |
|-------------------|----------------------------|
| Engine            | Unity                      |
| Programming       | C#                         |
| Version Control   | Git, GitHub                |

<br>

<summary><b>HighLight</b></summary>
<br>

- **3D Animation and Blend Trees:** Use Unity's keyframes to craft detailed 3D animations for character hands and weapons, animation set of actions and transitions such as shooting, reloading, and running.
- **Bullet and Shooting experience:** Bullets employ Rigidbody to simulate realistic trajectories, ejecting from the muzzle and gradually descending to the ground. Since each bullet is a GameObject with a Rigidbody component, an object pool is use to reduces the resource use caused by directly generating new bullets.
- **Buff System:** Players can choose different Buff effects to strengthen themselves in the game. Buffs of the same type will also provide combo effects.
<br>

</details>


<details>

<summary><b>Screen Shots</b></summary>
 
</details>




---

</details>





<details>
<summary>
  
  #### <b>Museum</b> 

  >『Unity』『Co-op』

</summary>

  ><p>『3D Horror puzzle game. "Working as a night security guard in a museum, but why I keep hearing strange noises emanating from the corridor."』</p>

<a href = ""> Repo </a>


<details>

<summary><b>Role</b></summary>

<b>Programmer, Designer</b>


- **Programming:** Character movement and camera swing, interactive system, and level puzzle.
- **Visual:** Using the rendering image as a lens filter and baking lighting effects for the levels.

<b>Technology Stack</b>
 
| Category          | Technologies               |
|-------------------|----------------------------|
| Engine            | Unity                      |
| Programming       | C#                         |
| Version Control   | Git, GitHub                |


<br>


</details>



<details>

<summary><b>Screen Shots</b></summary>
 
</details>




---

</details>





<details>
<summary>
  
  #### <b>Forest</b> 

  >『Console』『Solo』

</summary>

  ><p>『A Text-based RPG games. "As a warrior, you need to survive in this dangerous environment and defeat the enemy."』</p>

<a href = ""> repo </a>


<details>

<summary><b>Role</b></summary>

<b>Programmer</b>


- **Random Generation:** Randomly generated safe houses and monster lairs.
- **Env:** Dangerous terrain depletes the player's health points; walls, trees, and stones impede the player's movements.
- **Battle** Players can engage in turn-based combat with enemies.

<b>Technology Stack</b>
 
| Category          | Technologies               |
|-------------------|----------------------------|
| Console            | Visual Stuido                  |
| Programming       | C#           |


<br>


</details>



<details>

<summary><b>Screen Shots</b></summary>
 
</details>




---

</details>





<details>
<summary>
  
  #### <b>The Two World</b> 

  >『Construct 3』『Co-op』『Youth Fusion』

</summary>

  ><p>『3D top-down fishing game with a secret! Everything will seem peaceful until the secret is discovered. Fish, store, sell, and upgrade! Discover the secret through the hint on the boat!』</p>

<a href = "https://fusionjeunesse.org/jeuxvideo_files/18-19/Canada/MontrealEtPeripherie/S/Rosemont/TheTwoWorlds/Jeu"> Youth Fusion 2018-2019 edition</a>


<details>

<summary><b>Role</b></summary>

<b>Programmer, Artist</b>


- **Programming:** Simple level shooting and interactive puzzles
- **Art:** Some simple scene sprite

<b>Technology Stack</b>
 
| Category          | Technologies               |
|-------------------|----------------------------|
| Engine            | Construct 3                |
| Art            | Aseprite               |


<br>


</details>



<details>

<summary><b>Screen Shots</b></summary>
 
</details>




---

</details>

