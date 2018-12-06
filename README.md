# cookie-proxy-server
The problem is to send cookies from localhost developer environment to remote API. Browsers don't send the cookies and don't allow to change cookie-field in headers if you are not in the same domain. So, the obvious answer is to redirect all requests-responses to remote API through the local proxy server.
