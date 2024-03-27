0x10. Python - Network #0
=========================

BashPythonScriptingBack-endAPI

*   Weight: 1
*   Project will start Mar 27, 2024 6:00 AM, must end by Mar 28, 2024 6:00 AM
*   Checker was released at Mar 27, 2024 12:00 PM
*   An auto review will be launched at the deadline

Resources
---------

**Read or watch**:

*   [HTTP (HyperText Transfer Protocol)](/rltoken/rAon_EpQ6PGl8N0plySn4A "HTTP (HyperText Transfer Protocol)") (_except: “TRACE” Request Method, “CONNECT” Request Method, Language Negotiation and “Options MultiView” and Character Set Negotiation_)
*   [HTTP Cookies](/rltoken/MhVCl_0oviQldWPn5oX-NQ "HTTP Cookies")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](/rltoken/6HRdeOrrKTW2ih43ObB8tQ "explain to anyone"), **without the help of Google**:

### General

*   What a URL is
*   What HTTP is
*   How to read a URL
*   The scheme for a HTTP URL
*   What a domain name is
*   What a sub-domain is
*   How to define a port number in a URL
*   What a query string is
*   What an HTTP request is
*   What an HTTP response is
*   What HTTP headers are
*   What the HTTP message body is
*   What an HTTP request method is
*   What an HTTP response status code is
*   What an HTTP Cookie is
*   How to make a request with cURL
*   What happens when you type google.com in your browser (Application level)

### Copyright - Plagiarism

*   You are tasked to come up with solutions for the tasks below yourself to meet with the above learning objectives.
*   You will not be able to meet the objectives of this or any following project by copying and pasting someone else’s work.
*   You are not allowed to publish any content of this project.
*   Any form of plagiarism is strictly forbidden and will result in removal from the program.

Requirements
------------

### General

*   Allowed editors: `vi`, `vim`, `emacs`
*   \- A `README.md` file, at the root of the folder of the project, is mandatory
*   All your scripts will be tested on Ubuntu 20.04 LTS
*   All your Bash scripts should be exactly 3 lines long (`wc -l file` should print 3)
*   All your files should end with a new line
*   All your files must be executable
*   The first line of all your bash files should be exactly `#!/bin/bash`
*   The second line of all your Bash scripts should be a comment explaining what is the script doing
*   All `curl` commands must have the option `-s` (silent mode)
*   All your files will be interpreted/compiled on Ubuntu 20.04 LTS using `python3` (version 3.8.5)
*   The first line of all your Python files should be exactly `#!/usr/bin/python3`
*   Your code should use the pycodestyle (version `2.8.*`)
*   All your modules should be documented: `python3 -c 'print(__import__("my_module").__doc__)'`
*   All your classes should be documented: `python3 -c 'print(__import__("my_module").MyClass.__doc__)'`
*   All your functions (inside and outside a class) should be documented: `python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`
*   A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

### Quiz questions

**Great!** You've completed the quiz successfully! Keep going! (Show quiz)

#### Question #0

What is the name of the HTTP response header used to define the status code of the response?

*   Status-Code
    
*   Http-Status
    
*   Code
    
*   Status
    

#### Question #1

What’s the status code number for an invalid HTTP request (server can’t understand it)?

*   400
    
*   404
    
*   500
    

#### Question #2

In the following URL, how many parameters are in the query string?

    https://www.google.com/apply?batch=89&location=SF&name=John%20do%20is%20the%20best%20%3D%20c%20is%20fun
    

*   2
    
*   3
    
*   1
    
*   4
    
*   5
    

#### Question #3

In the following URL, what’s the sub domain?

    https://api-dev.google.com/v1/auth/new
    

*   /v1
    
*   /v1/auth/new
    
*   api-dev
    

#### Question #4

In the following URL, what’s the hostname?

    http://www.google.com
    

*   google.com
    
*   www.google
    
*   www.google.com
    
*   google
    

#### Question #5

What will be the port number requested by this URL?

    https://www.google.com:8080/apply
    

*   8888
    
*   8080
    
*   80
    

#### Question #6

What will be the port number requested by this URL?

    afp://www.google.com/access_in_port_543
    

*   548
    
*   80
    
*   543
    

#### Question #7

What is the name of the HTTP response header that defines a list of available HTTP methods for this URL?

*   Verbs-Allowed
    
*   Allow
    
*   Verbs
    

#### Question #8

What is the name of the HTTP response header used to define the formatting of the body? (This header gives details to the client on how to interpret the data received.)

*   Content-Format
    
*   Content-Type
    
*   Format
    
*   Type
    

#### Question #9

In this following HTML code, which HTTP verb will be used when you will submit this form?

    <FORM action="/login.php" method="post">
        <INPUT type="email" name="email" placeholder="Email" required/>
        <INPUT type="password" name="password" placeholder="Password" required/>
        <INPUT type="submit" name="submit" value="Login" />
    <FORM>
    

*   FORM
    
*   POST
    
*   SUBMIT
    
*   ENTER
    
*   GET
    

#### Question #10

What is the first digit of status codes that indicate a server error?

*   2xx
    
*   1xx
    
*   3xx
    
*   4xx
    
*   5xx
    

#### Question #11

What is the `curl` option to follow all redirects?

*   \-L
    
*   \-X
    
*   \-s
    

#### Question #12

Which `curl` option is used to set an HTTP header to a specific value?

*   \-s
    
*   \-X
    
*   \-H
    

#### Question #13

What’s the status code number for a web page that can’t be found?

*   500
    
*   405
    
*   404
    

#### Question #14

When an HTTP response indicates a redirection, which header defines the URL the client should be redirected to?

*   Location
    
*   Redirect-URI
    
*   Next-Location
    
*   Redirect-Location
    
*   Redirect
    

#### Question #15

In the following URL, what’s the name of the parameter in the query string?

    https://www.google.com/apply?batch=89
    

*   89
    
*   apply
    
*   batch
    

#### Question #16

In this following HTML code, which HTTP verb will be used when you will submit this form?

    <FORM action="/12/update.php" method="put">
        <INPUT type="text" name="first_name" value="Bob"/>
        <INPUT type="text" name="last_name" value="Dylan"/>
        <INPUT type="submit" name="update" value="Update" />
    <FORM>
    

*   UPDATE
    
*   PUT
    
*   POST
    
*   GET
    

#### Question #17

In the following URL, what’s the resource path?

    https://www.google.com/assets/scripts/main.js
    

*   assets/scripts
    
*   main.js
    
*   assets/scripts/main.js
    

#### Question #18

What is the name of the HTTP response header used to send cookies to the client from the server?

*   Cookie-Setter
    
*   Set-Cookie
    
*   Send-Cookies
    

#### Question #19

What is the `curl` option to disable the progression display?

*   \-c
    
*   \-p
    
*   \-b
    
*   \-s
    

#### Question #20

Which HTTP request header indicates the browser used by the client sending the request?

*   User-Agent
    
*   Browser-Name
    
*   I-Am
    
*   Origin
    

#### Question #21

In the following URL, what’s the resource path?

    https://www.google.com/index.html
    

*   www.google.com/index.html
    
*   index.html
    
*   /
    

#### Question #22

What is the name of the HTTP request header used to send cookies from the client?

*   Send-Cookie
    
*   Cookies
    
*   Cookie
    
*   Set-Cookie
    

#### Question #23

What’s the status code number for a permanent redirection (moved permanently)?

*   300
    
*   201
    
*   301
    
*   302
    
*   304
    

#### Question #24

What is the `curl` option to set a cookie with a key-value pair?

*   \-b
    
*   \-c
    
*   \-a
    
*   \-d
    

#### Question #25

When you are typing `https://intranet.hbtn.io` in your browser, which HTTP verb is used?

*   DELETE
    
*   PUT
    
*   GET
    
*   POST
    

#### Question #26

In the following URL, what’s the protocol?

    http://www.google.com
    

*   ftp
    
*   https
    
*   http
    

#### Question #27

In the following URL, what’s the sub domain?

    https://api.google.com/v1/auth
    

*   api
    
*   api.google
    
*   .com
    

#### Question #28

What will be the port number requested by this URL?

    http://www.google.com/apply
    

*   80
    
*   22
    
*   443
    
*   8080
    

#### Question #29

What is the `curl` option to save the body of the resulting response to a file?

*   \-b
    
*   \-o
    
*   \-r
    
*   \-d
    

#### Question #30

What is the `curl` option that defines the HTTP method used?

*   \-s
    
*   \-X
    
*   \-d
    

#### Question #31

In the following URL, what’s the resource path?

    https://api.google.com/v1/auth/new
    

*   v1/auth
    
*   v1/auth/new/index.html
    
*   v1/auth/new
    
*   v1
    

#### Question #32

What is the name of the HTTP request header that defines the size (in bytes) of the message body?

*   Length
    
*   Size
    
*   Content-Size
    
*   Content-Length
    

#### Question #33

In the following URL, how many parameters are in the query string?

    https://www.google.com/apply?batch=89&location=SF
    

*   1
    
*   3
    
*   2
    

#### Question #34

What is the name of the HTTP response header used to define the size, in bytes, of the body of the response?

*   Content-Size
    
*   Content-Length
    
*   Length
    
*   Body-Size
    

#### Question #35

What is the `curl` option to set a body key-value parameter?

*   \-d
    
*   \-X
    
*   \-b
    

Tasks
-----

### 0\. cURL body size

mandatory

Write a Bash script that takes in a URL, sends a request to that URL, and displays the size of the body of the response

*   The size must be displayed in bytes
*   You have to use `curl`

Please test your script in the sandbox provided, using the web server running on port 5000

    guillaume@ubuntu:~/0x10$ ./0-body_size.sh 0.0.0.0:5000
    10
    guillaume@ubuntu:~/0x10$ 
    

**Repo:**

*   GitHub repository: `alx-higher_level_programming`
*   Directory: `0x10-python-network_0`
*   File: `0-body_size.sh`

Done?! Check your code

×

#### Correction of "0. cURL body size"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

Get a sandbox

### 1\. cURL to the end

mandatory

Write a Bash script that takes in a URL, sends a `GET` request to the URL, and displays the body of the response

*   Display only body of a `200` status code response
*   You have to use `curl`

Please test your script in the sandbox provided, using the web server running on port 5000

    guillaume@ubuntu:~/0x10$ ./1-body.sh 0.0.0.0:5000/route_1 ; echo ""
    Route 2
    guillaume@ubuntu:~/0x10$ 
    

**Repo:**

*   GitHub repository: `alx-higher_level_programming`
*   Directory: `0x10-python-network_0`
*   File: `1-body.sh`

Done?! Check your code

×

#### Correction of "1. cURL to the end"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

Get a sandbox

### 2\. cURL Method

mandatory

Write a Bash script that sends a `DELETE` request to the URL passed as the first argument and displays the body of the response

*   You have to use `curl`

Please test your script in the sandbox provided, using the web server running on port 5000

    guillaume@ubuntu:~/0x10$ ./2-delete.sh 0.0.0.0:5000/route_3 ; echo ""
    I'm a DELETE request
    guillaume@ubuntu:~/0x10$ 
    

**Repo:**

*   GitHub repository: `alx-higher_level_programming`
*   Directory: `0x10-python-network_0`
*   File: `2-delete.sh`

Done?! Check your code

×

#### Correction of "2. cURL Method"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

Get a sandbox

### 3\. cURL only methods

mandatory

Write a Bash script that takes in a URL and displays all HTTP methods the server will accept.

*   You have to use `curl`

Please test your script in the sandbox provided, using the web server running on port 5000

    guillaume@ubuntu:~/0x10$ ./3-methods.sh 0.0.0.0:5000/route_4
    OPTIONS, HEAD, PUT
    guillaume@ubuntu:~/0x10$ 
    

**Repo:**

*   GitHub repository: `alx-higher_level_programming`
*   Directory: `0x10-python-network_0`
*   File: `3-methods.sh`

Done?! Check your code

×

#### Correction of "3. cURL only methods"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

Get a sandbox

### 4\. cURL headers

mandatory

Write a Bash script that takes in a URL as an argument, sends a `GET` request to the URL, and displays the body of the response

*   A header variable `X-School-User-Id` must be sent with the value `98`
*   You have to use `curl`

Please test your script in the sandbox provided, using the web server running on port 5000

    guillaume@ubuntu:~/0x10$ ./4-header.sh 0.0.0.0:5000/route_5 ; echo ""
    Hello School!
    guillaume@ubuntu:~/0x10$ 
    

**Repo:**

*   GitHub repository: `alx-higher_level_programming`
*   Directory: `0x10-python-network_0`
*   File: `4-header.sh`

Done?! Check your code

×

#### Correction of "4. cURL headers"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

Get a sandbox

### 5\. cURL POST parameters

mandatory

Write a Bash script that takes in a URL, sends a `POST` request to the passed URL, and displays the body of the response

*   A variable `email` must be sent with the value `test@gmail.com`
*   A variable `subject` must be sent with the value `I will always be here for PLD`
*   You have to use `curl`

Please test your script in the sandbox provided, using the web server running on port 5000

    guillaume@ubuntu:~/0x10$ ./5-post_params.sh 0.0.0.0:5000/route_6 ; echo ""
    POST params:
        email: test@gmail.com
        subject: I will always be here for PLD
    guillaume@ubuntu:~/0x10$ 
    

**Repo:**

*   GitHub repository: `alx-higher_level_programming`
*   Directory: `0x10-python-network_0`
*   File: `5-post_params.sh`

Done?! Check your code

×

#### Correction of "5. cURL POST parameters"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

Get a sandbox

### 6\. Find a peak

mandatory

**Technical interview preparation**:

*   You are not allowed to google anything
*   Whiteboard first

Write a function that finds **a peak** in a list of unsorted integers.

*   Prototype: `def find_peak(list_of_integers):`
*   You are not allowed to import any module
*   Your algorithm must have the lowest complexity (_hint: you don’t need to go through all numbers to find a peak_)
*   `6-peak.py` must contain the function
*   `6-peak.txt` must contain the complexity of your algorithm: `O(log(n))`, `O(n)`, `O(nlog(n))` or `O(n2)`
*   **Note**: there may be more than one peak in the list

    guillaume@ubuntu:~/0x10$ cat 6-main.py
    #!/usr/bin/python3
    """ Test function find_peak """
    find_peak = __import__('6-peak').find_peak
    
    print(find_peak([1, 2, 4, 6, 3]))
    print(find_peak([4, 2, 1, 2, 3, 1]))
    print(find_peak([2, 2, 2]))
    print(find_peak([]))
    print(find_peak([-2, -4, 2, 1]))
    print(find_peak([4, 2, 1, 2, 2, 2, 3, 1]))
    
    guillaume@ubuntu:~/0x10$ ./6-main.py
    6
    3
    2
    None
    2
    4
    guillaume@ubuntu:~/0x10$ wc -l 6-peak.txt 
    2 6-peak.txt
    guillaume@ubuntu:~/0x10$ 
    

**Repo:**

*   GitHub repository: `alx-higher_level_programming`
*   Directory: `0x10-python-network_0`
*   File: `6-peak.py, 6-peak.txt`

Done?! Check your code

×

#### Correction of "6. Find a peak"

Start a new test Close

Requirement success

Requirement fail

Code success

Code fail

Efficiency success

Efficiency fail

Text answer success

Text answer fail

Skipped - Previous check failed

Get a sandbox

×

#### Recommended Sandboxes

Running only

### 2 images(1/2 Sandboxes spawned)

### Ubuntu 20.04

Basic Ubuntu 20.04, with vim, emacs, curl, wget and all needed for Foundations

SSH

SFTP

[Webterm](/user_containers/649598/webterm)

RestartDestroy

#### Credentials

**Host**fda8e0cc5a27.687f6cc0.alx-cod.online

**Username**fda8e0cc5a27

**Password**03325d159a96fd10524a

#### Web access

[HTTPS](https://fda8e0cc5a27.687f6cc0.alx-cod.online)[HTTP](http://fda8e0cc5a27.687f6cc0.alx-cod.online)[3000](http://fda8e0cc5a27.687f6cc0.alx-cod.online:3000)[4000](http://fda8e0cc5a27.687f6cc0.alx-cod.online:4000)[5000](http://fda8e0cc5a27.687f6cc0.alx-cod.online:5000)[5001](http://fda8e0cc5a27.687f6cc0.alx-cod.online:5001)[8000](http://fda8e0cc5a27.687f6cc0.alx-cod.online:8000)[8080](http://fda8e0cc5a27.687f6cc0.alx-cod.online:8080)

#### Port mapping

**SSH**41134

**HTTP**41133

**HTTPS**41132

**3000**41131

**MySQL**41130

**4000**41129

**5000**41128

**5001**41127

**8000**41126

**8080**41125

### Ubuntu 20.04 - Python Network #0

Ubuntu 20.04 with Python and Flask - with a web server running for project `Network #0`

Run
