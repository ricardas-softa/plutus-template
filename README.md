# Plutus project template
It uses plutus-apps, so you must be in a nix-shell environment from plutus-apps.

## How to start?
1. Clone this repository
2. Go to plutus-apps directory and run `nix-shell`
3. Go to plutus-template directory and run `cabal build`

## Important!
- To use haskell-language-server in your VSCode or other text editor, you must run the editor in a nix-shell environment from plutus-apps.
- First time you run the editor, it will ask you to install some extensions. You must install them.
- It might take a while for the process to finish in the backround for the first time.
- You can see the logs in the Output tab in VSCode by selecting Haskell (plutus-template).
