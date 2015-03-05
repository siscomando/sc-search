sc-search
============

sc-search is an custom element to generic searches based in a preset model.


Usage
======

The sc-search uses the core-ajax component to search. 

```
    <sc-search url="http://api.randomuser.me/"></sc-search>
    // you can to listen the results. It's asynchronous.
    <script>
    ...
    search = document.querySelector('sc-search');
    search.addEventListener('sc-response', 
           function(e){ 
               console.log(e.detail.response['SCOPE'])
            }); 
    ...
    </script>
```

