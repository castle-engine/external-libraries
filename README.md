# External Libraries used by Castle Game Engine

*These are obsolete now*. The current libraries have been moved to castle_game_engine/tools/build-tool/data/external_libraries/ directory, part of Castle Game Engine SVN/GIT repos.

This repository contains various precompiled libraries used by the Castle Game Engine http://castle-engine.sourceforge.net/engine.php .

They are especially useful on Windows, where searching (or compiling yourself) these DLL files would be quite bothersome. On Linux and Mac OS X, these libraries are usually trivial to install using a package manager. The README files inside each subdirectory should specify the exact sources of each file.

You can manually copy these libraries to your projects (or to some directory listed on $PATH, this way they are visible by all projects).

You can also use our build tool https://sourceforge.net/p/castle-engine/wiki/Build%20tool/ to package your projects for Windows. In this case, you should define an environment variable $CASTLE_ENGINE_PATH pointing to the directory that has "external_libraries/" or "external-libraries/" subdirectory (for example, a clone of this repo) and then the build tool will automatically copy the necessary DLL files when packaging a Windows project.
