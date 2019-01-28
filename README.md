# yaz_cmd_tcl
## Requires 
* `tcl`
* [http://zoom.z3950.org/bind/tcl/](http://zoom.z3950.org/bind/tcl/)
  * ~~[http://gondolin.hist.liv.ac.uk/~cheshire/zoom/tcl.html](http://gondolin.hist.liv.ac.uk/~cheshire/zoom/tcl.html)~~ DOWN

* needs libyaz from yaz toolkit
  * [https://www.indexdata.com/resources/software/yaz/](https://www.indexdata.com/resources/software/yaz/)
  * [http://ftp.indexdata.dk/pub/yaz/yaz-5.27.1.tar.gz](http://ftp.indexdata.dk/pub/yaz/yaz-5.27.1.tar.gz)
    * `./buildconf.sh`
    * `./configure`
    * `make`
    * `sudo make install`
  * or
    * `./buildconf.sh`
    * `./configure --prefix=$HOME/myapps`
    * `make`
    * `make install`
    * ...
    * Add `export PATH="$HOME/myapps/bin:$PATH"` to `.bashrc`
    * (Reload file with `source ~/.bashrc`
