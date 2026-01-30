# Zygisk-Il2CppDumper Update Fork (CODM CFL MLBB)
Il2CppDumper with Zygisk, dump il2cpp data at runtime, can bypass protection, encryption and obfuscation.

For mlbb add ":UnityKillsMe"
For codm and CFL as is!!!!
nigas in paresan

## How to use
1. Install magisk and enable Zygisk
2. Build module
   - GitHub Actions
      1. Fork this repo
      2. Go to the **Actions** tab in your forked repo
      3. In the left sidebar, click the **Build** workflow.
      4. Above the list of workflow runs, select **Run workflow**
      5. Input the game package name and click **Run workflow**
      6. Wait for the action to complete and download the artifact
3. Install module in Magisk
4. Start the game, `dump.cs` will be generated in the `/data/data/GamePackageName/files/` directory
