Presentation Layer (Layer 6) of the OSI Model
The Presentation Layer is the sixth layer of the OSI model. It is responsible for the translation, encryption, and compression of data between 
the application layer and the lower layers. This layer ensures that the data sent from the application layer is in a format that can be understood by the receiving application, 
regardless of differences in data formats between systems.

Functions 

Data Translation: Converts data from the format used by the application into a common format for transmission over the network and vice versa at the destination.
Example: Converting ASCII to EBCDIC or JPEG to GIF.

Data Encryption: Encrypts data before it is transmitted across the network, ensuring privacy and confidentiality.
Example: Using SSL/TLS to encrypt HTTP traffic (HTTPS).

Data Compression: Compresses data to reduce the amount of data transmitted, which improves efficiency and speed.
Example: Compressing images (like in JPEG format) or audio (like MP3).

Data Formatting: Ensures that data is structured in a format that both sender and receiver can understand.
Example: XML or JSON formatting for data exchanged between systems.

Protocols and Technologies in the Presentation Layer
Encryption Protocols:

SSL/TLS – Used for secure communication over a network (e.g., HTTPS).
Data Formats:JPEG, GIF, PNG – Image formats.MPEG, MP3 – Video and audio formats.
Compression:ZIP, GZIP – Compression formats to reduce the size of data.
Character Set Encoding:ASCII, UTF-8, Unicode – Text encoding formats.

Presentation Layer in Cybersecurity
Encryption: One of the most important security measures for protecting sensitive data during transmission.
Data Integrity: Ensures that the data is not altered or tampered with during transmission.
Compression Attacks: Attackers can sometimes use compression algorithms for denial-of-service (DoS) attacks (e.g., Zip Bombs).
