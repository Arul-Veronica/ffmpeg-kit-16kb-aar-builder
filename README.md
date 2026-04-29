# FFmpeg AAR Builder

This repository contains a GitHub Actions workflow that builds FFmpeg as an `.aar` (Android Archive) file, ready to integrate into any Android project.

## Compatibility

The workflow has been tested and confirmed to produce stable builds on both **16KB page size devices** and **4KB page size devices**.

## Usage

1. Navigate to the **Actions** tab in this repository
2. Select the build workflow
3. Click **Run workflow**
4. Once the build completes, download the `.aar` file from the **Artifacts** section of the workflow run

## Customizing the Build

If you need to modify the FFmpeg build configuration to suit your own requirements:

1. Fork this repository to your GitHub account
2. Open the workflow file located at `.github/workflows/`
3. Adjust the build flags, codecs, or any other configuration as needed
4. Commit your changes — GitHub Actions will trigger a new build automatically
5. Download your customized `.aar` from the Artifacts section of the workflow run

## Output

The workflow produces an `.aar` file that can be added to your Android project as a local dependency.

## License

See [LICENSE](LICENSE) for details.
