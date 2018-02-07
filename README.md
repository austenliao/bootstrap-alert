# bootstrap-alert
Popup window display, a useful jquery plug-in,extended Bootstrap Alert and modal class.
Bootstrap4 supported.
To get started, check out [https://github.com/austenliao/bootstrap-alert](https://github.com/austenliao/bootstrap-alert)!
## Quick start
Include the dependencies: jQuery, Bootstrap and Bootstrap Switch CSS + Javascript:
``` html
<link href="bootstrap.css" rel="stylesheet">
<link href="bootstrap-alert.css" rel="stylesheet">
<script src="jquery.js"></script>
<script src="bootstrap.js"></script>
<script src="bootstrap-alert.js"></script>
```
examples:
``` html

<button type="button" class="btn btn-primary" onclick="doAlert()"><span class="fa fa-minus"></span>make Alert</button>
<button type="button" class="btn btn-primary" onclick="doConfirm()"><span class="fa fa-minus"></span>make confirm</button>


<script type="text/javascript">
    
    //$.bsAlert.init();

    function doAlert() {
        $.bsAlert.alert("warning!warning");
    }

    function doConfirm() {
        $.bsAlert.confirm("please confirm!",function(){
            alert(1);
        });
    }

</script>
``` 
