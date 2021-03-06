# caniuse.js. Detecting new html5 and Js features

Often we are looking new html5 or js features at [caniuse.com](http://caniuse.com/) to
determine if we can use this feature or not for my production code.

caniuse.js -> It will detect everything in browser side. It can tell us if I can
play mp3/ogg/wav music, use server sent events, geolocation, or if i can use drag and drop feature.
Returns true or false. You can check many things. Type it in your browser console
```javascript
caniuse.audio();
caniuse.ogg();
caniuse.mp3();
caniuse.wav();
caniuse.canvasTextApi();
caniuse.datalist();
caniuse.formConstraintValidation();
caniuse.iframeSandBox();
caniuse.iframeSrcDoc();
caniuse.inputTypeTel();
caniuse.inputTypeTime();
caniuse.inputTypeDateTime();
caniuse.inputDateTimeLocal();
caniuse.inputTypeMonth();
caniuse.crossDocumentMessaging();
caniuse.dragAndDrop();
caniuse.fileApi();
caniuse.geolocation();
caniuse.history();
caniuse.localStorage();
caniuse.microdata();
caniuse.offlineWebApplication();
caniuse.serverSentEvents();
caniuse.sessionStorage();
caniuse.svg();
caniuse.svgInTextHtml();
caniuse.undo();
caniuse.indexDB();

//// & .etc ...
```

#### Installing
```bash
bower install caniuse --save
```

![screen](https://raw.githubusercontent.com/btomashvili/caniuse/master/screens/caniuse.gif)
