# LINQ-SDK Sample Unity Project
Unity Sample Project for LINQ SDK UnityPackage (2022.3.29)

This project is designed to provide a unityPackage to enable Unity developers to more easily import the Linq.gg SDK found here:

https://github.com/linqgg/unity-sdk

This project currently targets .NET Standard 2.0 for Unity 2022.3.29 including compatible DLLS for gRPC, Google Protocol Buffers, NewtonSoft JSON, EDM 1.2.179 and their required dependencies.

All Linq-specific assets can be found under the following Linq subfolders:
- Assets/Linq
- Assets/Plugins/Linq
- Assets/Editor/Linq

This project also includes:
- External Dependency Manager v1.2.179
- Linq SDK
- UniWebView (used by Linq SDK) 

## Installation & Use
By using this project and/or the included unityPackage(s), you agree to all of the licenses included here-in.

To install, use the unityPackage found in the root of this project.  Current version: linq-sdk-keithAtPlay-0.0.3.unitypackage

Licenses for the included libraries are as follows:

## Project Overview

- **Unity Version**: 2022.3.29
- **Target Framework**: netstandard2.0
- **Platform Support**: Android and iOS

## Third-Party Plugins and Dependencies

This project uses several third-party plugins and dependencies, each with its respective licensing terms. Please review the licenses for each dependency to ensure compliance.

### Plugins and Dependencies

1. **Google Protocol Buffers (Google.Protobuf)**
   - **Version**: 3.19.0
   - **License**: Apache License 2.0
   - **Description**: Provides support for Protocol Buffers, Google's language-neutral, platform-neutral, extensible mechanism for serializing structured data.

2. **gRPC Core API (Grpc.Core.Api)**
   - **Version**: 2.39.1
   - **License**: Apache License 2.0
   - **Description**: Core API for gRPC, a high-performance, open-source universal RPC framework.

3. **gRPC .NET Client (Grpc.Net.Client)**
   - **Version**: 2.39.0
   - **License**: Apache License 2.0
   - **Description**: Provides client-side functionality for gRPC.

4. **gRPC .NET Client Web (Grpc.Net.Client.Web)**
   - **Version**: 2.39.0
   - **License**: Apache License 2.0
   - **Description**: Adds support for gRPC-Web, allowing gRPC to be used in environments like web browsers.

5. **gRPC .NET Common (Grpc.Net.Common)**
   - **Version**: 2.39.0
   - **License**: Apache License 2.0
   - **Description**: Contains common functionality for gRPC .NET libraries.

6. **Microsoft Extensions Logging Abstractions (Microsoft.Extensions.Logging.Abstractions)**
   - **Version**: 3.0.3
   - **License**: MIT License
   - **Description**: Provides common logging abstractions used by various Microsoft and third-party components.

7. **System.Runtime.CompilerServices.Unsafe**
   - **Version**: 4.5.3
   - **License**: MIT License
   - **Description**: Provides support for low-level memory manipulation and interop scenarios.

8. **Unity Plugins**
   - **Android Support**: Various `.aar` files located under `Assets/Plugins/Linq/Android/`.
   - **iOS Support**: Various `.a` and `.framework` files located under `Assets/Plugins/Linq/iOS/`.
