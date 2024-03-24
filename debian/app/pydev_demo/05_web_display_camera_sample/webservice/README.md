English| [简体中文](./README_cn.md)

# aiexpress_webserver

Includes nginx service and web pages that are compatible with the ai-express unified web client.

The PC web page communicates with the X3-side WebDisplayPlugin based on the web socket protocol, obtaining jpg images and serialized perception results sent by WebDisplayPlugin, deserializing the perception results, and then rendering and displaying them.

# Instructions
1. Copy this folder to the device
2. Start the service: ./sbin/nginx -p .
3. Access:
    Web display terminal: http://IP