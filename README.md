# Boost-CppBuilder
A guide for setting up Boost in C++ projects.

## Installation Steps

#### Option 1: Download and Build from Source
1. Download the latest version of Boost from the [official GitHub repository](https://github.com/boostorg/boost) or from the [official website](https://www.boost.org/), and save the tar.gz file.
    ```bash
    cd Documents
    wget https://archives.boost.io/release/1.82.0/source/boost_1_82_0.tar.gz
    ```
2. **Extract the archive and move it to your Documents directory:**
    ```bash
    tar -xzvf boost_1_82_0.tar.gz
    cd ~/Documents/boost_1_82_0
    ```

    ```bash
    ./bootstrap.sh
    ./b2 install
    ```

#### Option 2: Using a Package Manager

##### For Debian/Ubuntu:
```bash
sudo apt-get install libboost-all-dev
```


## Reference
- **boost setting Started** [boost Install Document](https://www.boost.org/doc/libs/1_82_0/more/getting_started/unix-variants.html)
