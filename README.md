# Google SignIn Package

This repository makes it possible to use [google-signin-for-unity](https://github.com/googlesamples/google-signin-unity) with Unity Package Manager (UPM)

## Installation

### Install via Git URL

- Add following dependency to `Packages/manifest.json` in your project;

  ```json
  {
    "dependencies": {
      "com.google.external-dependency-manager": "1.2.160",
      "com.google-signin.unity": "https://github.com/unfilet/google-signin-unity.git#1.0.5"
    },
    "scopedRegistries": [
    {
      "name": "Game Package Registry by Google",
      "url": "https://unityregistry-pa.googleapis.com",
      "scopes": [
        "com.google"
      ]
    }
    ]
  }
  ```

> For the official plugin, check out the [original repository](https://github.com/googlesamples/google-signin-unity)
