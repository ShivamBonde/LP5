if g++ is not installed then 
sudo apt update
sudo apt install g++
sudo apt install build-essential

FOR CPP:-
to create file->nano bfs.cpp

to save->CTRL + O
ENTER
to exit->CTRL + X

to compiler->
g++ bfs.cpp -fopenmp -o bfs
or
g++ -fopenmp bfs.cpp -o bfs

to run->
./bfs


FOR CUDA:-
step 1- open terminal

step 2-type- 
    nvcc --version

step 3-create/open file
    nano vectorAdd.cu

step 4-write code

step 5-save file
      control + O

step 6 exit file
    control + X

step 7-compiler code
    nvcc vectorAdd.cu -o vectorAdd

step 8- run code
    ./vectorAdd

for DL EXP1- housing.csv
for DL EXP2- imdb dataset
for DL EXP3- import from tensonflow ->fashionmnist
