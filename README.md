# Fanouts and Percentiles

This is a tool to help visualize latency in a typical "parent-child" or "root-leaf" fanout distributed system design. Specifically we want to ask questions about how the leaf latency distribution affects the overall latency distribution.

You can try it out [here](https://paulcavallaro.com/standalone/fanouts.html)

Here is an example visualization:

![Example Visualization](https://raw.githubusercontent.com/paulcavallaro/fanouts-and-percentiles/master/example-visualization.png)


## Future Work

- [ ] support dropping slow children
- [ ] support retrying slow children
- [ ] support customizing child latency distribution
