# <p style="text-align:center"> **Curl Commands** <p> #
### 1. To find the location of the curl program in your system “where curl” is used.
### 2. To find the version of curl “curl --version” is used.
### 3. GET -> To send a get request to a URL we just write curl followed by the url, it generates the file html file of the given url.
![img_15.png](img_15.png)
### 4. -o -> This saves the output from the get request to the url.
### 5. -I -> This gives the header of the given url.
![img_3.png](img_3.png)
### 6. -O -> This saves the output from the get request to the url and save with the given name instead of using a custom name.
### 7.  --limit-rate -10k -> This will limit the download rate.
### 8. -C - -> It is used to continue the download of the file.
![img_4.png](img_4.png)
### 9. -L -> By default redirects are not followed in curl so if we want to follow the redirects we use this.
### 10. -a -> This is used to append the output of the file to an existing one.
### 11. -v -> Sometimes referred as verbose mode this allows to view request headers and connection information of the url. Request data, response headers, and other information about the request, such as the IP used and the SSL handshake process, are all included in the output.
 ![img_5.png](img_5.png)
### 12. -vo -> When we don’t want the body and just save the output of the headers and to a null device.
![img_6.png](img_6.png)
### 13. -H -> Used to set up the custom header for an url.
![img_7.png](img_7.png)
### 14. --data -> It is used to send a POST request to the server and send the data.
![img_8.png](img_8.png)
### 15.  -X –H ->Sending JSON data to the server using POST.
![img_9.png](img_9.png)
### 16. -sSo ->Manually verifying the Http requests.
![img_10.png](img_10.png)
### 17.  -v --sslv3   ->Checking if the server supports a specific protocol.
![img_11.png](img_11.png)
### 18. -k -> To avoid the certificate checking for a specific site.
![img_12.png](img_12.png)
### 19. -6 -> To check if a certain site is configured to use ipv6.
![img_13.png](img_13.png)
### 20. -k -file_name -> It Provides different configuration for different url requests.
![img_14.png](img_14.png)

# <p style="text-align:center"> **Postman Methods** <p>
### 1. GET
![img_16.png](img_16.png)
### 2. POST
![img_17.png](img_17.png)
### 3. PUT
![img_18.png](img_18.png)
### 4. PATCH
![img_19.png](img_19.png)
### 5. UPDATE
![img_20.png](img_20.png)
### 6. HEAD
![img_21.png](img_21.png)