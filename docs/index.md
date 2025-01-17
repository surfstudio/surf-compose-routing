## Compose Routing

![picture](https://github.com/surfstudio/surf-compose-routing/blob/master/data/just-image.png?raw=true)

Interfaces that make it easier to work with navigator routing.

## Connection

![Maven metadata URL](https://img.shields.io/maven-metadata/v?metadataUrl=https%3A%2F%2Fartifactory.surfstudio.ru%2Fartifactory%2Flibs-release-local%2Fru%2Fsurfstudio%2Fcompose%2Frouting%2Fmaven-metadata.xml)

```gradle
repositories {
    maven("https://artifactory.surfstudio.ru/artifactory/libs-release-local")
}
dependencies {
    implementation("ru.surfstudio.compose:routing:${version}")
}
```

## Features:

### ![picture](https://github.com/google/material-design-icons/blob/master/png/maps/alt_route/materialicons/18dp/1x/baseline_alt_route_black_18dp.png?raw=true) NavigationDispatcher
Handles navigation stack and routes for the whole application

### ![picture](https://github.com/google/material-design-icons/blob/master/png/maps/alt_route/materialicons/18dp/1x/baseline_alt_route_black_18dp.png?raw=true) NavigationDispatcherCallback
BackPressedDispatcher with OnBackPressedCallback by compose status

## License

```
Copyright 2021 Surf LLC

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```