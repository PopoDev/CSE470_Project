# CSE470_Project


## Requirements
- g++ compiler


## Getting Started
Clone the repository
```bash
git clone https://github.com/PopoDev/CSE470_Project.git
```

Download the 15M parameter model trained on the TinyStories dataset
```bash
wget https://karpathy.ai/llama2c/model.bin -P out
```

Compile the code
```bash
g++ run.cpp -o run
```

Run the code
```bash
./run out/model.bin
```
