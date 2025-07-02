# Webserv

Webserv is our own HTTP server written in C++98.

The goal of this project was to help us understand how HTTP really works by building a web server from scratch. We can test it with any web browser and see how it handles real web requests.

Our server can:

- Listen on one or more ports.
- Handle multiple clients at the same time without blocking.
- Support the HTTP methods GET, POST, and DELETE.
- Serve static files and directories.
- Run CGI scripts to deliver dynamic content.
- Allow file uploads through POST requests.
- Use a configuration file to set options like ports, routes, and error pages.
- Respond with correct HTTP status codes and headers.

We made sure our server never crashes and works well with standard web browsers.

This project taught us a lot about networking, non-blocking input/output, and how servers work behind the scenes.

---

To run our server:

```bash
./webserv [path_to_config_file]
