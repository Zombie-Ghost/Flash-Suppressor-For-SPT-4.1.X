# Flash Suppressor

A BepInEx 5 plugin for SPT 4.1.6 that adjusts muzzle flash lighting and firing smoke.

## Build and install

Build `FlashSuppressor.csproj` with the .NET Framework 4.7.2 targeting pack installed. The project uses `D:\Escape From Tarkov SPT 4.1.6` by default and copies `FlashSuppressor.dll` to `BepInEx\plugins\FlashSuppressor` after a successful build.

To use a different SPT installation, pass its root directory as the `GameDir` MSBuild property.

## Configuration

The plugin configuration is generated under `BepInEx\config` on first launch. It controls muzzle flash disabling, muzzle light intensity, barrel smoke intensity, and residual smoke intensity.
