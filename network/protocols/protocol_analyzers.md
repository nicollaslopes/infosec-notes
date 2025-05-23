# Protocol Analyzers

A great command-line protocol analyzer is `tcpdump`.

You can capture traffic for a given protocol (e.g. icmp) using the following command:

```bash
$ sudo tcpdump -v -i enp2s0 icmp
```

If you want the capture to be saved to a file, we can use it like this:

<figure><img src="../../.gitbook/assets/tcpdump-1.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/tcpdump-1-2.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/tcpdump-1-3.png" alt=""><figcaption></figcaption></figure>
