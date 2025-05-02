| Model     | Scenario     |   Accuracy |   Throughput | Latency (in ms)   | Power Efficiency (in samples/J)   | TEST01   |
|-----------|--------------|------------|--------------|-------------------|-----------------------------------|----------|
| retinanet | server       |     37.351 |      637.534 | -                 |                                   | passed   |
| retinanet | multistream  |     37.304 |      733.407 | 10.908            |                                   | passed   |
| retinanet | offline      |     37.305 |      862.035 | -                 |                                   | passed   |
| retinanet | singlestream |     37.338 |      570.125 | 1.754             |                                   | passed   |