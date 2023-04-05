# tcptools
## Using "ping"
### What were the min/avg/max/stddev statistics for each?
**www.amazon.com:**
* **Ping One:** *min:* 9ms *avg:* 19ms *max:* 31ms *stddev:* I have a windows and this field doesn't populate
* **Ping Two:** *min:* 9ms *avg:*  11ms *max:* 17ms *stddev:* I have a windows and this field doesn't populate
* **Ping Three:** *min:* 9ms *avg:* 14ms *max:* 28ms *stddev:* I have a windows and this field doesn't populate

**www.google.com**
* **Ping One:** *min:* 8ms *avg:* 8ms *max:* 9ms *stddev:* I have a windows and this field doesn't populate
* **Ping Two:** *min:* 8ms *avg:* 8ms *max:* 10ms *stddev:* I have a windows and this field doesn't populate
* **Ping Three:** *min:* 7ms *avg:* 26ms *max:* 65ms *stddev:* I have a windows and this field doesn't populate

**www.microsoft.com**
* **Ping One:** *min:* 9ms *avg:* 11ms *max:* 14ms *stddev:* I have a windows and this field doesn't populate
* **Ping Two:** *min:* 8ms *avg:* 15ms *max:* 30ms *stddev:* I have a windows and this field doesn't populate
* **Ping Three:** *min:* 6ms *avg:* 9ms *max:* 14ms *stddev:* I have a windows and this field doesn't populate
### Was there any packet loss on any of the pings?
* **www.amazon.com:** No packets lost on any of the three pings.
* **www.google.com:** No packets lost on any of the three pings.
* **www.microsoft.com:** No packets lost on any of the three pings.
### Did the IP address change for a given website between pings?
* **www.amazon.com:** Yes the IP address changed between pings 2 and 3, but was the same for ping one. For pings one and two it was 18.65.233.187, for ping three it was 18.172.169.208.
* **www.google.com:** No the IP address did not change for Google, it was 142.250.69.196 for all pings.
* **www.microsoft.com:** No the IP address did not change for Microsoft, it was 23.45.229.117 for all pings.

## Using "tracert"
### What was the target server's IP address?
**www.amazon.com:**
* 18.172.169.208

**www.google.com:**
* 142.250.68.196
### How many hops were needed to reach the target?
**www.amazon.com:**
* 17, and hops 11-15 requests timed out.

**www.google.com:**
* 11
### Can you identify your ISP from the intermediate server DNS names?
* Yes I can tell my ISP from the intermediate server DNS names, because they show they are hopping through comcast.net in the intermediate server DNS names for all three targets.
### Identify the "class" of IP address for each major step in the trip
**www.amazon.com:**
* Step 1: Class C
* Steps 2-10 and 16-17: Class A
* Steps 11-15: Timed out, no IP adress

**www.google.com:**
* Step 1: Class C
* Steps 2-8: Class A
* Steps 9-11: Class B
