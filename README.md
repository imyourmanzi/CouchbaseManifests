# Couchbase Developer Manifests

For use with the `repo` tool from Google.

`repo` tool resources:

- https://source.android.com/docs/setup/build/downloading
- https://gerrit.googlesource.com/git-repo/+/refs/heads/master/README.md
- https://gerrit.googlesource.com/git-repo/
- http://code.google.com/p/git-repo/downloads/list (may not work)

## Usage

```sh
mkdir couchbase-sdk
cd couchbase-sdk
repo init -u https://github.com/imyourmanzi/CouchbaseManifests -m sdk.xml --partial-clone # requires git 2.19 or newer
repo sync
```
