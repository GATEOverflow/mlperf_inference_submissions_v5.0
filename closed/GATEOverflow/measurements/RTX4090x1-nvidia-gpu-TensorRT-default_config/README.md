| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | server       |     37.355 |      637.538 | -                 |                                   | passed   |
| retinanet | multistream  |     37.339 |      734.012 | 10.899            |                                   | passed   |
| retinanet | offline      |     37.346 |      861.441 | -                 |                                   | passed   |
| retinanet | singlestream |     37.322 |      570.776 | 1.752             |                                   | passed   |