# Vision Transformer (ViT)

Use a transformer to classify images.

# Transfer Learning
fine-tuning a pre-trained model

```python
model = get_model_from_hf(model_name)
freeze_weights(model)
train(model, data)
```

- Get a pre-trained model
    - which model? how do we find one that is good for our task?


- Freeze the weights
    - what does 'freezing' mean?
    - why do we do this? benefits?
    - which weights? how do we know which ones?
