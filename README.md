# Life Reincarnation Simulator Demo

A Windows demo build of a Java life-reincarnation simulator game.

## Download and Run

Download the bundled Windows package:

```text
dist/LifeReincarnationSimulatorDemo-windows-bundled.zip
```

Then:

1. Extract the zip file.
2. Open the extracted `LifeReincarnationSimulatorDemo` folder.
3. Double-click `LifeReincarnationSimulatorDemo.exe`.

This bundled package includes its own Java runtime, so you do not need to install Java separately.

## Important

Do not run only a copied `.exe` file by itself. The executable needs the bundled `runtime` and `app` folders next to it.

The old standalone exe required a local JVM and could show this error:

```text
No JVM could be found on your system.
```

Use the bundled zip package above instead.

## Repository Contents

- `LifeReincarnationSimulatorDemo.jar`: original Java application jar
- `dist/LifeReincarnationSimulatorDemo-windows-bundled.zip`: Windows package with bundled Java runtime
- `src/image`, `src/music`: application assets

## Build Notes

The bundled Windows package was created with JDK 21 `jpackage` using `App` as the main class.
