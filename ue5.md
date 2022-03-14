# Build the Plugin for Unreal Engine 5 Preview 2

The following steps can be used to build and use the plugin with Unreal Engine 5 Preview 2:

1. Make sure your project contains C++ code. You can add an empty C++ class from the Editor.
1. Download the Plugin from the Marketplace.
2. Move the plugin from `<Engine_Root>/Plugins/Marketplace/OneSignal` to `<Project_Root>/Plugins/OneSignal`.
3. Open the file `<Project_Root>/Plugins/OneSignal/Sources/OneSignal/OneSignal.Build.cs`.
4. Replace `#if UE_5_0_OR_LATER` with `#if 1` and save the file.
5. Open your project and choose `Yes` when asked to build the project.
