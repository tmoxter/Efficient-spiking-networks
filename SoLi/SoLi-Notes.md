## Notes and questions regarding the SoLi data and task
### Issues
- No 'test' key in 'file_half.json' file but generate_dataset_into.py looks for that key
- Unclear which file for data preproessing to use first


### Things to think about:
- Modelling inhibitory neurons as simple as only allowing negative weights to downstream neurons?
- See that update rule (optimizer) and surrogate grad usage still works for negative-only weights from I-neurons
- torch syntax refers to entire layers of neurons, how can I individualize the behaviour of a number of neurons within a layer?
