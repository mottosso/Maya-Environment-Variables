Output from `maya.api.OpenMaya.MEventMessage.getEventNames()`, as of Maya 2015

For a description of events, see https://help.autodesk.com/cloudhelp/2020/ENU/Maya-Tech-Docs/CommandsPython/scriptJob.html

```bash
linearUnitChanged
timeUnitChanged
angularUnitChanged
Undo
undoSupressed
Redo
timeChanged
currentContainerChange
quitApplication
idleHigh
idle
RecentCommandChanged
ToolChanged
PostToolChanged
ToolDirtyChanged
DisplayRGBColorChanged
animLayerRebuild
animLayerRefresh
animLayerAnimationChanged
animLayerLockChanged
animLayerBaseLockChanged
animLayerGhostChanged
cameraChange
cameraDisplayAttributesChange
SelectionChanged
LiveListChanged
ActiveViewChanged
SelectModeChanged
SelectTypeChanged
SelectPreferenceChanged
DisplayPreferenceChanged
DagObjectCreated
renderLayerManagerChange
renderLayerChange
displayLayerManagerChange
displayLayerAdded
displayLayerDeleted
displayLayerVisibilityChanged
displayLayerChange
renderPassChange
renderPassSetChange
renderPassSetMembershipChange
passContributionMapChange
DisplayColorChanged
lightLinkingChanged
lightLinkingChangedNonSG
UvTileProxyDirtyChangeTrigger
polyTopoSymmetryValidChanged
SceneSegmentChanged
PostSceneSegmentChanged
SequencerActiveShotChanged
ColorIndexChanged
deleteAll
NameChanged
symmetricModellingOptionsChanged
softSelectOptionsChanged
SetModified
linearToleranceChanged
angularToleranceChanged
nurbsToPolygonsPrefsChanged
nurbsCurveRebuildPrefsChanged
constructionHistoryChanged
threadCountChanged
SceneSaved
NewSceneOpened
SceneOpened
SceneImported
PreFileNewOrOpened
PostSceneRead
workspaceChanged
selectionConstraintsChanged
startColorPerVertexTool
stopColorPerVertexTool
start3dPaintTool
stop3dPaintTool
DragRelease
ModelPanelSetFocus
modelEditorChanged
MenuModeChanged
gridDisplayChanged
interactionStyleChanged
axisAtOriginChanged
CurveRGBColorChanged
SelectPriorityChanged
snapModeChanged
nurbsToSubdivPrefsChanged
ChannelBoxLabelSelected
selectionPipelineChanged
playbackRangeChanged
playbackRangeSliderChanged
currentSoundNodeChanged
glFrameTrigger
RebuildUIValues
```

Descriptions, as of Maya 2020.

| Event | Description
|:------|:----------------
| `angularToleranceChanged` | when the tolerance on angular units is changed. This tolerance can be changed by | using the MEL command, "tolerance" with the "-angular" flag changing the pref under Options->GeneralPreferences-> Modeling tab->Tangential Tolerance
| `angularUnitChanged` | when the user changes the angular unit.
| `axisAtOriginChanged` | when the axis changes at the origin.
| `axisInViewChanged` | when the axis changes at a particular view.
| `ColorIndexChanged` | when the color index values change.
| `constructionHistoryChanged` | when construction history is turned on or off.
| `currentContainerChanged` | when the user set or unset the current container.
| `currentSoundNodeChanged` | whenever the sound displayed in the time slider changes due to | the sound being removed (or no longer displayed) [RMB in the time slider] a new sound being displayed [RMB in the time slider] sound display being toggled [animation options] sound display mode being changed [animation options]
| `DagObjectCreated` | when a new DAG object is created.
| `deleteAll` | when a file new occurs
| `DisplayColorChanged` | when the display color changes.
| `displayLayerChange` | when a layer has been created or destroyed.
| `displayLayerManagerChange` | when the display layer manager has changed.
| `DisplayRGBColorChanged` | when the RGB display color changes.
| `glFrameTrigger` | for internal use only.
| `ChannelBoxLabelSelected` | when Channel Box label(first column) selection changes.
| `gridDisplayChanged` | for internal use only.
| `idle` | when Maya is idle and there are no high priority idle tasks
| `idleHigh` | when Maya is idle. This is called before low priority idle tasks. You should almost always use "idle" instead.
| `lightLinkingChanged` | when any change occurs which modifies light linking relationships.
| `lightLinkingChangedNonSG` | when any change occurs which modifies light linking relationships, except when the change is a change of shading assignment.
| `linearToleranceChanged` | when the linear tolerance has been changed. This tolerance can be changed by | using the MEL command, "tolerance" with the "-linear" flag changing the pref under Options->GeneralPreferences-> Modeling tab->Positional Tolerance
| `linearUnitChanged` | when the user changes the linear unit through the Options menu.
| `MenuModeChanged` | when the user changes the menu set for the menu bar in the main Maya window (for example, from "Modeling" to "Animation").
| `RecentCommandChanged` | for internal use only.
| `NewSceneOpened` | when a new scene has been opened.
| `PostSceneRead` | after a scene has been read. Specifically after a file open, import or all child references have been read.
| `nurbsToPolygonsPrefsChanged` | when any of the nurbs-to-polygons prefs have changed. These prefs can be changed by | using the Mel command, "nurbsToPolygonsPref" changing the prefs under Polygons->Nurbs To Polygons->Option Box
| `playbackRangeChanged` | when the playback keyframe range changes.
| `playbackRangeSliderChanged` | when the animation start/end range (i.e. the leftmost or rightmost entry cells in the time slider range, the inner ones adjust the playback range) change
| `preferredRendererChanged` | when the preferred renderer changes.
| `quitApplication` | when the user has chosen to quit, either through the quit MEL command, or through the Exit menu item.
| `Redo` | when user has selected redo from the menu and there was something to redo. This callback can be used for updating UI or local storage. Do not change the state of the scene or DG during this callback.
| `renderLayerChange` | when creation or deletion of a render layer node has occured.
| `renderLayerManagerChange` | when the current render layer has changed.
| `RebuildUIValues` | for internal use only.
| `SceneOpened` | when a scene has been opened.
| `SceneSaved` | when a scene has been saved.
| `SelectionChanged` | when a new selection is made.
| `SelectModeChanged` | when the selection mode changes.
| `SelectPreferenceChanged` | for internal use only.
| `SelectPriorityChanged` | when the selection priority changes.
| `SelectTypeChanged` | when the selection type changes.
| `setEditorChanged` | obsolete. No longer used.
| `SetModified` | when the set command is used to modify a set
| `SequencerActiveShotChanged` | when the active sequencer shot is changed.
| `snapModeChanged` | when the snap mode changes. E.g. changes to grid snapping.
| `timeChanged` | when the time changes.
| `timeUnitChanged` | when the user changes the time unit.
| `ToolChanged` | when the user changes the tool/context.
| `PostToolChanged` | after the user changes the tool/context.
| `NameChanged` | when the user changes the name of an object with the rename command.
| `Undo` | when user has selected undo from the menu and there was something to undo. This callback can be used for updating UI or local storage. Do not change the state of the scene or DG during this callback.
| `modelEditorChanged` | when the user changes the options of a model editor.
| `colorMgtEnabledChanged` | when the global per-scene color management enabled flag changes.
| `colorMgtConfigFileEnableChanged` | when the global per-scene color management OCIO configuration enabled flag changes.
| `colorMgtPrefsViewTransformChanged` | when the global per-scene color management view transform preferences transform changes.
| `colorMgtWorkingSpaceChanged` | when the global per-scene color management working space changes.
| `colorMgtConfigFilePathChanged` | when the global per-scene color management OCIO configuration file path changes.
| `colorMgtConfigChanged` | when the color management mode changes from native to OCIO, or when a different OCIO configuration is loaded.
| `colorMgtPrefsReloaded` | when all the global per-scene color management settings are reloaded.
| `colorMgtUserPrefsChanged` | when any user-level color management preference has changed.
| `colorMgtOutputChanged` | when the color management transform, or its enabled state, has changed.
| `colorMgtOCIORulesChanged` | when the type of rules in OCIO mode has changed.
| `colorMgtRefreshed` | when the color management is refreshed to trap environment variable changes.
| `metadataVisualStatusChanged` | for internal use only.
| `shapeEditorTreeviewSelectionChanged` | when a new selection in shape editor's treeview is made .
| `RenderViewCameraChanged` | when the Render View's current camera is changed.
| `tabletModeChanged` | Windows only: if your device is a Tablet PC, then the convertible mode has changed. You can use command about -tabletMode to query if your device is currently running in tablet or laptop (keyboard attached) mode.
