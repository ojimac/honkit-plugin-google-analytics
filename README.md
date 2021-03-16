# Google Analytics Hook for Honkit

Adds a standard `UA-XXXXXXXX-Y` analytics hook for google analytics to your header.

## Install

```sh
npm install honkit-plugin-google-analytics --save-dev
```

## Usage

Add it to your `book.json` with this configuration...

```json
{
    "plugins": ["honkit-plugin-google-analytics"],
    "pluginsConfig": {
        "analytics": {
            "uid": "UA-XXXXXXXX-Y"
        }
    }
}
```
