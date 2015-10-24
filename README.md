# NAME

 mrkvw - Live markdown viewer

# SYNOPSIS

    $ mrkvw --port=7000 [markdown file]
    http server is ready: http://127.0.0.1:7000/ (pid:xxxxxx)

    -> open browser and access to http://127.0.0.1:7000 

# INSTALL

    $ git clone https://github.com/magnolia-k/p6-mrkvw.git
    $ cd p6-mrkvw
    $ panda install HTTP::Server::Tiny
    $ panda install WebSocket::P6SGI
    $ panda install Text::Markdown
