Install pyenv:

```bash
$ brew install pyenv
````

install miniconda:

- [Installing on macOS — conda 23.1.0 documentation](https://docs.conda.io/projects/conda/en/23.1.x/user-guide/install/macos.html)

```bash
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh -O ~/miniconda.sh
bash ~/miniconda.sh -b -p $HOME/miniconda
```

install the env:

```bash
❯ conda env create -f env.yml
```

init the conda:

```bash
❯ ~/miniconda/bin/conda init
```

if you are using fish:

```bash
❯ ~/miniconda/bin/conda init fish
```

activate the env:

```bash
$ conda activate my_env
```

install the tensorflow:

- [Tensorflow Plugin - Metal - Apple Developer](https://developer.apple.com/metal/tensorflow-plugin/)
- [Installing with conda — conda 25.1.1 documentation](https://docs.conda.io/projects/conda/en/stable/user-guide/concepts/installing-with-conda.html)

```bash
$ conda install tensorflow
```

run the test script:

```bash
❯ python test.py
```

training process:

<img width="1512" alt="1361739788314_ pic" src="https://github.com/user-attachments/assets/11ef8cac-6540-4d8f-9084-e20c3b10faed" />

<img width="800" alt="1351739788303_ pic" src="https://github.com/user-attachments/assets/9001ec0e-7d89-4c7d-92f2-312e91623144" />

to update the deps:

```bash
► conda env update -f env.yml
```

<img width="828" alt="image" src="https://github.com/user-attachments/assets/8d91ca84-429a-4475-ac20-94755797ff27" />

to install the `transformers` on the ARM chip based Apple computer, you need to install Rust `x86` firstly:

```bash
❯ rustup target add x86_64-apple-darwin                                                                                                                         (my_env) 10:37:34
info: downloading component 'rust-std' for 'x86_64-apple-darwin'
info: installing component 'rust-std' for 'x86_64-apple-darwin'
 27.8 MiB /  27.8 MiB (100 %)  25.7 MiB/s in  1s ETA:  0s
```

Or you will meet this problem:

<img width="1382" alt="image" src="https://github.com/user-attachments/assets/efdeaf5d-c07a-4165-b27d-b66054ebe6ab" />

