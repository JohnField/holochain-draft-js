# holochain-draft-js

This is a learning attempt at deploying a modern JS app as a Holochain app.
Was made curious by seeing the [Developer docs](https://developer.holochain.org/HoloWorld_Tutorial_Writing_Functions) recommend a transpiler as HC copies the app into a VM sandbox.

I've combined a rich text editor from [Draft JS](https://github.com/facebook/draft-js) and my [HoloWorld](https://github.com/JohnField/holochain-holoworld)

Holochain apps are of course peer-to-peer; the app runs in a browser that `hcdev` serves from `ui` directory.

So, `ui` contains the entire draft-js React app. Use the editor as normal; press Write and Read to stoare and fetch to the chain as per the tutorial.