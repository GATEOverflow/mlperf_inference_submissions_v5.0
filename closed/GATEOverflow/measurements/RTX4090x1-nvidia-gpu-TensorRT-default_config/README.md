| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| resnet50 | server       |     76.078 |     35342.5  | -                 |                                   | passed   | passed   |
| resnet50 | multistream  |     76.064 |     16877.6  | 0.474             |                                   | passed   | passed   |
| resnet50 | offline      |     76.078 |     43650.6  | -                 |                                   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      3610.11 | 0.277             |                                   | passed   | passed   |