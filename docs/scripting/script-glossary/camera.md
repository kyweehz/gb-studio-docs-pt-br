---
sidebar_position: 2
#
# This file is autogenerated. DO NOT MODIFY DIRECTLY
#
---

import ScriptEventPreview from '@site/src/components/ScriptEventPreview';

# Camera

### Camera Lock To Player
Move the camera back to centering on the player, locking into position when the player moves. Optionally allows locking to follow player in only horizontal or vertical axis.
<ScriptEventPreview title={"Camera Lock To Player"} fields={[{"key":"speed","width":"50%","label":"Speed","description":"The movement speed, use 'Instant' to immediately move to the new location.","type":"moveSpeed","defaultValue":0,"allowNone":true,"noneLabel":"Instant"},{"key":"axis","width":"50%","label":"Lock Axis","description":"Set if either horizontal axis, vertical axis or both should be locked.","type":"togglebuttons","options":[["x","H","Horizontal"],["y","V","Vertical"]],"allowMultiple":true,"allowNone":false,"defaultValue":["x","y"]}]} />

- **Speed**: The movement speed, use 'Instant' to immediately move to the new location.  
- **Lock Axis**: Set if either horizontal axis, vertical axis or both should be locked.  

### Camera Move To
Move the camera to a new position.
<ScriptEventPreview title={"Camera Move To"} fields={[{"type":"group","fields":[{"key":"x","label":"X","description":"The horizontal position.","type":"value","min":0,"max":2047,"width":"50%","unitsField":"units","unitsDefault":"tiles","unitsAllowed":["tiles","pixels"],"defaultValue":{"type":"number","value":0}},{"key":"y","label":"Y","description":"The vertical position.","type":"value","min":0,"max":2047,"width":"50%","unitsField":"units","unitsDefault":"tiles","unitsAllowed":["tiles","pixels"],"defaultValue":{"type":"number","value":0}}]},{"key":"speed","label":"Speed","description":"The movement speed, use 'Instant' to immediately move to the new location.","type":"moveSpeed","defaultValue":0,"allowNone":true,"noneLabel":"Instant"}]} />

- **X**: The horizontal position.  
- **Y**: The vertical position.  
- **Speed**: The movement speed, use 'Instant' to immediately move to the new location.  

### Camera Shake
Shake the camera for a period of time.
<ScriptEventPreview title={"Camera Shake"} fields={[{"type":"group","fields":[{"key":"time","type":"number","label":"Duration","description":"The length of time to shake camera for in seconds or frames.","min":0,"max":60,"step":0.1,"defaultValue":0.5,"unitsField":"units","unitsDefault":"time","unitsAllowed":["time","frames"],"conditions":[{"key":"units","ne":"frames"}]},{"key":"frames","label":"Duration","description":"The length of time to shake camera for in seconds or frames.","type":"number","min":0,"max":3600,"width":"50%","defaultValue":30,"unitsField":"units","unitsDefault":"time","unitsAllowed":["time","frames"],"conditions":[{"key":"units","eq":"frames"}]},{"key":"shakeDirection","label":"Movement Type","description":"Choose if camera should shake only in horizontal or vertical axis or if should shake in both directions.","hideLabel":true,"type":"moveType","defaultValue":"horizontal","flexBasis":30,"flexGrow":0,"alignBottom":true}]},{"key":"magnitude","label":"Magnitude","description":"The amount of camera movement during a camera shake.","type":"value","min":1,"max":255,"defaultValue":{"type":"number","value":5}}]} />

- **Duration**: The length of time to shake camera for in seconds or frames.  
- **Movement Type**: Choose if camera should shake only in horizontal or vertical axis or if should shake in both directions.  
- **Magnitude**: The amount of camera movement during a camera shake.  

### Set Camera Position
Move the camera to a new position.
<ScriptEventPreview title={"Set Camera Position"} fields={[{"type":"group","fields":[{"key":"x","label":"X","description":"The horizontal position.","type":"value","min":0,"max":2047,"width":"50%","unitsField":"units","unitsDefault":"tiles","unitsAllowed":["tiles","pixels"],"defaultValue":{"type":"number","value":0}},{"key":"y","label":"Y","description":"The vertical position.","type":"value","min":0,"max":2047,"width":"50%","unitsField":"units","unitsDefault":"tiles","unitsAllowed":["tiles","pixels"],"defaultValue":{"type":"number","value":0}}]}]} />

- **X**: The horizontal position.  
- **Y**: The vertical position.  

## Screen
### Fade Screen In
Fade the scene from a blank screen.
<ScriptEventPreview title={"Fade Screen In"} fields={[{"key":"speed","label":"Speed","description":"The speed of the fade animation.","type":"fadeSpeed","defaultValue":"2"}]} />

- **Speed**: The speed of the fade animation.  

### Fade Screen Out
Fade the scene to a blank screen.
<ScriptEventPreview title={"Fade Screen Out"} fields={[{"key":"speed","label":"Speed","description":"The speed of the fade animation.","type":"fadeSpeed","defaultValue":"2"}]} />

- **Speed**: The speed of the fade animation.  

