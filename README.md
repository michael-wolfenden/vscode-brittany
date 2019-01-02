# vscode-brittany

Format Haskell code with [brittany](https://github.com/lspitzner/brittany) in Visual Studio Code.

# Important

This extension has not been published to the Visual Studio Marketplace, I run it by copying the source to the local extensions folder. This was purely a learning excercise for me. Having said that, this extension is feature complete.

# Features 

This extension uses [brittany](https://github.com/lspitzner/brittany) to format Haskell source code. 

* To format a full-page document, open the command palette and choose "Format Document".
* To format a selection, select some text, open the command palette, and choose "Format Selection".
* To format on save, open User Preferences (⌘ , or Ctrl ,), then add: `"editor.formatOnSave": true` 

# Requirements

* [Stack](http://haskellstack.org) must be in `$PATH`.
* [brittany](https://github.com/lspitzner/brittany) must be available in the current stack project.

To add [brittany](https://github.com/lspitzner/brittany) to a stack project run `stack build brittany` (`build`, _not_ `install`!) in the stack project.

# Configuration

`brittany` can be configured via a `brittany.yaml` configuration file in the root directory of your workspace. 

