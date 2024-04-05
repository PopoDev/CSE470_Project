# CSE470_Project


## Requirements
- gcc compiler
- g++ compiler


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
