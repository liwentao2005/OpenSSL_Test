# OpenSSL_Test
**The main role of the project: OpenSSL's usage**  
**Note: Clone this repository to E:/GitCode/ in windows**
- open source library version:
	- OpenSSL: 1.0.1g, [GitHub](https://github.com/openssl/openssl/releases?after=OpenSSL_1_0_2-beta3)
	- b64: [GitHub](https://github.com/littlstar/b64.c)
	- http-parser: [GitHub](https://github.com/nodejs/http-parser)
	- curl: 7.44.0, [url](https://curl.haxx.se/)
	- gRPC: v1.23.0 [GitHub](https://github.com/grpc/grpc)
- test code include:
	- OpenSSL
		- RC4 encrypt and decrypt
		- DES encrypt and decrypt
		- RSA encrypt and decrypt
		- AES encrypt and decrypt
		- MD5's usage
		- HMAC's usage
	- base64's usage
	- http-parser's usage
	- curl's usage
	- gRPC's usage(only support Linux)
	- socket

**The project support platform:** 
- windows7/10 64 bits: It can be directly build with VS2013 in windows7/10 64bits.
- Linux: It supports cmake build(file position: prj/linux_cmake_OpenSSL_Test)
- Linux: It supports cmake build(file position: prj/linux_cmake_gRPC_Test)

**Windows VS Screenshot:**  
![](https://github.com/fengbingchun/OpenSSL_Test/blob/master/prj/x86_x64/Screenshot.png)

**Blog:** [fengbingchun](https://blog.csdn.net/fengbingchun/article/category/2628015)
