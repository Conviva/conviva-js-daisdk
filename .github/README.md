# conviva-js-daisdk
Conviva Google IMA DAI SDK module auto-detects ad events emitted by Google IMA DAI SDK.

## Offline Library
The Conviva JavaScript Google IMA DAI SDK module is built on top of <a href="https://github.com/Conviva/conviva-js-coresdk">conviva-core-sdk</a>, is shared as offline library and should be included via the <script> tag in the application.

Via html:
``` 
<script type="text/javascript" src="<PATH>/conviva-core-sdk.js"></script>
<script type="text/javascript" src="<PATH>/conviva-googledai-module.js"></script>
```
Via import/require:
```
const Conviva = require('<path>/conviva-js-coresdk');
const ConvivaGoogledaiModule = require('<path>/conviva-googledai-module');
```

```
import Conviva from '@convivainc/conviva-js-coresdk'
import ConvivaGoogledaiModule from'@convivainc/conviva-googledai-module '
```

## Install via npm 

```
npm install @convivainc/conviva-js-daisdk --save
```
## Install via yarn 

```
yarn add @convivainc/conviva-js-daisdk
```

## Note:
* Refer https://community.conviva.com/ for integration guidelines.
