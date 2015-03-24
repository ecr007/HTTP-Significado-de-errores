<h1>Codigo de Errores y su significado</h1>

<div id="column_l">
<h1>HTTP Status Codes</h1>
<p>Every HTTP transaction has a status code sent back by the server 
to define how the server handled the transaction. Here is a list of 
the most common ones.</p>
<h2>List of Common HTTP Status Codes</h2>
<ol>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-200">
200 OK</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-300">
300 Multiple Choices</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-301">
301 Moved Permanently</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-302">
302 Found</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-304">
304 Not Modified</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-307">
307 Temporary Redirect</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-400">
400 Bad Request</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-401">
401 Unauthorized</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-403">
403 Forbidden</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-404">
404 Not Found</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-410">
410 Gone</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-500">
500 Internal Server Error</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-501">
501 Not Implemented</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-503">
503 Service Unavailable</a></li>
<li>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#code-550">
550 Permission denied</a></li>
</ol>
<a id="code-200"></a>
<h3>HTTP Status Code - 200 OK</h3>
<p>The request has succeeded. The information returned with the response 
is dependent on the method used in the request.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-300"></a>
<h3>HTTP Status Code - 300 Multiple Choices</h3>
<p>The requested resource has different choices and cannot be resolved 
into one. For example, there may be several index.html pages depending 
on which language is wanted (such as Dutch).</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-301"></a>
<h3>HTTP Status Code - 301 Moved Permanently</h3>
<p>The requested resource has been assigned a new permanent URI and 
any future references to this resource should use one of the returned 
URIs.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-302"></a>
<h3>HTTP Status Code - 302 Found</h3>
<p>The requested resource resides temporarily under a different URI. 
Since the redirection might be altered on occasion, the client SHOULD 
continue to use the Request-URI for future requests.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-304"></a>
<h3>HTTP Status Code - 304 Not Modified</h3>
<p>If the client has performed a conditional GET request and access 
is allowed, but the document has not been modified, the server SHOULD 
respond with this status code. The 304 response MUST NOT contain a message-body, 
and thus is always terminated by the first empty line after the header 
fields. If the client has done a conditional GET and access is allowed, 
but the document has not been modified since the date and time specified 
in If-Modified-Since field, the server responds with a 304 status code 
and does not send the document body to the client. Response headers 
are as if the client had sent a HEAD request, but limited to only those 
headers which make sense in this context. This means only headers that 
are relevant to cache managers and which may have changed independently 
of the document's Last-Modified date. Examples include Date , Server 
and Expires . The purpose of this feature is to allow efficient updates 
of local cache information (including relevant meta information) without 
requiring the overhead of multiple HTTP requests (e.g. a HEAD followed 
by a GET) and minimizing the transmittal of information already known 
by the requesting client (usually a caching proxy).</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-307"></a>
<h3>HTTP Status Code - 307 Temporary Redirect</h3>
<p>The requested resource resides temporarily under a different URI. 
Since the redirection MAY be altered on occasion, the client SHOULD 
continue to use the Request-URI for future requests. This response is 
only cacheable if indicated by a Cache-Control or Expires header field.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-400"></a>
<h3>HTTP Status Code - 400 Bad Request</h3>
<p>The request could not be understood by the server due to malformed 
syntax. The client SHOULD NOT repeat the request without modifications.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-401"></a>
<h3>HTTP Status Code - 401 Unauthorized</h3>
<p>The request requires user authentication. The response MUST include 
a WWW-Authenticate header field containing a challenge applicable to 
the requested resource.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-403"></a>
<h3>HTTP Status Code - 403 Forbidden</h3>
<p>The server understood the request, but is refusing to fulfill it. 
Authorization will not help and the request SHOULD NOT be repeated.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-404"></a>
<h3>HTTP Status Code - 404 Not Found</h3>
<p>The server has not found anything matching the Request-URI. No indication 
is given of whether the condition is temporary or permanent.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-410"></a>
<h3>HTTP Status Code - 410 Gone</h3>
<p>The requested resource is no longer available at the server and no 
forwarding address is known. This condition is expected to be considered 
permanent. Clients with link editing capabilities SHOULD delete references 
to the Request-URI after user approval.</p>
<p>If the server does not know, or has no facility to determine, whether 
or not the condition is permanent, the status code 404 Not Found SHOULD 
be used instead. This response is cacheable unless indicated otherwise.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-500"></a>
<h3>HTTP Status Code - 500 Internal Server Error</h3>
<p>The server encountered an unexpected condition which prevented it 
from fulfilling the request.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-501"></a>
<h3>HTTP Status Code - 501 Not Implemented</h3>
<p>The server does not support the functionality required to fulfill 
the request. This is the appropriate response when the server does not 
recognize the request method and is not capable of supporting it for 
any resource.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<a id="code-503"></a>
<h3>HTTP Status Code - 503 Service Unavailable</h3>
<p>Your web server is unable to handle your HTTP request at the time. 
There are a myriad of reasons why this can occur but the most common 
are:</p>
<ul>
<li>server crash</li>
<li>server maintenance</li>
<li>server overload</li>
<li>server maliciously being attacked</li>
<li>a website has used up its allotted bandwidth</li>
<li>server may be forbidden to return the requested document</li>
</ul>
<p>This is usually a temporary condition. Since you are getting a return 
code, part of the server is working. The web people have made the server 
return this code until they fix the problem.<br>
<br>
If you do not get service back soon, contact your web host as they would 
know the best. Some web hosts have server status pages you can check.</p>
<p><a href="#topofpage">Back to top</a></p>
<a id="code-550"></a>
<h3>HTTP Status Code - 550 Permission Denied</h3>
<p>The server is stating the account you have currently logged in as 
does not have permission to perform the action you are attempting. You 
may be trying to upload to the wrong directory or trying to delete a 
file.</p>
<p>
<a href="http://www.smartlabsoftware.com/ref/http-status-codes.htm#topofpage">
Back to top</a></p>
<h3>W3C References</h3>
<ol>
<li>
<a href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html#sec10" title="W3C status code definitions">
W3C - 10 Status Code Definitions</a></li>
<li>
<a href="http://www.w3.org/Protocols/rfc2616/rfc2616-sec14.html" title="W3C header field definitions">
W3C - 14 Header Field Definitions</a></li>
</ol>
<div class="gextras">
<!-- Place this tag where you want the +1 button to render. -->
</div>
</div>
