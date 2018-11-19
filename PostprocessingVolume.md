
## Post Processing Volumes

&&ADD IMAGE&&

Post processing volumes allow to specify different effect settings for different areas, e.g. Inside a building and outside of it or a different visual mood around a graveyard etc. 




For this you've got post processing volumes
Add an empty GameObject to your scene, add the PostProcessing Volume script and a collider of your choice to it. It will be the area of effect. Pro tip: you can add multiple colliers as children to your volume. 
The profile assigned to the volume is only applied when the camera is inside of the pp volume and has a Cat Post Processing Manager. Be aware that Post Processing Volumes with a higher `Importance` value and the profile set in the post processing manager can overwrite some or all settings.
