## API Report File for "@backstage/integration-react"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
/// <reference types="react" />

import { ApiRef } from '@backstage/core-plugin-api';
import { Config } from '@backstage/config';
import { ScmIntegrationRegistry } from '@backstage/integration';

// Warning: (ae-missing-release-tag) "ScmIntegrationIcon" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export const ScmIntegrationIcon: ({
  type,
}: {
  type?: string | undefined;
}) => JSX.Element;

// Warning: (ae-missing-release-tag) "ScmIntegrationsApi" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export class ScmIntegrationsApi {
  // (undocumented)
  static fromConfig(config: Config): ScmIntegrationRegistry;
}

// Warning: (ae-missing-release-tag) "scmIntegrationsApiRef" is exported by the package, but it is missing a release tag (@alpha, @beta, @public, or @internal)
//
// @public (undocumented)
export const scmIntegrationsApiRef: ApiRef<ScmIntegrationRegistry>;
```
