# Project Timeline

## Phase 1
- Sketched initial hand concept
- Have one string that puls the finger. Then have a rubber band outside on the back of the finger that keeps hand open. So hand closes only if string is pulled
<img width="720" height="1280" alt="image" src="https://github.com/user-attachments/assets/a5714ae8-bd29-4458-9842-a3f7819ed636" />
---

## Phase 2
- Built paper prototype
- Tested finger mobility
<img width="1500" height="2000" alt="image" src="https://github.com/user-attachments/assets/4c50edb3-ea08-4a8d-91ce-32afe0bffa13" />
<img width="1500" height="2000" alt="image" src="https://github.com/user-attachments/assets/287d32a9-5087-4c19-bee0-eb2e99d7a533" />
<img width="1500" height="2000" alt="image" src="https://github.com/user-attachments/assets/fdae8da2-27f9-4e52-a316-77e64afdf38c" />

# Conclusions:
- 3 joints is too little mobility, need to have 4
- The round shape is too hard for now. Need to make the desine simpler to 3D model for now
- Wire goes outside, otherwice theres a chance the trajectory crumples
- Becouse we were not given in this asigment any other sensors or other ways to handle the motor than a speed paddle then need to come upp a way to make it recconaise when its pulled the max way closed
  - Could make it so that as long you press the speed paddle then it stays closed. Once you dont the springs open the hand
      - Could have i string that loops around the motor and goes upp the back off the finger but the mechanical side seems a bit complex for a 3 finger and 1 actuator system
  - Problably should add a max amount of rotations it can goe. Or just make shure the gear can only handle so much force and starts skidding when the max is reached

# Revised plans
<img width="1352" height="2048" alt="image" src="https://github.com/user-attachments/assets/d2ddf3ae-04ba-43fd-aa92-28d64cdc2edd" />
<img width="1352" height="2048" alt="image" src="https://github.com/user-attachments/assets/d2ddf3ae-04ba-43fd-aa92-28d64cdc2edd" />
- The midpoint of desingning
<img width="2048" height="1865" alt="image" src="https://github.com/user-attachments/assets/4cf1c6ce-6bb0-45a7-b2b5-12cbce412019" />
- The final result

---
## Phase 3
- Started 3D modeling in Fusion
- Problems / decisions:
  - Redesigned the model to make it easier to 3D print, resulting in a more rectangular structure
  - Added grooves for the string and rubber band
    - Rubber band groove is mainly for alignment
    - String groove is mostly decorative but helps guiding
  - Changed joint design:
    - Instead of symmetric joint holes on both sides, one side now has two holes and the connecting part has one elongated slot
    - Allows a small steel screw to pass through and be tightened from both sides
(picture)

---
## Phase 4
- Printed first finger prototype
- Problems / improvements:
  - Initially did not account for required clearance in the joints for movement
  - Movement space was too limited, causing stiffness
  - Increased the joint slope/clearance for smoother motion
  - First print also failed at the string anchor point
    - Fixed by redesigning it as a full through-hole
    - String now shares the same anchor point as the rubber band
(picture)

---
## Phase 5
- Printed and assembled fingers
- Problems / observations:
  - Screws holding the joints tended to loosen over time
    - Plan: add glue or locking method between joints
  - Joint tightness:
    - Movement is surprisingly smooth and responsive despite tight tolerances
    - Does not overextend toward the rubber band side (except the smallest joint, by design)
    - Intended function: enable pinching/gripping small objects
  - Design iteration:
    - Initially switched to a 2-finger design for pinching
    - However, finger collision limited usable object sizes
    - Decided to return to a 3-finger layout:
    - Two fingers on one side, one on the other
    - Prevents collision and improves grip range
  - Next consideration:
    - Ensure screw placement has enough clearance and does not interfere with motion
(picture)
