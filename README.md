# usher

```bash
sudo apt install build-essential wget cmake libboost-all-dev libprotoc-dev libprotoc-dev protobuf-compiler rsync
cd v0.3/source
wget https://github.com/oneapi-src/oneTBB/archive/2019_U9.tar.gz
tar -xvzf 2019_U9.tar.gz
mkdir -p build && cd build
cmake  -DTBB_DIR=${PWD}/../oneTBB-2019_U9  -DCMAKE_PREFIX_PATH=${PWD}/../oneTBB-2019_U9/cmake ..
make -j 4
```