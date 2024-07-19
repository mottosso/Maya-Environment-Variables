All available (but undocumented) environment variables in Autodesk Maya

- EDIT: Many documented variables [here](http://help.autodesk.com/view/MAYAUL/2018/ENU/?guid=GUID-FC154DF1-CC21-4DBF-9FAC-19FDE6DCBC9A).

| Variable                                      | Description                                          | Since | To   | Source
|:----------------------------------------------|:-----------------------------------------------------|:------|:-----|:------------
| `MAYA_IGNORE_DIALOGS`                         | Suppress warnings on scene open                      | 2015  |      | 
| `MAYA_DISABLE_CLIC_IPM`                       | Cloud login utilities                                | 2016  |      | [Slow startup](https://forums.autodesk.com/t5/maya-forum/maya-2016-5-slow-start-up/td-p/6347777)
| `MAYA_DISABLE_CIP`                            | Avoid fatal crash on start-up                        | 2014  |      | [Autodesk Forum](https://forums.autodesk.com/t5/installation-licensing/maya-2015-fatal-error-crash-at-startup/td-p/5116132)
| `MAYA_DISABLE_CER`                            | Customer Error Reporting                             | 2014  |      | [Slow shutdown](http://discourse.techart.online/t/maya-reducing-maya-shutdown-time-by-disabling-autodesk-cip/4951)
| `MAYA_NO_CONSOLE_WINDOW`                      | Hide console window on start-up                      | 2014  |      | [Domemaster3D][]
| `MAYA_TEXTURED_SCULPT`                        | Enable/disable the texture sculpt deformer controls. It is off by default.                                                                                                                                  | 2014  |      | [Domemaster3D][]
| `MAYA_VR_PER_SHAPE_ATTR`                      | Control vector rendering modes per shape.                                                                                                                                                                   | 2014  |      | [Domemaster3D][]
| `MAYA_ENABLE_VP2_SHAPE_INSTANCING`            | Override the globals node hwInstancing attribute setting. By setting the variable to 1 the hardware instancing is enabled. Setting the variable to any other value with disable the hardware instancing.    | 2014  |      | [Domemaster3D][]
| `MAYA_OGS_DEVICE_OVERRIDE`                    | Can be set to "VirtualDeviceDx11" to override the Viewport 2.0 rendering engine.                                                                                                                            | 2014  |      | [Domemaster3D][]
| `MAYA_OGS_ENABLE_MAX_TEXTURE_SIZE_PREF`       | Can be set to 1 to set texture size used for viewport display (can fix some slowdown in Mac OS X).                                                                                                          | 2022  |      | [Maya documentation](https://help.autodesk.com/view/MAYAUL/2022/ENU/?guid=GUID-2CCFF304-FB52-47FE-BBCB-21D68C455929)
| `MAYA_OGS_GPU_MEMORY_LIMIT `                  | Can be set to override memory detection in Viewport 2.0 and set a lower memory limit to reserve GPU memory for an alternate 3d application (in MB).                                                         | 2022  |      | [Running multiple Maya sessions](https://help.autodesk.com/view/MAYAUL/2022/ENU/?guid=GUID-370E7A71-6570-4277-9C9E-827BEF94FF28)
| `MAYA_VP2_DEVICE_OVERRIDE`                    | Can be set to "VirtualDeviceDx11", "VirtualDeviceGLCore", or "VirtualDeviceGL"                                                                                                                              | 2014  |      | [Domemaster3D][]
| `MAYA_VP2_WANT_OGS_WARNINGS `                 | Can be set to 1 to see the viewport compile errors                                                                                                                                                          | 2022  |      | [Debugging ShaderFX network](https://help.autodesk.com/view/MAYAUL/2022/ENU/?guid=GUID-EBCA34EA-4F6F-466B-93DE-0BB72F2F772F)
| `MAYA_OFFSCREEN_HRB`                          | Control offscreen hardware rendering.                                                                                                                                                                       | 2014  |      | [Domemaster3D][]
| `MAYA_SHADER_LIBRARY_PATH`                    | Can be set to 1 to enable the control.                                                                                                                                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_PLUG_IN_RESOURCE_PATH`                  | Specifiy a language-dependent resource file when Maya is running using a localized language.                                                                                                                | 2014  |      | [Domemaster3D][]
| `MAYA_BATCH_RENDERING_STOPS_ON_ERROR`         | Allows clients to receive the error codes from the command engine when it terminates.                                                                                                                       | 2014  |      | [Domemaster3D][]
| `MAYA_TESTING_CLEANUP`                        | Will suppress user confirmation dialogs during automated testing                                                                                                                                            | 2014  |      | [Domemaster3D][]
| `MAYA_NO_INITIAL_AUTOLOAD_MT`                 | Can be used to exclude the autoloading of plugins like xgenToolkit and xgenMR that were added in Maya 2014+.                                                                                                | 2014  |      | [Domemaster3D][]
| `MAYA_CUSTOM_TEMPLATE_PATH`                   | Define the path for the Maya 2016 XML property editor templates.                                                                                                                                            | 2014  |      | [Domemaster3D][]
| `MAYA_ENABLE_LEGACY_RENDER_LAYERS`            |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_MODULE_PATH`                            |                                                      | 2014  |      | [Domemaster3D][]
| `SHARED_MAYA_DIR`                             |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_UI_LANGUAGE`                            |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_DISABLE_VP2_WHEN_POSSIBLE`              |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_ENABLE_LEGACY_PARTICLES`                |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_RUNNING_TESTS`                          |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_SCRIPT_BASE`                            |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_HELP_URL`                               |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_EXPOSE_FACADE_NODES`                    |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_ENABLE_CLASSIC_HAIR`                    |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_DISABLE_LEGACY_VIEWPORT`                |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_LICENSE_METHOD`                         |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_PSEUDOTRANS_MODE`                       |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_PROJECTS_DIR`                           |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_ADSK_ASSET_LIBS`                        |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_SCRIPT_PATH`                            |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_VP2_USE_GPU_MAX_TARGET_SIZE`            |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_QUICKTIME_ENCODING_GAMMA`               |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_REVERSE_FILEFORMAT_EXT`                 |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_ENABLE_LEGACY_RIGID`                    |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_EXR_LONGNAME`                           |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_PROJECT`                                |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_LOCATION`                               |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_ALIEN_WIDGETS`                          |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_VP2_DEFAULT_MATERIAL_LOADING_MODE`      |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_REAL_WORLD_SIZE`                        |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_BIFROST_COMPOUNDS`                      |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_PRESET_PATH`                            |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_SHELF_PATH`                             |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_DISABLE_IDLE_LICENSE`                   |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_RENDER_DESC_PATH`                       |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_BG_DEPTH_IMAGE`                         |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_FBX_PLUGIN_LOCATION`                    |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_DISABLE_LOOKDEV_MATERIAL_VIEWER`        |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_MRFM_SHOW_CUSTOM_SHADERS`               |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_PLUG_IN_PATH`                           |                                                      | 2016  |      | [Domemaster3D][]
| `MAYA_ALT_EN`                                 |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_ENABLE_LEGACY_HYPERSHADE`               |                                                      | 2016  | 2016 | [Domemaster3D][]
| `MAYA_APP_DIR`                                |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_DISABLE_LOOKDEV_PROPERTY_PANEL`         |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_LICENSE`                                |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_COLOR_MANAGEMENT_POLICY_LOCK`           |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_COLOR_MANAGEMENT_POLICY_FILE`           |                                                      | 2014  |      | [Domemaster3D][]
| `VRAY_FOR_MAYA_DRPORT`                        |                                                      | 2014  |      | [Domemaster3D][]
| `VRAY_FOR_MAYA_LOG_FILE_PATH`                 |                                                      | 2014  |      | [Domemaster3D][]
| `VRAY_FOR_MAYA_DRLISTS_PATH`                  |                                                      | 2014  |      | [Domemaster3D][]
| `VRAY_FOR_MAYA_LOG_FILE_NAME`                 |                                                      | 2014  |      | [Domemaster3D][]
| `MI_MAYA_SOCKETS`                             |                                                      | 2014  |      | [Domemaster3D][]
| `MI_MAYA_BATCH_OPTIONS`                       |                                                      | 2014  |      | [Domemaster3D][]
| `MAYA_RETAIN_PYTHON_GIL`                      | ?                                                    | 2017  |      | [ATC1][]
| `MAYA_ENABLE_LEGACY_VIEWPORT`                 | Enable Viewport 1.0                                  | 2018  |      | [RV1][]
| `MAYA_ENABLE_WEBENGINE`                       |                                                      | 2018.1|      | [#2][]  
| `MAYA_RENDER_SETUP_GLOBAL_PRESETS_PATH`       |                                                      | 2017  |      | [#1][] 

[#1]: https://github.com/mottosso/Maya-Environment-Variables/issues/1
[#2]: https://github.com/mottosso/Maya-Environment-Variables/issues/2
[Domemaster3D]: https://raw.githubusercontent.com/zicher3d-org/domemaster-stereo-shader/master/Domemaster3D%20Installer/installer%20files/Domemaster3D/maya/common/scripts/domeDiagnostics.mel
[ATC1]: http://around-the-corner.typepad.com/adn/2016/07/avoid-dg-evaluation-caused-by-mayacmds-when-there-are-python-custom-nodes-in-the-scene-in-parallel-mode.html
[RV1]: http://help.autodesk.com/view/MAYAUL/2018/ENU/?guid=GUID-4928A912-DA6C-4734-863B-AB5959DA73C9

