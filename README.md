# VelocityUnsigned

This is fork of [Velocity](https://github.com/PaperMC/Velocity) that removes signed messages (that broke plugins).

A Minecraft server proxy with unparalleled server support, scalability,
and flexibility.

Velocity and VelocityUnsigned is licensed under the GPLv3 license.

## Building

Velocity is built with [Gradle](https://gradle.org). We recommend to run `./gradlew build` to run the full build cycle.

Once you've built Velocity, you can copy and run the `-all` JAR from `proxy/build/libs`.

Alternatively, you can get the proxy JAR from the [Releases](https://github.com/ygmpxwn/VelocityUnsigned/releases)
page.

## Sync Fork

You can merge new commits from `PaperMC/Velocity - dev/3.0.0` to `ygmpxwn/VelocityUnsigned - dev/3.0.0` using:
1. `git fetch upstream`
2. `git merge upstream/dev/3.0.0`

# Localisation

Translations are handled using [Crowdin](https://papermc-io.crowdin.com/velocity).
If you want to translate a language not available on Crowdin,
you might want to ask in the [Discord](https://discord.gg/papermc) about it.