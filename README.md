## Masked/Not masked

## Networks(Results)
> To Beat : 0.9787 (20 epochs)
- resnet50 + AdamW (pretrained)
    - wd = 10e-4, lr = 3e-4, 7 epochs, 64x64
        - 99.27%
    - no dropout
        - underfitting like hell
        - 98.54%
- vgg16 + AdamW (pretrained)
    - wd = 10e-4, lr = 3e-4, 5 epochs, 64x64
        - 98. something

## Conclusion
- vgg16 ~ resnet50
- weight decay is awesome

> Beat :)
