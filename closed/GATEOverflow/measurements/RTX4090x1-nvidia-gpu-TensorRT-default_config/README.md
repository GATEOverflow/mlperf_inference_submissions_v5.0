| Model    | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   | TEST04   |
|----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|----------|
| resnet50 | server       |     76.078 |     35342.5  | -                 |                                   | passed   | passed   |
| resnet50 | multistream  |     76.064 |     17094    | 0.468             |                                   | passed   | passed   |
| resnet50 | offline      |     76.078 |     43797.8  | -                 |                                   | passed   | passed   |
| resnet50 | singlestream |     76.064 |      3610.11 | 0.277             |                                   | passed   | passed   |