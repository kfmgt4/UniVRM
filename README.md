# UniVRM

![GitHub latest release](https://img.shields.io/github/v/release/vrm-c/UniVRM?color=green)
![GitHub license](https://img.shields.io/github/license/vrm-c/UniVRM)

The standard implementation of 3D Avatar file format [VRM](https://vrm-consortium.org/en/) for [Unity](https://unity.com/).

VRM is an extension of [glTF 2.0](https://www.khronos.org/gltf/), so this library also support glTF 2.0 files.

## Features

UniVRM supports the [VRM 1.0 specification](https://github.com/vrm-c/vrm-specification) and the [glTF 2.0 specification](https://registry.khronos.org/glTF/).

UniVRM can import/export following supported file types at both runtime and editor.

### Supported file types
- VRM 1.0 (.vrm)
- VRM 0.x (.vrm)
- glTF 2.0 (.glb | .gltf | .zip)

### Import features
- You can import supported file types at both runtime and editor.
- Support for async/await importing at runtime.
- Support for Migration VRM 0.x files into VRM 1.0 files.
- Support for ScriptedImporter for VRM 1.0 and glTF 2.0.
- You can import glTF's PBR materials into Unity Built-in RP's Standard materials.

### Export features
- You can export supported file types at both runtime and editor.
- You can export Unity Built-in RP's Standard materials into glTF's PBR materials.

## Requirements

The latest UniVRM supports Unity 2020.3 LTS or later.

## Installation

![GitHub latest release](https://img.shields.io/github/v/release/vrm-c/UniVRM?color=green)

You can install UniVRM using the UnityPackage or the UPM Package.

### UnityPackage

From the [latest release](https://github.com/vrm-c/UniVRM/releases/latest), you can download the `.unitypackage` files.

- For import/export VRM 1.0
    - You can download **VRM-0.XXX.X-YYYY.unitypackage**.
    - You can also download sample projects as **VRM_Samples-0.XXX.X-YYYY.unitypackage**.
- For import/export VRM 0.x
    - You can download **UniVRM-0.XXX.X-YYYY.unitypackage**.
    - You can also download sample projects as **UniVRM_Samples-0.XXX.X-YYYY.unitypackage**.
- For import/export glTF 2.0
    - You can download **VRM-0.XXX.X-YYYY.unitypackage**.

### UPM Package

From the [latest release](https://github.com/vrm-c/UniVRM/releases/latest), you can find UPM package urls.

- For import/export VRM 1.0
    - You have to install all of the following UPM packages.
        - `com.vrmc.vrmshaders`
        - `com.vrmc.gltf`
        - `com.vrmc.vrm`
- For import/export VRM 0.x
    - You have to install all of the following UPM packages.
        - `com.vrmc.vrmshaders`
        - `com.vrmc.gltf`
        - `com.vrmc.univrm`
- For import/export glTF 2.0
    - You have to install all of the following UPM packages.
        - `com.vrmc.vrmshaders`
        - `com.vrmc.gltf`

You can install these UPM packages via `Package Manager` -> `+` -> `Add package from git URL...` in UnityEditor.

## Documentation

- https://vrm.dev/en/vrm/index.html

### For developers

- https://vrm-c.github.io/UniVRM/en/

## License

* [MIT License](./LICENSE.txt)
