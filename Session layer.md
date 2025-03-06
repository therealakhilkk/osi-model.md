Session Layer (Layer 5) of the OSI ModelThe Session Layer is the fifth layer of the OSI model. It is responsible for establishing, maintaining, 
and terminating communication sessions between applications on different devices.This layer ensures that a session is properly managed, 
allowing data to be synchronized and exchanged efficiently.

Functions 

Session Establishment, Maintenance, and Termination
Creates and manages a session between two communicating devices.
Example: Logging into a remote server using SSH.

Synchronization
Inserts checkpoints (synchronization points) in long data transfers to ensure recovery in case of failure.
Example: If a file download is interrupted, resuming from the last checkpoint instead of starting over.

Dialog Control
Determines whether communication is half-duplex (one-way at a time) or full-duplex (both ways simultaneously).
Example: Video calls require full-duplex communication, while walkie-talkies use half-duplex.

Authentication and Authorization
Ensures that users or devices are properly authenticated before establishing a session.
Example: Logging into a secure website using a username and password.

Session Recovery
If a session is interrupted, it can recover from the last known good state.
Example: Online banking transactions need session recovery to prevent data loss in case of a timeout.

Session Layer in Cybersecurity
Session Hijacking: Attackers may intercept or take control of active sessions (e.g., stealing session cookies in web applications).
Secure Authentication: Uses encryption and secure authentication mechanisms to prevent unauthorized access.
Session Timeout Policies: Automatically logs out inactive users to prevent unauthorized access (e.g., banking apps logging out users after inactivity).

Here are some common types of attacks that target the Session layer

Session Hijacking,
Session Fixation,
Man-in-the-Middle (MitM) Attacks,
Cross-Site Request Forgery (CSRF),
Session Sidejacking.
