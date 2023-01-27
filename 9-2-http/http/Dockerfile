FROM ajnouri/nginx

RUN echo "set encoding=utf-8\nset fileencodings=iso-2022-jp,euc-jp,sjis,utf-8\nset fileformats=unix,dos,mac" >> ~/.vimrc \
    && . ~/.vimrc
ADD http://cs.nislab.io/class/index.html /usr/share/nginx/html/

RUN chmod 644 /usr/share/nginx/html/index.html