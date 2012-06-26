# at-at changelog

## 0.8.0
_26th June 2012_

* Added `without-osc-bundle` to allow specific OSC messages generated
  within a call to `in-osc-bundle` to pass through unbundled. Likely to
  be rarely used. Prefer not using this unless explicitly required.
* Type hint message sending aspects of code for faster performance
* Wait for longer before timing out the send operation
* Increase size of initial send queue
* Updated dependency on `at-at` to 1.0.0
