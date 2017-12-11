Add at the very beginning of the template "header":

<!-- dynamic garland -->
     <link rel="stylesheet" href="NewYearDynamic/NewYearDynamic.min.css">
     <script type="text/javascript" src="NewYearDynamic/newyear.min.js"></script>
     <script type="text/javascript" src="NewYearDynamic/swfobject.min.js"></script>
     <script type="text/javascript" src="NewYearDynamic/bodyclass.js"></script>
     <div style="position:absolute !important; left:0%; top:0px;"><img src="NewYearDynamic/balls/NewYearLeft.png" border="0" /></div><div style="position:absolute !important; right:0%; top:0px;"><img src="NewYearDynamic/balls/NewYearRight.png" border="0" /></div>
<!--/ dynamic garland -->

Optionally, adjust the spacing from the top of the template "headinclude":

<style>
     body { 
         margin-top: 28px !important;
     }
</style>