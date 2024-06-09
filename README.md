# Perl Web Test

## How to use this repo
1. Open repository into [Visual Studio Code for the Web](https://code.visualstudio.com/docs/editor/vscode-web) (in a Chrome browser, Safari does not seem to work).

2. Ensure the `ktock.container-wasm` extension is installed (it should be !).

3. Open the `Command Pallet` in VS Code and run the `Run Container On Browser` command. The container will launched the terminal (be patient it will take a minute).
    - (if the terminal does not open/work, you may need to add `?vscode-coi=on` query manually at the end of the URL)

4. The terminal will open in the root directory (`/`). Change directories to `/workspace` (`cd workspace`) to be in the same directory as VS Code's file explorer.

5. To run a Perl program
- `perl ./hello_world.pl`

6. When ready to commit your code back to GitHub, use the `Source Control` button in the Activity Bar on the left hand side.