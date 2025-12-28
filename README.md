# nw-ruffle-example

Use Ruffle to display SWF files in NW.js

1. Download/fork/clone the repo
1. Install [Volta](https://volta.sh)
1. `npm i`
1. `npm start`


Updating Ruffle:

1. Run `npm i --save @ruffle-rs/ruffle@latest`
1. This will update the version in the `package.json`
1. If the version is greater than `0.x.x` (such as `1.0.0`, `2.0.0`, etc), then consult documentation for API changes.


* * *


**Alternatives:**

* [NWRuffle](https://github.com/Anikthedev-Official/NWRuffle) - Stores settings in the manifest, uses them to start a local webserver to display the SWF in NW.js.
