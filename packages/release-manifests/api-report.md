## API Report File for "@backstage/release-manifests"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
// @public
export function getByReleaseLine(
  options: GetByReleaseLineOptions,
): Promise<ReleaseManifest>;

// @public
export type GetByReleaseLineOptions = {
  releaseLine: string;
};

// @public
export function getByVersion(
  options: GetByVersionOptions,
): Promise<ReleaseManifest>;

// @public
export type GetByVersionOptions = {
  version: string;
};

// @public
export type ReleaseManifest = {
  releaseVersion: string;
  packages: {
    name: string;
    version: string;
  }[];
};
```