## Ping within IPYTHON.

<!-- IPV4/V6 Ping --> 

- Use the `!` magic of IPYTHON

> In IPython syntax, the exclamation mark (`!`) allows users to run `shell commands` from inside a Jupyter Notebook code cell

```python
In [1]: !ping www.google.com

Pinging www.google.com [142.250.74.132] with 32 bytes of data:
Reply from 142.250.74.132: bytes=32 time=155ms TTL=47
Reply from 142.250.74.132: bytes=32 time=138ms TTL=47
Reply from 142.250.74.132: bytes=32 time=136ms TTL=47
Reply from 142.250.74.132: bytes=32 time=140ms TTL=47

Ping statistics for 142.250.74.132:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 136ms, Maximum = 155ms, Average = 142ms
```
