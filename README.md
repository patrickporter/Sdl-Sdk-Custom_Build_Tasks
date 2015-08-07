# Sdl-Sdk-Custom_Build_Tasks
.targets files that can be referenced from a Trados plugin project in Visual Studio to customize the build process

ManifestCompress.targets is a temporary fix to add the maxversion attribute to the manifest file inside the .sdlplugin file.  As of the date of this commit there is a problem with the SDL SDK which prevents the maxversion from being updated and packages. This task fixes it until the SDK is fixed.

ManifestUpdateFile.targets and ReferencesCopy.targets can be used to build a single plugin project for all versions of Trados Studio by selecting custom build configurations from the drop-down in the Visual Studio IDE. For more info check out:
 http://www.linguisticproductions.com/target-all-versions-of-trados-studio-with-a-single-plugin-project
