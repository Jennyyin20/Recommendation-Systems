# Recommendation-Systems
In this project, I leveraged student engagement data from the course IEOR E4579 to create a recommendation app step by step. This app utilizes AI-generated photos and text and can recommend a feed from over 500,000 pieces of AI generated content.

## build_llm.ipynb
I first built a Generatively Pretrained Transformer (GPT) to generate new text based on input. Big thanks to [Andrej Karpathy](https://www.youtube.com/watch?v=kCc8FmEb1nY) for sharing his ideas. I used this model as a pretrained model, and then changed some settings like the final layer, loss function etc. to build a new model that can predict user interaction on a scale from -1 to 1 (-1 means dislike, 1 means like). The model works well and reaches test MSE of 0.1249.
