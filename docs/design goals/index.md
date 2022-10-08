Title: Design Goals

# Design Goals
The goal of the RenderWagon Rendering API for Minecraft is to provide a compatibility layer between content creation mods, and different rendering engines.
To achieve this different sections of the API have different design goals.

## Compatibility
The primary goal of the API is to provide a compatibility layer between content creation mods, and different rendering engines.
This means that the API should be as simple as possible, and should not require any knowledge of the underlying rendering engine.
This also means that the API should not be tied to any specific rendering engine, and should be able to support multiple rendering engines.

## Performance
The API should be as performant as possible, and should not introduce any performance overhead.
However, under certain conditions it might be too restricting on content creation to focus only on performance, as such performance is a primary goal, but if it interferes with the usability of the API