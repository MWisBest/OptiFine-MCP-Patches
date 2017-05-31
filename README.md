# OptiFine-MCP-Patches
Patches for MCP to decompile a jar with OptiFine properly.

# How-To
1. (Recommended) Do a clean decompile of vanilla Minecraft with MCP. Ensure it worked correctly, then delete the src/ and temp/ folders in MCP.
2. Copy the .patch files here for the version you're using to the "conf/patches/minecraft_ff" folder in MCP, overwriting any existing files.
3. Extract the OptiFine jar somewhere. Copy its contents, minus the "optifine" and "META-INF" folders, into the Minecraft jar in MCP's jars folder. Also delete the META-INF folder in the Minecraft jar.
4. Decompile again. MCP should warn you that it detected a modified jar; if it doesn't, you probably did step 3 wrong.
