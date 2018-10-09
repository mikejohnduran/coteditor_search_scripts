# CotEditor Search Scripts

## ripgreg Search

This script allows you to do a grep search in the folder of the file you're currently working on. It utilizes 'ripgrep' by BurntSushi, to provide a significantly faster search time. The files are listed in the terminal with 'fzf' and the pathname for the search results are extracted with 'Path Extractor'. Everything is already properly integrated, so once you find the file you'd like to open in CotEditor, you simply press enter and a new window or tab will open in CotEditor with the selected file. The following must be installed first -- 

 
```
brew install fzf
go get github.com/edi9999/path-extractor/path-extractor
brew install ripgrep
```

The limitation of the script right now is that it doesn't allow you to do a massive search-and-replace. Otherwise, it is a great way to do a grep search faster than what most editors currently offer without having to manually choose the directory of the file. If you're interested in a script that accomplishes a similar task, check out [PathPicker by Facebook](http://facebook.github.io/PathPicker/). 

## Package Repository

This script checks the file extension of the file you're working on and opens in your default browser the homepage for the most popular package manager. For instance, if you're working on a JavaScript file, it'll open the NPM homepage. RubyGems for Ruby. 

## Documentation in Browser

Opens the main documentation page in your default browser based on the file extension you're working on.

## Links

* [ripgreg](https://github.com/BurntSushi/ripgrep)
* [fzf](https://github.com/junegunn/fzf)
* [path-extractor](https://github.com/edi9999/path-extractor)


## Credit

* 1024jp for CotEditor
* junegunn for fzf
* edi999 for path-extractor
* BurntSushi for ripgrep

