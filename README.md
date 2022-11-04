# network-performance-tester-client

GitHub repo: https://github.com/jrcamenzuli/network-performance-tester-client

The goal of this project is to stress-test a device under various network loads and measure its performance. This test suite can be used to test the performance of the network itself, or monitor an application, for example. These tests can help find regressions or areas of improvement in what is being tested. Various measurements can be made such as: CPU usage, Memory usage, error rate, transfer rate and timings.

## Testing Methodology

All tests require a minimum of two devices:

1. A DUT (device under test)
2. A [server](https://github.com/jrcamenzuli/network-performance-tester-client) that is uncontested and dedicated to the purpose of performance testing. You may also want to directly connect your server to you DUT if you are not interested in measuring the variances of a wireless network.


## Types of tests

### Device Idle Test

This test is used to get a baseline measurement of performance for a system.

### Process Idle Test

This test is used to get a baseline measurement of performance for a OS process.

### HTTP Connection Burst

A burst of HTTP requests made at increasing sizes between rest periods. The test stops when the device's limit has been reached or some predefined maximum burst size has been reached.

### HTTPS Connection Burst

To do.

### HTTP Connection Constant Rate

HTTP requests made at increasing rates between rest periods. The test stops when the device's limit has been reached or some predefined maximum rate size has been reached.

### HTTPS Connection Constant Rate
To do.

### Throughput over HTTP

The maximum throughput that is possible. Throughput will be measured in both directions independently and in both directions at the same time. 

### Throughput over HTTPS

To do.

### Ping

The measured Ping or RTT.

### Jitter

The measured Jitter.

### DNS Burst

A burst of DNS queries made at increasing sizes between rest periods. The test stops when the device's limit has been reached or some predefined maximum query burst size has been reached.

### DNS Rate

DNS queries made at increasing rates between rest periods. The test stops when the device's limit has been reached or some predefined maximum query rate size has been reached.

# network-performance-tester-server

This client complements https://github.com/jrcamenzuli/network-performance-tester-server

