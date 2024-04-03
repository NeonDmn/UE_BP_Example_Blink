## My Unreal Engine 5 recreation of "Blink" ability from a game "Dishonored" by Arcane Studios using blueprints.
1. Obstacle detection
  (Can't blink through solid surfaces)
2. Edge detection
  (Custom behiaviour on blinking towards an edge of a flat surface with a free space to stand on)
3. Floor level detection
  (Prevent from blinking inside the floor by keeping safe distance)
4. Tight space detection
  (Prevent from blinking inside a space where the player would not fit)

As an added bonus it is possible to blink through a tight, normally not traversable gap as long as there is a free space on the other side
<br/>

## Visual movement
**On ground** <br/>
![blink_moveground](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/72c68b3c-780c-4b7c-86e0-56c51d9e9c83)
![UEblink_moveground](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/1ee4f703-ba29-42d2-8a2d-b44d0d96181d)

**Off ground** <br/>
![blink_moveair](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/1d5b67f3-ff53-4a50-bfdc-78473c86592f)
![UEblink_moveair](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/8a4c9e59-99fc-4f70-aaa8-bc804fd10885)

## Blink on ground
![blink_ground](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/8fd72b5d-c969-4aa5-bd00-0724ad7c20f8)
![UEblink_ground](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/894611c8-5edb-4a96-9a89-09515eaae96d)

## Blink off ground <br/>
![blink_air](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/82a1e374-a6de-42b0-9d8f-cdcc12258f17) 
![UEblink_air](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/fda700b2-1d6f-4e29-bbd6-637b7da59227)

## Edge detection
![blink_edge](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/bcf9719c-caf1-4d6a-9168-e8859b0b925e)
![UEblink_edge](https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/faae4bd8-db33-4b4c-9b94-f3fc7d835020)

## Debug visuals
https://github.com/NeonDmn/UE_BP_Example_Blink/assets/25182762/250c7b76-de88-47e4-953a-8d0f6b96bf9c

