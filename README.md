# BAFFS
sudo apt-get install libfuse3-dev
mkdir build
cd build
cmake ../fs
cmkae --build .


SPDLOG_LEVEL=debug ./debloated_fs --realdir=/home/ubuntu/repos/BAFFS/build/real --lowerdir=/home/ubuntu/repos/BAFFS/build/lower --optimize=l0 -d /home/ubuntu/repos/BAFFS/build/mount

ls ./mount/aaa
Not support create file

 ./build/baffs shadow  --images=file_reader:latest
 ./build/baffs debloat  --images=file_reader:latest 
 must run with tags