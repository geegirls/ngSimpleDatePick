ngSimpleDatePick
================

A small angular date picker using JQuery and momentJS.
Supports min and max dates, so tha only dates in between those can be picked.
Works on inputs with ngModel or on a &lt;div&gt;, &lt;span&gt; or any other tag.

<pre>
&lt;input type="text" ng-model="anydate" simple-date-pick /&gt;

&lt;div simple-date-pick sdp-date="mydate" sdp-min="smallestdate" sdp-max="largestdate"&gt;{{ mydate }}&lt;/div&gt;
</pre>


Dependencies
------------
<ul>
<li>AngularJS (used v1.3.3)</li>
<li>JQuery (used v1.11.1)</li>
<li>Moment.js (used v2.8.3)</li>
</ul>

Documentation
-------------

To use it, add attribute <b>simple-date-pick</b> to any tag. If your tag is an input ngModel can be used to store the picked date. Otherwise use attribute <b>sdp-date</b>. These attribute's values should be a property of your controller's scope, so that all changes are automatically processed on both ends (the directive and the controller).

Other Attributes:

<b>sdp-min & sdp-max</b>
These should also be a property of your controller, so that these dates can change and be perceived by the ngSimpleDatePick directive. You can use them both or separately meaning dates after or before a given date.

<b>format</b>
This is a normal string attribute to set the date's format. Default is 'DD/MM/YYYY'.



Licence
-------

Released under the MIT license:

The MIT License (MIT)

Copyright (c) 2014 Walter Staeblein

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
