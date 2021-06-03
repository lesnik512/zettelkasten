- depend in the direction of stability. Any volatile component should not be depend on a component that is difficult to change.

I (Instability) = Fan–out/(Fan–in + Fan–out). This metric has the range [0, 1]. I = 0 indicates a maximally stable component. I = 1 indicates a maximally unstable component.

SDP says that the I metric of a component should be larger than the I metrics of the components that it depends on.
## Related
- [[principles of component cohesion]]