## API Report File for "@backstage/plugin-api-docs-spectral-linter"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts
/// <reference types="react" />

import { ApiEntity } from '@backstage/catalog-model';
import { BackstagePlugin } from '@backstage/core-plugin-api';
import { RouteRef } from '@backstage/core-plugin-api';

// @public
export const apiDocsSpectralLinterPlugin: BackstagePlugin<
  {
    root: RouteRef<undefined>;
  },
  {},
  {}
>;

// @public
export const EntityApiDocsSpectralLinterContent: () => JSX.Element;

// @public
export const isApiDocsSpectralLinterAvailable: (entity: ApiEntity) => boolean;
```
