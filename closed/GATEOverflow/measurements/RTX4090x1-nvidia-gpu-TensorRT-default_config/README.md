| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | server       |     37.374 |      637.533 | -                 |                                   | passed   |
| retinanet | multistream  |     37.289 |      733.474 | 10.907            |                                   | passed   |
| retinanet | offline      |     37.354 |      865.429 | -                 |                                   | passed   |
| retinanet | singlestream |     37.336 |      572.41  | 1.747             |                                   | passed   |