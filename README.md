## Sidequest Week 2

GBDA302 Week 2 Example 3: Platforms (AABB Collisions)

---

## Authors

Karen Cochrane, David Han, and Katrina Huang - k262huan - 21070864

---

## Description

Adds several rectangular platforms. The blob is drawn as a noisy circle but collides using a simple axis-aligned bounding box (AABB). X and Y are resolved separately to keep behaviour predictable and teachable.

When the blob is on the ground, the blob is relaxed and surrounded by a nice environment. But when the blob is in the air, it starts to panic and the environment around the blob becomes more dark and scary.

---

## Learning Goals

Learning Goals:

- Convert a circular sprite to an AABB for collision
- Implement overlap test and push-out resolution
- Manage grounded state only when landing on top faces
- Change background/fill colours due to certain circumstances (in air vs on ground)

---

## Assets

N/A

---

## GenAI

The code was written by Dr. Karen Cochrane but she used GenAI to write the comments.
The code written/comments made by Katrina Huang does not include GenAI use.

---
