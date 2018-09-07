
# Live XR Editor 

An XR editor that enables you to see the changes as you edit the file.

## Running

```
git clone https://github.com/chrislatorres/live-XR-editor.git 
cd live-XR-editor 
npm install .
npm run sync
```

The in-app browser goes to <a href="http://localhost:3000">localhost:3000</a> where the monaco-editor is being hosted by browser-sync.


### TODO:
- enable "reality tab" functionality
- allow opening and saving from monaco-editor ( can use fs? ) ( outside tab changes based on which file is being edited currently )
- enable reloading of outside tab upon saving edited file
- fix performance ( buffering probably )

## License

MIT
