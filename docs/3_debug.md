## Issues and solutions

If the main camera (the one attached to the player) dose not move when you play the game (same image is render) only solution seem to use a different camera. Spawn a new camera with the respective command or drag in the scene a FusionCameraActor object. Use this camera to take images.

If there a actors in the scene that are not a static mesh no object mask will be applied. To solve this go to the FusionCameraActor and in the details panel select the AnnotationCamSensor. Search for "Primitive render mode" and select "Render Scene Primitives". This will color the non static mesh actors with a grey color.

If unreal engine crashes after some command make sure to play the level first.
