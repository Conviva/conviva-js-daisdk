# conviva-js-daisdk
Conviva Google IMA DAI SDK module auto-detects ad events emitted by Google IMA DAI SDK.

## Offline Library
The Conviva JavaScript Google IMA DAI SDK module is built on top of <a href="https://github.com/Conviva/conviva-js-coresdk">conviva-core-sdk</a>, is shared as offline library and should be included via the <script> tag in the application.

``` 
<script type="text/javascript" src="<PATH>/conviva-core-sdk.js"></script>
<script type="text/javascript" src="<PATH>/conviva-googledai-module.js"></script>
```
## Install via npm 

```
npm install @convivainc/conviva-js-daisdk --save
```

## Usage

```
import Conviva from '@convivainc/conviva-js-coresdk';
import ConvivaModule from '@convivainc/conviva-js-daisdk';
or
const Conviva = require('@convivainc/conviva-js-coresdk');
const ConvivaModule = require('@convivainc/conviva-js-daisdk');
```

## Note:
* Refer https://community.conviva.com/ for integration guidelines.