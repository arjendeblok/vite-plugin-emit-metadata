# Vite Plugin Emit Metadata

This is a Vite plugin that transpiles some of your .ts files via the TypeScript compiler instead of via ESBuild.
This can slow down the process but Vite then support the use of the emitDecoratorMetadata flag of TypeScript.

The main reason for this plugin that I wanted to use dependency injection in my SvelteKit project. 
For this I need a dependency injection framework like tsyringe that requires to use reflect metadata.


