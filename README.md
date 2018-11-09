## Odin assimp bindings for 4.1.0

## Usage
 * Clone: https://github.com/assimp/assimp
 * Build the x64 Visual Studio project
   - Cmake: cmake -G”Visual Studio 15 Win64"
 * Place `assimp-vc140-mt.lib` next to `assimp.odin`
 * Place the DLL next to your executable

##Notes:
 * These bindings are incomplete right now, and I have only tested the `import_file` and `release_import` functions.
 * Some of the types may not be right
