Android Studio Issue https://issuetracker.google.com/issues/218370114

Setup a new project and move the AndroidManifest.xml to a custom location and specify it in build.gradle with manifest.srcFile
(example project to reproduce with available at https://github.com/kevinslashslash/TestManifestSrc )
Open project in Android Studio Chipmunk or Dolphin and observe that the source files reprot "Java file outside of source root" and full IDE functionality is not available in the files
Build/deploy works fine
Android Studio Bumblebee works fine
Remove the manifest.srcFile line and the "Java file outside of source root" issue is resolved

