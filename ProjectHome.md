## Update ##
**2012/01/24 Fix date ranges problem.**

**2011/07/01 add example to download section.**

**If you got any issue please contact me at sorajate@gmail.com**

## English ##
This is extension for jquery-ui-datepicker to make it support support BE (buddhist era) Format

Tested with jquery-ui-datepicker version 1.8.13 and jquery-1.6

### Usage ###
include this file after jquery and jquery-ui ( or jquery-ui-datepicker )

### Extension Option ###
**(bool)isBE : true to enable BE era**

**(bool)autoConversionField : true to auto create hidden input field to contains CE format**

### Example ###
```
<script src="/path_to/jquery.ui.datepicker.js" type="text/javascript" charset="utf-8"></script>
<script src="/path_to/jquery.ui.datepicker.ext.be.js" type="text/javascript" charset="utf-8"></script>
<script type="text/javascript">
$(document).ready(function(){
$( ".datepicker").datepicker({                
                    isBE: true,
                    autoConversionField: true
});
});
</script>
```


---

## Thai ( ภาษาไทย ) ##
ส่วนเสริม สำหรับ jquery ui datepicker ให้ใช้ ปี พศ ได้ :D ในรูปแบบ Plugins วิธีใช้อ่านด้านบน

## Change Logs ##
# Version 0.1 First Version

# Version 0.2 Add Compatible with jquery datetimepicker and Fix some bugs