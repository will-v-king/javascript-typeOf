javascript-typeOf
=================

typeOf is a function to get the type of a javascript object.

result as :
/*
* typeOf({},['object','string']) == true;
*
* typeOf({},'object) == true;
*
* typeOf({}) == 'Object'
*
* typeOf(null, 'Object') == false;
*
* typeOf(function(){},'function') == true;
*
* typeOf(undefined, 'undefined') == true;
*
* typeOf(null,'null') == true;
*
* typeOf() == 'undefined';
*
* typeOf(NaN) == 'NaN';
*/
