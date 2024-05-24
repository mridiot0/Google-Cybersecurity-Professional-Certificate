### Question 1
#### Why is network traffic monitoring important in cybersecurity? Select two answers.

* It provides a method of classifying critical assets.
* It provides a method to encrypt communications.
* [x] It helps identify deviations from expected traffic flows.
* [x] It helps detect network intrusions and attacks.

### Question 2
#### What tactic do malicious actors use to maintain and expand unauthorized access into a network?

* Data size reduction
* Phishing
* [x] Lateral movement
* Exfiltration

### Question 3
#### Fill in the blank: The transmission of data between devices on a network is governed by a set of standards known as _____.

* [x] protocols
* ports
* payloads
* headers

### Question 4
#### Do packet capture files provide detailed snapshots of network communications?

* [x] Yes. Packet capture files provide information about network data packets that were intercepted from a network interface.
* No. Packet capture files do not contain detailed information about network data packets.
* Maybe. The amount of detailed information packet captures contain depends on the type of network interface that is used.

### Question 5
#### Fill in the blank: tcpdump is a network protocol analyzer that uses a(n) _____ interface.

* Linux
* graphical user
* [x] command-line
* internet

### Question 6
#### Which protocol version is considered the foundation for all internet communications?

* UDP
* HTTP
* ICMP
* [x] IPv4

### Question 7
#### Which IPv4 header fields involve fragmentation? Select three answers.

* Type of Service
* [x] Identification
* [x] Fragment Offset
* [x] Flags

### Question 8
#### Which IPv4 field uses a value to represent a standard, like TCP?

* Total Length
* Version
* Type of Service
* [x] Protocol

### Question 9
#### Which tcpdump command outputs detailed packet information?

* `sudo tcpdump -v any -i`
* [x] `sudo tcpdump -i any -v`
* `sudo tcpdump -i any -n`
* `sudo tcpdump -i any -c 100`

### Question 10
#### Examine the following tcpdump output:

`22:00:19.538395 IP (tos 0x10, ttl 64, id 33842, offset 0, flags [P], proto TCP (6), length 196) 198.168.105.1.41012 > 198.111.123.1.61012: Flags [P.], cksum 0x50af (correct), seq 169, ack 187, win 501, length 42`

#### What is the source IP address?

* `22:00:19.538395`
* `41012`
* [x] `198.168.105.1`
* `198.111.123.1`