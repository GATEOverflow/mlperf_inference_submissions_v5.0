| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | server       |     37.344 |      637.533 | -                 |                                   | passed   |
| retinanet | multistream  |     37.29  |      731.864 | 10.931            |                                   | passed   |
| retinanet | offline      |     37.312 |      862.965 | -                 |                                   | passed   |
| retinanet | singlestream |     37.319 |      570.125 | 1.754             |                                   | passed   |