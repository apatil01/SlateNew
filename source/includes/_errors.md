# Response Codes

PEX uses conventional HTTPS response codes to indicate the success or failure of a request. In general, 200-level codes indicate success, 400-level codes indicate an error that resulted from your input, and 500-level codes are typically related to a PEX internal issue, and should be reported to us. Errors specific to a call are included on the documentation page. Global errors can occur with most calls and they are listed below:


Error Code | Meaning
---------- | -------
400 | The request is invalid
401 | Password has changed
401 | Token expired or does not exist
401 | Missing authorization header
401 | Bad authorization scheme
401 | Invalid appId
403 | Must be admin user
403 | Business is not open
403 | User is not active
403 | Invalid Card Account ID
409 | Conflict
429 | Usage limits exceeded
500 | System error
502 | Bad Gateway; please retry after 2 mins


<aside class="notice">
If 400: Invalid Input is received, further helpful information about the error is provided in the response.
</aside>
