# Journal
Write your Journal questions and notes here.

# Phase 1: The Divine Blueprint

In this phase, I created the Artifact class and added a constructor that sets the material. I also tested it in the main method. Using a constructor is important because it makes sure the material is set when the object is created instead of having to set it later.

# Phase 2: Legendary Armaments

In this phase, I created the DivineWeapon class and used super() to call the Artifact constructor. If I leave out super(), Java will try to call a constructor with no arguments, but Artifact does not have one. This causes an error. Java requires the parent class to be initialized before the child class.

# Phase 3: The Master's Shortcuts

In this phase, I added a new constructor that gives the weapon a default essence. Using this() makes the code easier because I don't have to repeat the same code. If I want to change the default essence later, I only need to change the value inside this().
