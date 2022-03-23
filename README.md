<h1 align="center">
TypeScript: Basics Course Seed
</h1>

## tsc

The `tsc` command runs the TypeScript compiler, converting .ts files into .js files with the appropriate TypeScript rules applied.

## tsc --init

The `tsc --init` files creates a tsconfig.json file, where configurations for the TypeScript compiler can be made.

## outDir

An `outDir` property can be added to the tsconfig.json file, and will be used by the compiler to know which directory to send the newly-generated JavaScript files to.

An explicit `tsc --outDir yourDirName/Here` command will specify where to send the new JavaScript files on this one run.

## tsc -w

This watches for any changes within .ts files, and applies them to their .js counterparts as you save your changes. This will also watch for new .ts files.