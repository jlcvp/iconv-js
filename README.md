iconv-js - pure javascript character encoding conversion
====================================================================

## Usage

#### Node.js
    
    var iconv = require('iconv-js');
    
    // Convert from SJIS buffer to UTF8 buffer.
    utf8_buffer = iconv.fromSJIS(sjis_buffer);
    
    // Convert from UTF8 buffer to SJIS buffer.
    sjis_buffer = iconv.toSJIS(utf8_buffer);
        
#### Browser
    
    <script src="iconv-js/index.js"></script>
    <script src="iconv-js/table/sjis-uni.js"></script>
    <script>

    var iconv = iconv_js.init();
            
    // Convert from SJIS arraybuffer to UTF8 buffer.
    utf8_arraybuffer = iconv.fromSJIS(sjis_arraybuffer);
    
    // Convert from UTF8 arraybuffer to SJIS buffer.
    sjis_arraybuffer = iconv.toSJIS(utf8_arraybuffer);

    </script>
        
    

## Supported encodings

*   SJIS(win) <-> UTF8

## TODO

*   Add more encodings.
