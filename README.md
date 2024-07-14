Begin by cloning the repository `git clone https://github.com/Ryntak94/vs-code-go-lsp-extension`
Then, run the following commands:
`cd vs-code-go-lsp-extension`
`git submodule init` this will connect the two submodules to their remote repositories
`git submodule update` this will fetch/checkout the main branches.

To run the extension, open up `run-go-lsp` in vscode (if you don't open it as the root directory, you may run into issues) and press `F5` or open the command pallete and run `Start Debugging` or open the debugging panel and plus play. Regardless of how you choose to do this, the debugger needs to be pointed at `Run Extension`

then open a `*.go` file. In the _current_ state you will see a bunch of 1's printed to the console inside of the Output window when you have the `activateFunc` output selected.
