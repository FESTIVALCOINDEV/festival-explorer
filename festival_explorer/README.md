# FESTIVAL Blockchain Explorer
This is a block explorer for the fest currency.

#### Installation

1) It takes data from daemon kepld. It should be accessible from the Internet. Run festivald with open port as follows:
```bash
./festivald --enable-cors=* --enable_blockexplorer
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
