# Reproduction for [mrmlnc/vscode-scss#152](https://github.com/mrmlnc/vscode-scss/issues/152)

1. Setup

   ```sh
   # Clone this repository
   git clone https://github.com/loilo/repro-scss-intellisense-private-members.git
   
   # cd into the cloned folder
   cd repro-scss-intellisense-private-members
   ```

2. Open `main.scss` in VS Code.
3. Try to autocomplete variables from the `util` module. Private variables will be included in suggestions.