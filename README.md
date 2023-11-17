# as3_demo
Basic AS3 demo for F5 BIG-IP

This is a basic demo showing how to use the Application Services 3 (AS3) extension on F5 BIG-IP.

AS3 provides a declarative API in which you specify a desired configuration end-state via a JSON declaration.

Here I'll provide a video demo using Postman to configure BIG-IP and also make simple changes to the configuration using AS3.

![image](https://github.com/delgadillo22/as3_demo/assets/23509342/09afa938-c5ea-45c2-a2b7-f0794f8d4722)

File Info:

**Basic AS3 Demo.mp4:**
- Demo video

**Initial Declaration:**

Initial AS3 JSON declaration which enables: 
- Basic HTTP service with single VIP
- 2 pool members
- HTTP monitor
