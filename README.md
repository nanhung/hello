## Installatiom

To instal hello-world program, type the following command in linux terminal:

```
wget https://github.com/nanhung/hello/releases/download/v0.1/helloworld-0.1.tar.gz
tar -xzvf helloworld-0.1.tar.gz
rm helloworld-0.1.tar.gz
cd helloworld-0.1
./configure 
make
sudo make install
```

## Execution

```
helloworld
```

---

## Additional info to build tarball from source:

```
aclocal                # Set up an m4 environment
autoconf               # Generate configure from configure.ac
automake --add-missing # Generate Makefile.in from Makefile.am
./configure            # Generate Makefile from Makefile.in
make distcheck         # Use Makefile to build and test a tarball to distribute
```
