# CrashGuard Engine

**A Windows desktop utility for game integrity checks, crash analysis, and safer recovery.**

[English](README.md) · [Türkçe](README.tr.md)

CrashGuard Engine helps you discover game installations, check file integrity, make crash evidence easier to understand, and investigate mod-related problems.

## Features

- Discovers installations for Steam, Epic Games, GOG, Xbox, EA, and Ubisoft from known launcher records.
- Runs read-only, cancellable game-file integrity scans.
- Ranks Windows crash records, executable integrity results, and mod matches as evidence.
- Clearly presents severity, confidence, risk, and a verification plan.
- Requests approval and creates a recovery point before actions that change files.
- Uses a safe rollback approach when a recovery step cannot be verified.
- Includes Turkish and English interfaces.
- Verifies official Steam artwork and falls back to the CrashGuard Engine cover when an image is invalid.

## Download

Download the latest Windows 10/11 x64 build from [GitHub Releases](https://github.com/fkalsasx/CrashGuard-Engine/releases/latest).

1. Download <code>CrashGuardEngine-v1.0.0.exe</code>.
2. Verify the file against the SHA-256 value on the release page.
3. Run the executable.

The app is a standalone, single-file build and does not require a separate .NET installation.

## Safety and privacy

CrashGuard does not present missing evidence as a definitive diagnosis. Game paths, hash results, and diagnostic logs stay on your computer by default. Online research and support-package exports are started by you. You should not disable your security software.

## Recorded verification — September 23, 2026

- All 154 automated tests passed.
- The release build completed with zero errors.
- The NuGet scan found no known vulnerabilities.
- UI and packaged executable startup checks completed successfully.

See the [latest release notes](https://github.com/fkalsasx/CrashGuard-Engine/releases/latest) for current build details.

## Report a problem

Open an [Issue](https://github.com/fkalsasx/CrashGuard-Engine/issues) with the game name, steps to reproduce, expected result, and observed result. Do not include passwords, account credentials, or personal file contents.
