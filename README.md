# ngx-maps

A generic map and layer library for Angular: it represents a map and its layers, and everything
domain-specific is added by configuration, plugins and feature kits on top.

**Status: placeholder (0.0.1).** The name is reserved while the library is being extracted from a
working application. There is no usable API in this release.

Planned packages (scope `@ngx-maps/*`):

| Package | Role |
| --- | --- |
| `@ngx-maps/core` | layer/config model, map state, engine port, tile pipeline, packages |
| `@ngx-maps/engine-ol` | OpenLayers engine |
| `@ngx-maps/ui` | map view, toolbar, generic tools, layer panels |
| `@ngx-maps/plugin-*` | tile and feature sources (XYZ, WMS, vector, MBTiles, PMTiles) |
| `@ngx-maps/offline` | managed offline areas, package export and import |

Licensed under the EUPL-1.2 (European Union Public Licence v. 1.2), see [LICENSE.md](LICENSE.md).
The same licence as the gCube components this library is meant to work with.
