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
❯ conda env create -f env.yml                                                                                                                                     (base) 18:07:18
```

init the conda:

```bash
❯ ~/miniconda/bin/conda init
```

```bash
❯ ~/miniconda/bin/conda init fish
```

activate the env:

```bash
$ conda activate my_env
```

install the tensorflow:

- [Tensorflow Plugin - Metal - Apple Developer](https://developer.apple.com/metal/tensorflow-plugin/)

install the tensorflow:

- [Installing with conda — conda 25.1.1 documentation](https://docs.conda.io/projects/conda/en/stable/user-guide/concepts/installing-with-conda.html)

```bash
$ conda install tensorflow
```

```bash
$ conda install tensorflow-macos
```

run the test script:

```bash
❯ python test.py
```

