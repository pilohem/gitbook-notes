# Continuous Integration/Delivery

### Differences between CI and CD

![Source: DeepLearnig.ai](<../../../.gitbook/assets/image (12).png>)

![Source: DeepLearnig.ai](<../../../.gitbook/assets/image (10).png>)

All together...

![Source: DeepLearnig.ai](<../../../.gitbook/assets/image (11).png>)

CI handles Unit Testing: Testing that each component in the pipeline produces the expected artifacts.

Unit Testing can be done in:

* Data
  * Testing feature engineering logic
  * Test the actual values of the features
  * Test the output format
* Model
  * Testing the model methods
  * Model performance
  * Avoid NaNs, empty values, or strings
  * Avoid inherent bias

To implement the unit tests you can work with a mock dataset, but you should make sure this dataset covers the edge and corner cases. Also, this mock data must sparsely cover the "real" data but it should be a smaller dataset.
