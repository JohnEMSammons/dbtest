--dbtest--

initial testing of cmake and sqlite

the basic code creates a few entries in a new sqlite db.



To test be sure the sqlite dev files are installed:

sudo apt install gcc cmake g++ cmake-doc ninja-build libsqlite3-dev sqlitebrowser


download code.

mkdir build

cd build

cmake ../

make

./dbtest 

Opened database successfully

Table removed successfully

Table created successfully

Records created successfully
