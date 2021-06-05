# usher

```bash
sudo apt install build-essential wget cmake libboost-all-dev libprotoc-dev libprotoc-dev protobuf-compiler rsync
cd v0.3/source
mkdir -p usher_build && cd usher_build
cmake -DTBB_DIR=${PWD}/../oneTBB-2019_U9  -DCMAKE_PREFIX_PATH=${PWD}/../oneTBB-2019_U9/cmake ..
make -j 30
```