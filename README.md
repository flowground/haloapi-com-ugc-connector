# ![LOGO](logo.png) UGC **flow**ground Connector

## Description

A generated **flow**ground connector for the UGC API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/haloapi.com/ugc/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:42:15+03:00

## API Description

API that provides Metadata about User-Generated Content (Maps and Game Variants).

## Authorization

Supported authorization schemes:
- API Key- API Key
## Actions

### Halo 5 - Player Game Variants

> <p>Retrieves a list of Game Variants created by a Player.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "List Game Variants" to "Halo 5 - Player Game Variants".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>August 5, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Gamertag of the Player that owns the listed Game Variants.
* `start` - _optional_ - When specified, this indicates the starting index (0-based) for which the list of results will begin at.
* `count` - _optional_ - When specified, this indicates the maximum quantity of items the caller would like returned in the response.
* `sort` - _optional_ - When specified, this indicates what field should be used to sort the results as the primary sort order. When omitted, "modified" (descending) is the assumed primary sort order. Allowed sort fields are: name, description, accessibility, created, modified, bookmarkCount.
* `order` - _optional_ - When specified, this indicates the ordering that will be applied. When omitted, "desc" is assumed. Allowed order values are: asc, desc.

### Halo 5 - Player Game Variant

> <p>Retrieves Metadata about a Player-created Game Variant.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Get Game Variant" to "Halo 5 - Player Game Variant".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>August 5, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Gamertag of the Player that owns the Game Variant.
* `variant` - _required_ - The ID for the Game Variant.

### Halo 5 - Player Map Variants

> <p>Retrieves a list Map Variants created by a Player.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "List Map Variants" to "Halo 5 - Player Map Variants".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>August 5, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Gamertag of the Player that owns the listed Map Variants.
* `start` - _optional_ - When specified, this indicates the starting index (0-based) for which the list of results will begin at.
* `count` - _optional_ - When specified, this indicates the maximum quantity of items the caller would like returned in the response.
* `sort` - _optional_ - When specified, this indicates what field should be used to sort the results as the primary sort order. When omitted, "modified" (descending) is the assumed primary sort order. Allowed sort fields are: name, description, accessibility, created, modified, bookmarkCount.
* `order` - _optional_ - When specified, this indicates the ordering that will be applied. When omitted, "desc" is assumed. Allowed order values are: asc, desc.

### Halo 5 - Player Map Variant

> <p>Retrieves Metadata about a Player-created Map Variant.</p><br/>
> <br /><br/>
> <h4>Changelog</h4><br/>
> <div class="panel-body"><br/>
>     <p><strong>February 21, 2017:</strong></p><br/>
>     <ul><br/>
>         <li>Renamed Endpoint from "Get Map Variant" to "Halo 5 - Player Map Variant".</li><br/>
>         <li>Removed "{title}" Request Parameter.</li><br/>
>     </ul><br/>
> </div><br/>
> <div class="panel-body"><br/>
>     <p><strong>August 5, 2016:</strong></p><br/>
>     <ul><br/>
>         <li>Added Endpoint.</li><br/>
>     </ul><br/>
> </div>

#### Input Parameters
* `player` - _required_ - The Gamertag of the Player that owns the Map Variant.
* `variant` - _required_ - The ID for the Map Variant.

## License

**flow**ground :- Telekom iPaaS / haloapi-com-ugc-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
