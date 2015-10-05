# apex-jquery-resizable-columns-demo

<img src="http://cdn-ak.f.st-hatena.com/images/fotolife/t/tyoshikawa1106/20151005/20151005181422.png" />

## include
```
<apex:includeScript value="{!URLFOR($Resource.jquery_resizable, 'dist/jquery.min.js')}" />
<apex:includeScript value="{!URLFOR($Resource.jquery_resizable, 'dist/store.min.js')}" />
<apex:includeScript value="{!URLFOR($Resource.jquery_resizable, 'dist/jquery.resizableColumns.min.js')}" />
<apex:stylesheet value="{!URLFOR($Resource.jquery_resizable, 'dist/jquery.resizableColumns.css')}" />
```

## JavaScript
```
<apex:page>
  <script type="text/javascript">
    $(function(){
      $(".resizableTable").resizableColumns({
        store: window.store
      });
      $(".resizableTable-vf").resizableColumns({
        store: window.store
      });
    });
  </script>
</apex:page>
```

##Demo
<a href="https://www.youtube.com/watch?t=45&v=7N9p4c8VCwQ">https://www.youtube.com/watch?t=45&v=7N9p4c8VCwQ</a>

##jquery-resizable-columns
<a href="https://github.com/dobtco/jquery-resizable-columns">https://github.com/dobtco/jquery-resizable-columns</a>
