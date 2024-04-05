# CSE470_Project


## Requirements
- gcc compiler


## Getting Started
Clone the repository
```bash
git clone https://github.com/PopoDev/CSE470_Project.git
```

Download the 15M parameter model trained on the TinyStories dataset
```bash
wget https://huggingface.co/karpathy/tinyllamas/resolve/main/stories15M.bin -P models/
```

Compile the code
```bash
make run
```

Run the code
```bash
./run models/stories15M.bin
```

## Optimization
Enable fast math optimization
```bash
make runfast
./run models/stories15M.bin
```

Enable OpenMP parallelization. OpenMP is a compiler directive that allows the compiler to parallelize the code.
```bash
make runomp
OMP_NUM_THREADS=4 ./run models/stories15M.bin
```