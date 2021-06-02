# barcodeScan
This plugin detects barcode input. It uses a function as an arguement. It requires jQuery.

## To use this plugin

```
<script type="text/javascript" src="jquery.js"></script>

<script type="text/javascript" src="barcodeScan.js"></script>
```

Example
`````````
function results(barcode) {
  $( "input" ).val(barcode);
}

$( document ).ready(function() {
    barcodeScan(results);
});

`````````
