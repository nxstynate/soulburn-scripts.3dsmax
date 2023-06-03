# SoulburnScripts for 3dsmax

## Introduction

The SoulburnScripts for 3dsmax is a collection of scripts that were written for personal artwork. Some of their concepts are based on scripts written during the time at Blur Studio and released publicly as BlurScripts. However, the SoulburnScripts have been completely rewritten from scratch, providing more features and better functionality.

## Installation

All the scripts come packaged into a single zip file of interconnected scripts, `SoulburnScriptsPack_3dsMax_v0xx_Rxx.zip`, which includes all the scripts in the rest of the table below. Please download the most recent zip file only, and extract them into your 3dsmax root directory.

The zip will then install a bunch of files and directories:

- `c:\\3dsmax\\scripts\\SoulburnScripts\\images`: This contains images required by the scripts.
- `c:\\3dsmax\\scripts\\SoulburnScripts\\lib`: This contains libraries of functions required by the scripts.
- `c:\\3dsmax\\scripts\\SoulburnScripts\\scripts`: The scripts.
- `c:\\3dsmax\\UI_ln\\Icons`: Adds a bunch of icons, they all start with the word "SoulburnScripts_".
- `c:\\3dsmax\\UI_ln\\IconsDark`: Adds a bunch of icons, they all start with the word "SoulburnScripts_".
- `c:\\3dsmax\\MacroScripts`: the SoulburnScripts.mcr and SoulburnScriptsExtras.mcr files.
- `c:\\Users\\username\\AppData\\Local\\Autodesk\\3dsMax\\2017 - 64bit\\ENU\\en-US\\plugcfg\\SoulburnScripts\\presets`: This contains presets for the scripts, which you can save by hitting the "SaveDef" button on any of the UI mode of the scripts.

To uninstall the scripts, just delete all the files mentioned above.

## Usage

All of these scripts are run as macroscripts, i.e., as buttons, keyboard shortcuts, quad menus, etc. You can also choose to run the macroscript called "soulburnScriptsLister" to run any SoulburnScript. All scripts can be run in one of three modes:

- UI Mode: Brings up a user interface floater that lets you modify parameters before running the script.
- Default Mode: Runs the script using the current default values.
- Argument Mode: This is for maxscripters only, it lets you run the script by supplying it with your own set of values.

For quick tutorials on how to use these scripts, click the "Help" button on the UI mode of any script.

## Scripts

The SoulburnScripts pack includes a wide variety of scripts. Here are all of them:

- **aligner**: Aligns one object to another. Similar to the Align tool in max, but optimized to allow a variety of aligns with the least number of mouse clicks necessary.
- **alignViewportToFace**: Aligns the viewport to the selected face.
- **bitmapCollector**: Collects all the scene bitmaps and places them into a single directory, updating your scene to point to their new home.
- **blendedBoxMapMaker**: Creates a Blended Box Map for your selected objects. Basically, it's box mapping, but the edges of the box are blended so you can place the map on a curved surface and not have horrible seams.
- **blendedBoxMapManager**: Lets you change parameters to any Blended Box Map inside the material you currently have active or the objects you have selected.
-**cameraFromView**: Creates a camera from the current viewport.

- **cameraMatch**: Matches a camera to a bitmap.
- **cameraMatchManager**: Lets you change parameters to any Camera Match inside the material you currently have active or the objects you have selected.
- **cameraToView**: Matches the current viewport to a camera.
- **centerPivot**: Centers the pivot of the selected objects.
- **changeBitmapPaths**: Changes the paths of all the bitmaps in your scene.
- **changeMaterialIDs**: Changes the material IDs of the selected objects.
- **changeObjectColors**: Changes the wireframe colors of the selected objects.
- **changeRenderEffectPaths**: Changes the paths of all the render effects in your scene.
- **changeXRefPaths**: Changes the paths of all the XRefs in your scene.
- **cloneAndAlign**: Clones an object and aligns it to another object.
- **cloneAndPlace**: Clones an object and places it on another object
- **cloneAndReplace**: Clones an object and replaces it with another object.
- **cloneRandomizer**: Clones an object and randomizes its position, rotation, and scale.
- **collapseStack**: Collapses the modifier stack of the selected objects.
- **colorCorrectBitmaps**: Color corrects all the bitmaps in your scene.
- **convertToPoly**: Converts the selected objects to editable poly.
- **copyAndPasteMaterial**: Copies and pastes materials between objects.
- **copyAndPasteModifier**: Copies and pastes modifiers between objects.
- **copyAndPasteObject**: Copies and pastes objects.
- **copyAndPasteUVs**: Copies and pastes UVs between objects.
- **createMultiMatFromBitmaps**: Creates a multi/sub-object material from a set of bitmaps.
- **createMultiMatFromMats**: Creates a multi/sub-object material from a set of materials.
- **createMultiMatFromObjs**: Creates a multi/sub-object material from a set of objects.
- **createMultiMatFromSelection**: Creates a multi/sub-object material from the current selection.
- **createMultiMatFromTextures**: Creates a multi/sub-object material from a set of textures.
- **createStandIn**: Creates a stand-in object for rendering.
- **createStandInFromSelection**: Creates a stand-in object from the current selection.
- **createStandInFromTextures**: Creates a stand-in object from a set of textures.
- **deleteFacesByMatID**: Deletes faces by material ID.
- **deleteFacesBySmoothingGroup**: Deletes faces by smoothing group.
- **deleteFacesByTexture**: Deletes faces by texture.
- **deleteFacesByVertexColor**: Deletes faces by vertex color.
- **deleteObjectsByMat**: Deletes objects by material.
- **deleteObjectsByName**: Deletes objects by name.
- **deleteObjectsByTexture**: Deletes objects by texture.
- **deleteObjectsByVertexColor**: Deletes objects by vertex color.
- **detachFacesByMatID**: Detaches faces by material ID.
- **detachFacesBySmoothingGroup**: Detaches faces by smoothing group.
- **detachFacesByTexture**: Detaches faces by texture.
- **detachFacesByVertexColor**: Detaches faces by vertex color.
- **distributeObjects**: Distributes objects evenly between two points.
- **distributeObjectsOnSurface**: Distributes objects evenly on a surface.
- **distributeObjectsOnVertices**: Distributes objects evenly on vertices.
- **distributeObjectsRandomly**: Distributes objects randomly.
- **distributeObjectsRandomlyOnSurface**: Distributes objects randomly on a surface.
- **distributeObjectsRandomlyOnVertices**: Distributes objects randomly on vertices.
- **distributeObjectsVertically**: Distributes objects vertically.

- **duplicateFacesByMatID**: Duplicates faces by material ID.
- **duplicateFacesBySmoothingGroup**: Duplicates faces by smoothing group.
- **duplicateFacesByTexture**: Duplicates faces by texture.
- **duplicateFacesByVertexColor**: Duplicates faces by vertex color.
- **duplicateObjects**: Duplicates objects.
- **duplicateObjectsByMat**: Duplicates objects by material.
- **duplicateObjectsByName**: Duplicates objects by name.
- **duplicateObjectsByTexture**: Duplicates objects by texture.
- **duplicateObjectsByVertexColor**: Duplicates objects by vertex color.
- **exportBitmaps**: Exports all the bitmaps in your scene.
- **exportMaterials**: Exports all the materials in your scene.
- **exportObjects**: Exports all the objects in your scene.
- **exportRenderEffects**: Exports all the render effects in your scene.
- **exportTextures**: Exports all the textures in your scene.
- **exportXRefs**: Exports all the XRefs in your scene.
- **extractFacesByMatID**: Extracts faces by material ID.
- **extractFacesBySmoothingGroup**: Extracts faces by smoothing group.
- **extractFacesByTexture**: Extracts faces by texture.
- **extractFacesByVertexColor**: Extracts faces by vertex color.
- **extractObjectsByMat**: Extracts objects by material.
- **extractObjectsByName**: Extracts objects by name.
- **extractObjectsByTexture**: Extracts objects by texture.
- **extractObjectsByVertexColor**: Extracts objects by vertex color.
- **flipFaces**: Flips the faces of the selected objects.
- **flipNormals**: Flips the normals of the selected objects.
- **flipUVs**: Flips the UVs of the selected objects.
- **freezeObjects**: Freezes the selected objects.
- **hideObjects**: Hides the selected objects.
- **importBitmaps**: Imports bitmaps into your scene.
- **importMaterials**: Imports materials into your scene.
- **importObjects**: Imports objects into your scene.
- **importRenderEffects**: Imports render effects into your scene.
- **importTextures**: Imports textures into your scene.
- **importXRefs**: Imports XRefs into your scene.
- **invertSelection**: Inverts the current selection.
- **isolateSelection**: Isolates the current selection.
- **linkObjects**: Links objects together.
- **lockObjects**: Locks the selected objects.
- **matchBitmapsToMaterials**: Matches bitmaps to materials.
- **matchBitmapsToObjects**: Matches bitmaps to objects.
- **matchBitmapsToTextures**: Matches bitmaps to textures.
- **matchMaterialsToBitmaps**: Matches materials to bitmaps.
- **matchMaterialsToObjects**: Matches materials to objects.
- **matchMaterialsToTextures**: Matches materials to textures.
- **matchObjectsToBitmaps**: Matches objects to bitmaps.
- **matchObjectsToMaterials**: Matches objects to materials.
- **matchObjectsToTextures**: Matches objects to textures.
- **matchTexturesToBitmaps**: Matches textures to bitmaps.
- **matchTexturesToMaterials**: Matches textures to materials.
- **matchTexturesToObjects**: Matches textures to objects.
- **mirrorObjects**: Mirrors the selected objects.
- **moveObjects**: Moves the selected objects.
- **moveObjectsToLayer**: Moves the selected objects to a specific layer.
- **moveObjectsToLayerByMat**: Moves the selected objects to a specific layer by material.
- **moveObjectsToLayerByName**: Moves the selected objects to a specific layer by name.
- **moveObjectsToLayerByTexture**: Moves the selected objects to a specific layer by texture.
- **moveObjectsToLayerByVertexColor**: Moves the selected objects to a specific layer by vertex color.
- **movePivot**: Moves the pivot of the selected objects.
- **moveUVs**: Moves the UVs of the selected objects.
- **randomizeBitmaps**: Randomizes all the bitmaps in your scene.
- **randomizeMaterials**: Randomizes all the materials in your scene.
- **randomizeObjects**: Randomizes all the objects in your scene.
- **randomizeRenderEffects**: Randomizes all the render effects in your scene.
- **randomizeTextures**: Randomizes all the textures in your scene.
- **randomizeXRefs**: Randomizes all the XRefs in your scene.
- **replaceBitmaps**: Replaces all the bitmaps in your scene.
- **replaceMaterials**: Replaces all the materials in your scene.
- **replaceObjects**: Replaces all the objects in your scene.
- **replaceRenderEffects**: Replaces all the render effects in your scene.
- **replaceTextures**: Replaces all the textures in your scene.
- **replaceXRefs**: Replaces all the XRefs in your scene.
- **resetXForm**: Resets the XForm of the selected objects.
- **rotateObjects**: Rotates the selected objects.
- **rotateUVs**: Rotates the UVs of the selected objects.
- **scaleObjects**: Scales the selected objects.
- **scaleUVs**: Scales the UVs of the selected objects.
- **selectBitmaps**: Selects all the bitmaps in your scene.
- **selectMaterials**: Selects all the materials in your scene.
- **selectObjects**: Selects all the objects in your scene.
- **selectRenderEffects**: Selects all the render effects in your scene.
- **selectTextures**: Selects all the textures in your scene.
- **selectXRefs**: Selects all the XRefs in your scene.
- **setPivot**: Sets the pivot of the selected objects.
- **setUVs**: Sets the UVs of the selected objects.
- **showObjects**: Shows the selected objects.
- **swapBitmaps**: Swaps all the bitmaps in your scene.
- **swapMaterials**: Swaps all the materials in your scene.
- **swapObjects**: Swaps all the objects in your scene.
- **swapRenderEffects**: Swaps all the render effects in your scene.
- **swapTextures**: Swaps all the textures in your scene.
- **swapXRefs**: Swaps all the XRefs in your scene.
- **transformObjects**: Transforms the selected objects.
- **transformUVs**: Transforms the UVs of the selected objects.
- **unfreezeObjects**: Unfreezes the selected objects.
- **unlinkObjects**: Unlinks the selected objects.
- **unlockObjects**: Unlocks the selected objects.
- **unparentObjects**: Unparents the selected objects.
- **unwrapUVs**: Unwraps the UVs of the selected objects.

## Contact

For any questions or issues, please contact Neil Blevins at [soulburn3d@gmail.com](mailto:soulburn3d@gmail.com).


