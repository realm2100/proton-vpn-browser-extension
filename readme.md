# Fetch upstream and merge

```
git fetch upstream
git rebase upstream/main
git push origin main --force-with-lease
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
