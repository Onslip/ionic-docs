This command creates a package build on Appflow. While the build is running, it prints the remote build log to the terminal. If the build is successful, it downloads the created app package file in the current directory. Downloading build artifacts can be skipped by supplying the flag `skip-download`.

Apart from `--commit`, every option can be specified using the full name setup within the [Dashboard](https://dashboard.ionicframework.com).

The `--signing-certificate` option is mandatory for any iOS build but not for Android debug builds.

Customizing the build:

- The `--environment` and `--native-config` options can be used to customize the groups of values exposed to the build.
- Override the preferred platform with `--build-stack`. This is useful for building older iOS apps.

Deploying the build to an App Store:

- The `--destination` option can be used to deliver the app created by the build to the configured App Store. This can be used only together with build type `release` for Android and build types `app-store` or `enterprise` for iOS.

Downloading build artifacts:

- By default once the build is complete, all artifacts are downloaded for the selected platform. `aab` and `apk` for Android `ipa` and `dsym` for iOS.
- The `--artifact-type` option can be used to limit artifact downloads to only of that type. For instance, with Android, you can specify `aab` if you do not wish to download `apk`.
