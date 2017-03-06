# GM_SuperValue
Improved, error-free and readable version of GreaseMonkey/TamperMonkey storage script "GM_SuperValue"

Same usage as GM_SuperValue original library (not git repository available for forking)

This library extends the Greasemonkey `GM_setValue` and `GM_getValue` functions to
handle any javascript variable type.

Add it to your GM script with:

    // @require http://userscripts.org/scripts/source/107941.user.js


**Usage:**

    GM_SuperValue.set(varName, varValue);  
    var x = GM_SuperValue.get(varName, defaultValue);  

**Test mode:**

    GM_SuperValue.runTestCases  (bUseConsole);

Here is the original script page for [reference](http://userscripts-mirror.org/scripts/show/107941).
