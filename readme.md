# Fetch upstream and merge

```
git pull upstream main
git push origin main
```

```
git archive --format zip --output source-code.zip HEAD
```
for submitting source code to firefox addons

# Build for Firefox

```
npm install
npm run pack-ff
```
