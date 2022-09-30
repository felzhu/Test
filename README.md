## **NOTE: If the code is not ran on the sam device, you will have to replace the “localhost” with the IP address of the device where the servers are running**

# Part A - Web Server
    1. Open terminal in this directory
    2. Run the Python file with python webserver.py
    3. Type in URL in your browser of your choosing (http://localhost:6789/HelloWorld.html)
    4. You should see "Hello World" just like ReceiveHTMlFromServer.PNG
    5. Accessing a file not in the directory will result in "404 Not Found" HTTP Response Header


# Part B - Web Proxy
    1. Open terminal in this directory
    2. Run the Python file with python proxyserver.py
    3. Type in the URLs in your browser of your choosing. The following URL will work with the proxy server, after that the html files should appear in the server directory:

    http://localhost:8888/gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file1.html
    http://localhost:8888/gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file2.html
    http://localhost:8888/gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file3.html
    http://localhost:8888/gaia.cs.umass.edu/wireshark-labs/HTTP-wireshark-file4.html

    You can also access the image files from server cache such as:

    http://localhost:8888/JPG_File.jpg
    http://localhost:8888/PNG_File.png
