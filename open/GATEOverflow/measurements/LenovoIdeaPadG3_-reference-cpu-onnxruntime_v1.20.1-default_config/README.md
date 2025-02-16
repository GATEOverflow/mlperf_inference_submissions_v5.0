| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   |
|----------|--------------|------------|--------------|-------------------|
| resnet50 | offline      |     76.456 |       42.138 | -                 |
| resnet50 | singlestream |     76.456 |       21.24  | 47.081            |
| resnet50 | multistream  |     76.456 |       33.009 | 242.356           |