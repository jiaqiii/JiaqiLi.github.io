---
layout: essay
type: essay
title: Quantum Computing
# All dates must be YYYY-MM-DD format!
date: 2018-01-15
labels:
  - Cyber Security
  - Quantum computer
  - Quantum cryptography
  - Post Quantum Cryptography
  - Modern Cryptography
  - Learning
---

    In modern cryptography, a prevalent method to protect one’s privacy is the PKI encryption, which is an algorithm method being used to securely exchange private keys. The invention of public key decreases the exposure of vulnerability during the transferring process of the private key. It resolved the inconvenient in where users have to physically exchange symmetric key method for security purpose before it is invented. The PKI hashing algorithm is constantly changing for the purpose of keeping hashing method secure and updated. However, with the maturing technology in quantum computing, it could threaten the security of PKI encryption.

    To further understand how quantum computing could become a threat to modern cryptography such as PKI encryption, RSA encryption and Elliptic curve cryptography, we can take a look at how quantum computer works.
We all know that a classical computer stores data in bit, and each bit of data stores either 0 or 1 as a possible outcome. In comparison, quantum computer stores data in qubit, and each qubit stores a value of either 0 or 1. Nonetheless, a qubit can store a value of both 0 and 1. This is because a particle could be pointing up, or down, or both up and down with different percentage for each direction. This particle could be a photon, an electron, or a nucleus, it is the physical storage of the unit qubit. With the special quality of qubit, it stores 2^n possible outcomes for every n possible outcomes a bit could store. For instance, a bit could store 2 possible outcomes, 0 or 1, while a qubit is able to store 2^2 possible outcomes, which is 4. This quality allows the storage of information in quantum computer increases exponentially as the storage of information increased in a classical computer.

    Let’s take PKI encryption for an example again. As mentioned earlier, this method uses mathematical algorithm to encrypt a private key algorithm. A secure and up-to-date mathematical algorithm would take a classical computer years to figure it out. However, with the exponentially growing calculating speed of a quantum computer, figuring out the algorithm would not take long at all. This is the reason why quantum computer is threatening the security of modern cryptography. 
There are different types of cryptography that is believed to be secure under quantum attack. One of them is lattice-based cryptography. Which is a method that utilizes the “difficulty of finding the nearest point in a lattice with hundreds of spatial dimensions”. This is however, a fairly new method and it is still at a very experimental stage. Other fairly new quantum-secure methods also include code-based cryptography which is “associate with an error-correcting code and the public key with a scrambled and erroneous version of the code”, and multivariate cryptography which “rely on the hardness of solving systems of multivariate polynomial equations”. 

    There are also other mathematical methods that are used to protect one’s privacy under quantum attack. Examples of those such as Mcbit, Things, and New Hope. These methods attempt to use longer keys that even quantum computer might have problem solving in a short amount of time. However, a longer key takes up space. Imagine one have to download a one megabyte key for opening a website every time. This make longer keys an impractical alternative to the experimental methods mentioned earlier. 
Another debatable method on whether or not it is quantum-secure is quantum cryptography. This method does not use mathematical encryption but instead, physics. This method is said to be unbreakable. To understand the reason behind, let’s look into how does this method work.

    As mentioned earlier, a particle could be pointing to different directions. When a particle pass through a rectilinear filter or a diagonal filter, the filter that matches the particle’s direction would allow it to pass through without changing its direction. Otherwise, the direction of the particle would change, and that would be an error. Therefore, an eavesdropping attempt would increase the error rate and disrupt the key exchanging process, leading the key to be resend through a different secure channel. This resending method would repeat every single time when eavesdropping attempt appeared, thus, unbreakable.
Quantum cryptography also uses one-time key pads that are created randomly during the process of key exchanging. Which allows no reusable keys for attackers to use. Both the filtering feature and the one-time key pad feature allows this method to securely protect the users’ privacy, and it is a trusted method to a lot users. However, the debate of quantum cryptography doesn’t protect information from attacks of a quantum computer came from the fact that a symmetric key itself is a mathematical algorithm. While quantum cryptography allows a safe delivery of the symmetric key,  a quantum computer will still be able to solve the algorithm of the symmetric key if it captures any clue about the algorithm of the key from other resources. The argument on this topic goes in a circle, because the rebuttal for this is that if the symmetric key is secure in the exchange process, there wouldn’t be clue leaking out for attackers.

    As safe as a quantum cryptography sound, there are limitations. One of them is that since it transfer information in physical method, the longest of the information that could be transfer so far is only 50 km. During the transferring process, only 1 out of 10 photon is received. In order to fix this problem, there are stations built in between delivery routes. Those stations duplicate the key, and send out that new key to the next station, until the final duplicated key reaches destination. This method would be only safe assuming the mid-stations are safe. Moreover, information would only be delivered assuming the physical path for transportation is not broken, although we could rest assure that the information would not leak out whether or not it is delivered successfully. Regarding the limitation in long distance transportation, scientist are working on developing materials that could allow a longer transportation without mid stations. Although the cost is high for building the transportation tools, the technology is being optimized in progress. Another limitation on storing qubit is that since particles are mostly highly active, they need to be stored at very low temperature to be able to allow quantum computer to function. 
One argument on quantum computer is that it might not substitute home computer just yet, because it is not universally applicable. It only improves the performance for specific cases. Also, imagine when informations all being transferred physically, no wifi available, this left the communication channels to be high cost, and low convenience. However, scientist are working on the optimization of quantum computer. Concurrently, quantum computing does come in handy in specific ways, such as big data analysis. The future is to expected with optimistic development of technology.




Reference:
https://www.youtube.com/watch?v=uiiaAJ3c6dM
https://www.youtube.com/watch?v=tG9ZiMLanhE&t=24s
https://www.youtube.com/watch?v=g_IaVepNDT4&t=302s
https://www.youtube.com/watch?v=zNzzGgr2mhk
https://www.youtube.com/watch?v=qO_W70VegbQ&list=PLtkEvlDzQleSZ5YX0YdlBfApei_XO2qWG&index=3
https://www.youtube.com/watch?v=OaDenwQU6EY&t=1501s
https://www.quantamagazine.org/quantum-secure-cryptography-crosses-red-line-20150908/
