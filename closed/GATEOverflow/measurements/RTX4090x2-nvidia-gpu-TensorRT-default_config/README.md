| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | multistream  |     37.33  |     1423.74  | 5.619             |                                   | passed   |
| retinanet | singlestream |     37.343 |      581.058 | 1.721             |                                   | passed   |
| retinanet | server       |     37.364 |     1414.96  | -                 |                                   | passed   |
| retinanet | offline      |     37.363 |     1741.05  | -                 |                                   | passed   |