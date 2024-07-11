# ZRAMer
### Auto ZRAM generator shell script. That you can use in any init system!
## How to use
To **enable** or **update** ZRAM, you just need to run ```zramer```. It will automatically pick your total RAM and CPU threads.

To customize them add these flags:
* ```-t``` or ```cpu``` - CPU threads number
* ```-m``` or ```mem``` - Gb of RAM number
* ```-c``` or ```alg``` - Compression algorithm (lzo,lzo-rle,lz4,lz4hc,842,zstd)

To **disable** ZRAM, just run ```zramer off``` or ```zramer -s```
