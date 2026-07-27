# UV and Baking Basics

## UV priorities
- Consistent texel density when needed
- Seams hidden where practical
- Straight shells when it helps painting or trim usage
- Enough padding for target resolution

## Baking priorities
- Clean cage setup
- Match smoothing groups and hard edges to UV splits when required
- Test normal map orientation in the destination engine or renderer
- Bake early enough to catch problems before texturing too far
