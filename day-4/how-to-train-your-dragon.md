## How To Train Your Dragon

## Concepts/Items Covered
* Joints
* Inverse Kinematics (IK)
* Skinning

## Introduction
Learn to rig and control your characters using joints, skinning, and inverse kinematics. Train your dragon and use your knowledge about keyframe animations to see if you can get your
dragon to fly!

## Part I: The Birth of a Dragon
1. Import your dragon from the already made dragon file.

## Part II: Create the Skeleton
1. Get into your Rigging Menu Set.
2. Click on the Rigging Shelf.
3. Select the ```Joint``` tool.
4. Get into your orthographic side view.
5. Place a joint in the origin of your dragon by clicking on the center of the dragon object.
6. Click back towards the tail in increments to create joints for your character.
7. When you reach the tail, click on the up arrow to go back to your initial joint.
8. Select upwards towards the head of your dragon and continue to create joints.
9. Press enter when the main body has been fully jointed.

## Part III: Finish the Skeleton
1. Start on the leg of your dragon by clicking on a high point in the leg and creating a joint node there.
2. Select downwards, clicking on the main joint areas for the leg.
3. Press Enter when done.
4. Continue to do the same for all of your legs and arms.
5. Position the joints correctly by moving into different views and adjusting the joints accordingly.
6. Combine and parent nodes by shift selecting multiple joints and pressing ```P``` on your keyboard.

## Part IV: IK Handlers
1. Create an IK handler by clicking on the Rigging shelf.
2. Select the Inverse Kinematics tool.
3. Create an IK handler for your legs by clicking on the topmost part of your leg and the bottom part of your leg afterwards. That should pop up a red line between the top and bottom leg parts.
4. Go into your Attribute Editor, find the IK Handler Attribute dropdown and make sure ```Stickiness``` is on.

## Part V: Dragon Skinning
1. Select all of your joints and the body of your dragon.
2. In the Rigging shelf, click on ```Bind Skin```.
3. Move your dragon around to see what happens!

## Part VI: The Noble Dragon
1. Create an animation by setting keyframes and rotating/moving the joints.
2. Apply this to your own characters in your final project!
