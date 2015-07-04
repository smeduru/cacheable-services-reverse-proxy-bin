# cacheable-services-reverse-proxy-bin
Reverse Proxy for caching soap/rest requests and responses. It will record SOAP/REST requests and responses dynamically during the initial work flow. It will make use of the cache to process the requests from the subsequent work flows. It uses the cache as long as the input/request is same. It basically uses request hash code to map the requests and responses. As long as the hash code generated from the request is same, it can retrieve it's corresponding response from the cache.


