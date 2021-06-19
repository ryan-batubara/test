# 1: Introduction

## 1.1: Background

As we become increasingly reliant on networks with open communication such as the internet, it is more important than ever before to keep stored and transmitted data secure from unwanted parties. This need has led to the development of cryptology, or the combination of cryptography (study of encrypting data) and cryptanalysis (study of breaking encryptions).

Cryptography has been relevant to humanity since ancient times, as it allows messages to be sent publicly yet only meaningful to wanted recipients. For example, the Romans were seen using codes, or pre-arranged substitutes for common messages, such as the raising of a red flag to indicate attack. The Romans had also developed ciphers, or algorithms to convert messages to meaningless jumbles until decrypted back into meaningful information. This was seen in the Caesar Cipher, which shifted the letters of the alphabet making it unreadable unless you knew how many letters they shifted, and hence how to unshift or decrypt the data.

However, such simple codes and ciphers are easy to understand and fall short to simple cryptanalysis. It is not difficult to notice the Roman’s flag signals or the Caesar cipher, especially when encountering it multiple times. Hence, the modern world required ciphers or encryption methods that were fast to execute, could handle messages of any size, and were very resistant to even the most advanced cryptanalysis. 

For the longest time, a private key encryption model was used. Suppose two people, conventionally named Alice and Bob, wanted to send messages to each other while Eve the eavesdropper was around. Alice would have to arrange with Bob a key, usually a number, that they would use to encrypt (multiply with their message) and decrypt (divide from their message) messages. However, this key would have to be arranged while Eve was not around, as if Eve had the key she could easily decrypt their communications. Furthermore, Eve will eventually be able to figure out the cipher herself as she notices patterns in Alice’s messages to Bob and vice versa. In all scenarios, Eve would eventually find the common factor or key, regardless whether Alice and Bob keep changing keys or other simple mitigation techniques.

In 1976, two people surname Diffie and Hellman proposed a famous theory called the Diffie-Hellman key exchange, which theorized that it was possible for Alice and Bob to send messages to each other without any pre-arrangements, and with Eve listening all the way through. Diffie and Hellman proposed a public key encryption system, where a publicly-known key would be used to encrypt a message, and a private key known only to Alice or Bob would be used to decrypt the messages. So if Alice wanted to send a message to Bob, she would only need to find Bob’s public key, which is publicly known, encrypt the message using the key, send it to Bob, and Bob would decrypt the message with his private key, and Eve would have no idea what the message is. But how could such a function exist?


You can use the [editor on GitHub](https://github.com/ryan-batubara/test/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ryan-batubara/test/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
