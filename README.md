# Studies on Ocornut ImGUI Demo adapted to WebAssembly
Based on @github/arcanosam studies and coding about @github/ocornut ImGUI demo in WebAssembly.

@github/arcanosam used to have a working stuff, but it wasn't present in the latest commits. It 
took some effort to get back to working version.

@github/OCTAGRAM wishes to aleady have own Objective-C compiler and GNUStep-on-Wasm port, but 
there is so much left to do on this way, and ImGUI is a way to have at least some Wasm GUI 
for now.

* [Original demo](http://sol.gfxile.net/ocornut_demo/imgui.html)
  * If you remove the imgui.html from the above URL, you could list the files on ocornut_demo path
  * There, there are the final product which is the html, mem file and js
  * But there are the source that generated the page

## Requirements
* Install [Webassembly toolchain](http://webassembly.org/getting-started/developers-guide/)

## Usage
  * Open console/prompt command
    * Run: *source __[[path to emsdk folder]]__/emsdk_env.sh*
  * Clone this repo
    * git clone --recursive https://github.com/OCTAGRAM/ImGUI_Wasm
  * Access repo folder
  * Run *./app/build.sh*
    * Don't forget permissions on build script
      * *chmod +x ./app/build.sh*
    * At end, will be generated all files on *./app/html* folder
    * Open up html file on your browser (Chrome or Firefox)
      * Both browsers must be updated for having *WebAssembly* enabled by default

