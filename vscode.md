
## vs code :keyboard shortcut when the Explorer sidebar is active
# create new file 
---
go to keyborad shortcut json in vs code [ (ctr + shft +p) & search for (keyboard shortcut json)

# add the following :

---
`{
		"key": "ctrl+down",
		"command": "explorer.newFile",
		"when": "explorerViewletFocus"
	},
{
		"key": "ctrl+right",
		"command": "explorer.newFolder",
		"when": "explorerViewletFocus"
	}`
 
---


## Add Extentsions 
1. prettier
2. ES7 react
3. brackets 
4. live server
5. Bracket Pair Colorizer


## change json setting 
## Add the following lines

`    "editor.formatOnSave": false,  
    "emmet.includeLanguages": {
        "javascript":"javascriptreact"
    },
    "emmet.syntaxProfiles": {
        "javascript":"jsx",
        "javascript":"html"
    }
`
