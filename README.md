# stylelint-max-root-rules
Limit the count of root rules.

## Installation

1. If you haven't, install [stylelint]:

```
npm install stylelint --save-dev
```

2.  Install `stylelint-max-root-rules`:

```
npm install stylelint-max-root-rules --save-dev
```

## Usage

Add `stylelint-max-root-rules` to your stylelint config `plugins` array, then add rules you need to the rules list. All rules from stylelint-max-root-rules need to be namespaced with `pitcher`.

```json
{
    "plugins": [
        "stylelint-max-root-rules"
    ],
    "rules": {
        "pitcher/max-root-rules": 300
    }
}
```
