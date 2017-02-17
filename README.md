# sonus-electron-boilerplate
Example of [Sonus] running in electron for OSX and Linux

## Unix Dependencies

1. Clone Repo
2. Install (and keep native electron cache away from your normal cache)
```
HOME=~/.electron-gyp npm install
```
3. Add your Google Cloud Speech `keyfile.json` to the root
4. Run `npm start`
4. Say "Sonus" and then whatever you want

## Known issues
As noted in Kitt-AI/snowboy#126, there are issues finding `cblas_sdot`. The fix mentioned there has not been tested in this repo yet.