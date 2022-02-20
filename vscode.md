
## vs code :keyboard shortcut when the Explorer sidebar is active
# create new file 
=================
go to keyborad shortcut json in vs code [ (ctr + shft +p) & search for (keyboard shortcut json)

#add the following :


`   {
		"key": "ctrl+down",
		"command": "explorer.newFile",
		"when": "explorerViewletFocus"
	},
    {
		"key": "ctrl+right",
		"command": "explorer.newFolder",
		"when": "explorerViewletFocus"
	}
 `
 
