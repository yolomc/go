## RESTful

##### REST是一种统一的接口定义。`HTTP/1.1`协议中共定义了9种HTTP请求方法，不同的方法规定了不同的操作指定的资源方式。服务端也会根据不同的请求方法做不同的响应。

#### `GET`

`GET`会方法请求指定的页面信息，并返回响应主体，`GET`被认为是不安全的方法，因为`GET`方法会被网络蜘蛛等任意的访问。

#### `HEAD`

`HEAD`方法与`GET`方法一样，都是向服务器发出指定资源的请求。但是，服务器在响应`HEAD`请求时不会回传资源的内容部分，即：响应主体。这样，我们可以不传输全部内容的情况下，就可以获取服务器的响应头信息。`HEAD`方法常被用于客户端查看服务器的性能。

#### `POST`

`POST`请求会 向指定资源提交数据，请求服务器进行处理，如：表单数据提交、文件上传等，请求数据会被包含在请求体中。常用于数据的提交，新增操作。

#### `PUT`

`PUT`请求会身向指定资源位置上传其最新内容，侧重于对于数据的修改操作。

#### `DELETE`

`DELETE`请求用于请求服务器删除所请求`URI`（统一资源标识符，Uniform Resource Identifier）所标识的资源。`DELETE`请求后指定资源会被删除。

#### `CONNECT`

`CONNECT`方法是`HTTP/1.1`协议预留的，能够将连接改为管道方式的代理服务器。通常用于[SSL](http://itbilu.com/other/relate/N16Uaoyp.html)加密服务器的链接与非加密的HTTP代理服务器的通信。

#### `OPTIONS`

`OPTIONS`请求与`HEAD`类似，一般也是用于客户端查看服务器的性能。 这个方法属于浏览器的预检请求，查看服务器是否接受请求，预检通过后，浏览器才会去发get，post，put，delete等请求。JavaScript的[XMLHttpRequest](http://itbilu.com/javascript/js/VkiXuUcC.html)对象进行`CORS`跨域资源共享时，就是使用`OPTIONS`方法发送嗅探请求，以判断是否有对指定资源的访问权限。 

#### `TRACE`

`TRACE`请求服务器回显其收到的请求信息，该方法主要用于HTTP请求的测试或诊断。

#### `PATCH`

`PATCH`方法出现的较晚(2010年)。`PATCH`请求与`PUT`请求类似，同样用于资源的更新。二者有以下两点不同：

- `PATCH`一般用于资源的部分更新，而`PUT`一般用于资源的整体更新。
- 当资源不存在时，`PATCH`会创建一个新的资源，而`PUT`只会对已在资源进行更新。





## HTTP/HTTPS、TCP/IP、UDP、SNMP 协议



## Socket



## WebSocket



## 用户认证 Authentication/OAuth/JWT



## 安全与加密

##### CSRF攻击 

##### 输入过滤

##### XSS攻击

##### SQL注入

##### 存储密码

##### 加密解密

RAS、AES、DES加密





