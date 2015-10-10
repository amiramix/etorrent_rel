etorrent release repository using builderl instead of relx

    git clone git://github.com/amiramix/etorrent_top.git
    cd etorrent_top
    make get-deps
    make dev
    ./bin/init.esh
    ./bin/start.esh
    to_erl ../ett/shell/
