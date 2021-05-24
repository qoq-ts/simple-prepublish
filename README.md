# ts-prepublish
Run shell script before `npm publish`.

# Installation
```bash
yarn add ts-prepublish --dev
```

# Usage
Add scripts to you package.json
```json
{
    "scripts: {
        "prepublishOnly": "ts-prepublish"
    }
}
```