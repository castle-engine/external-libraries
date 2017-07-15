# External Libraries used by Castle Game Engine

**This repository is obsolete / deprecated!**. The current libraries have been moved to the [Castle Game Engine repository](https://github.com/castle-engine/castle-engine), they can be found there inside the `tools/build-tool/data/external_libraries/` subdirectory. [Here is the direct link to the external libraries directory](https://github.com/castle-engine/castle-engine/tree/master/tools/build-tool/data/external_libraries).

This repository contains various precompiled libraries used by the Castle Game Engine https://castle-engine.sourceforge.io/ .

They are especially useful on Windows, where searching (or compiling yourself) these DLL files would be quite bothersome. On Linux and Mac OS X, these libraries are usually trivial to install using a package manager. The README files inside each subdirectory should specify the exact sources of each file.

You can manually copy these libraries to your projects (or to some directory listed on $PATH, this way they are visible by all projects).

You can also use our build tool https://github.com/castle-engine/castle-engine/wiki/Build-Tool to package your projects. In this case, you should define an environment variable $CASTLE_ENGINE_PATH pointing to the directory that has "castle_game_engine/" or "castle-engine/" subdirectory and then the build tool will automatically copy the necessary DLL files (for appropriate platform) when packaging your project.
