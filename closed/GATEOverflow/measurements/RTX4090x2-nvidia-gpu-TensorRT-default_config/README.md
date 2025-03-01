| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | multistream  |     37.351 |     1415.68  | 5.651             |                                   | passed   |
| retinanet | singlestream |     37.351 |      580.383 | 1.723             |                                   | passed   |
| retinanet | server       |     37.311 |     1414.96  | -                 |                                   | passed   |
| retinanet | offline      |     37.32  |     1733.88  | -                 |                                   | passed   |