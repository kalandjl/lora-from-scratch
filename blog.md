## Day 1: 2025-6-19

**Today's Goal:** Read LoRa paper, watch videos and grasp the key concepts and implementation

**Key Accomplishments:**
* Watched videos on LLM architecture to refresh my knowledge
* Read the LoRa paper
* Watched YT videos on LoRa

**Notes:**
* Today was a good start to the project, and I feel like I built a good base of understanding to start implementing the LoRa method in coding. 

## Day X: YYYY-MM-DD

**Today's Goal:** [Write a single sentence about what you aimed to do today.]

**Key Accomplishments:**
* [Accomplishment #1 - e.g., "Read the LoRA paper twice and took notes on Section 3."]
* [Accomplishment #2 - e.g., "Set up Google Colab environment with PyTorch and Transformers."]
* [Accomplishment #3]

**Major Challenge(s):**
* [Describe the main problem you hit. e.g., "The math in the paper for the scaling factor 'alpha' was confusing at first."]
* [e.g., "Ran into a CUDA version mismatch when installing dependencies."]

**Key Code Snippet(s):**
* [Paste a small code block that was important or tricky. Add a one-line comment.]

```python
# Example: Initializing the LoRA matrices
self.lora_A = nn.Parameter(self.weight.new_zeros((rank, self.in_features)))
self.lora_B = nn.Parameter(self.weight.new_zeros((self.out_features, rank)))