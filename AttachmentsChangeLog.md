# attachments.lua ChangeLog

### Version 0.83
- Fixed debug spheres appearing when using AttachProp from in game.
- Fixed attachments.txt database scale not being used when scale is omitted from AttachProp call.

### Version 0.82
- Added the ability to press Enter in any TextEntry to submit changes in the Attachment Configuration GUI
- Added the ability to scale the value of the + and - buttons for coarse and fine refinement
- Added the ability to toggle on/off the Debug Spheres showing the attachment point and prop point
- Removed the dependency on an external lua_modifier by internalizing the modifier definition to attachments.lua
- Removed the stun particle effect when Freezing a unit


### Version 0.81
- Added the ability to set a prop to attach to "attach_origin" point, even if this attach string does not directly exist
- Removed extra "model" and "attach" properties from being saved to the attachment database
- Fixed up the model scale settings so that changing the scale of a model after attaching a prop will maintain prop proportions
- Added Attachments:GetAttachmentDatabase() function
- Adjusted the default scripts/attachments.txt database to contain correct values for a couple demonstration prop attaches

### Version 0.80
- Added attachments.lua library