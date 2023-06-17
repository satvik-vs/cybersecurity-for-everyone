# introduction to OSI Model

**Introduction:**

In the realm of computer networks, the OSI (Open Systems Interconnection) model serves as a fundamental framework for understanding and implementing effective communication protocols. Developed in the 1980s by the International Organization for Standardization (ISO), the OSI model offers a systematic approach to networking that ensures seamless data transfer between interconnected devices. In this blog post, we will delve into the OSI model, exploring its seven layers and their significance in enabling reliable and efficient network communication.

<figure><img src="../../.gitbook/assets/osi_model_7_layers.png" alt=""><figcaption></figcaption></figure>

**1. Layer 1: Physical Layer:**

At the lowest level of the OSI model, the Physical Layer deals with the transmission of raw data bits over the physical medium. It encompasses various aspects such as electrical, mechanical, and functional specifications of the physical media, including cables, connectors, and network interfaces. This layer defines characteristics like voltage levels, data transfer rates, and synchronization methods.

**2. Layer 2: Data Link Layer:**

The Data Link Layer focuses on the reliable transmission of data frames between directly connected devices. It establishes and terminates logical connections, performs error detection and correction, and manages flow control. Ethernet and Wi-Fi are examples of protocols that operate at this layer.

**3. Layer 3: Network Layer:**

The Network Layer enables the transfer of data packets across different networks. It handles logical addressing, routing, and packet forwarding to ensure that data reaches its destination by choosing the most efficient path. [Internet Protocol (IP)](../ip-address/) is a key protocol that operates at the Network Layer.

**4. Layer 4: Transport Layer:**

Sitting between the upper layers and the lower layers, the Transport Layer ensures reliable end-to-end data delivery. It provides mechanisms for segmentation, reassembly, error recovery, and flow control. Transmission Control Protocol (TCP) and User Datagram Protocol (UDP) are two well-known protocols operating at this layer.

**5. Layer 5: Session Layer:**

The Session Layer establishes, manages, and terminates communication sessions between applications running on different devices. It enables synchronization and coordination, allowing for reliable data exchange. This layer is responsible for establishing checkpoints and restoring sessions in case of failures.

**6. Layer 6: Presentation Layer:**

The Presentation Layer focuses on data representation, ensuring that information is properly formatted and encoded for compatibility between different systems. It handles tasks such as data encryption, compression, and conversion between different data formats. Common formats like JPEG, ASCII, and MPEG operate at this layer.

**7. Layer 7: Application Layer:**

At the topmost layer of the OSI model, the Application Layer directly interacts with end-users and provides network services to applications. It encompasses protocols and services such as HTTP, FTP, [DNS](../dns.md), and SMTP. This layer allows users to access network resources, browse websites, send emails, and more.

**We will now dive into each of these 7 layers in detail ❤ 👍**
