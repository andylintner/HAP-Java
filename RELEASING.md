# How to release HAP-Java

These actions can only be performed by someone with maintainer level access to the repository.

1. Run the [Stage Release on Master Branch](https://github.com/hap-java/HAP-Java/actions/workflows/release.yml) Action
   This will perform the maven release, which creates two new commits, one with the release version that is tagged, and another with the new development version. The `deploy` action will upload the new release artifact and the SNAPSHOT.
2. After this completes, find the [tag](https://github.com/hap-java/HAP-Java/tags)
3. Click `...` next to the tag
4. Click `Create Release`
