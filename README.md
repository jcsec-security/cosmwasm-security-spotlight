# CosmWasm Security Spotlight

CosmWasm Security Spotlight is intended to be a series of medium posts about vulnerabilities found in audits of CW smart contracts. It would be a good starting point for anyone looking to get into CW contracts audits or to develop more secure smart contracts.

In addition, some hands-on labs are created so the reader can practice their bug hunting skills in easy targets. This series is being published in partnership with [Oak Security](https://www.oaksecurity.io/).

- [#1 Unsaved storage changes](https://medium.com/oak-security/cosmwasm-security-spotlight-1-cba294b27ea2)
    - Spot the bug challenge [01-Storewhat?](https://github.com/oak-security/cosmwasm-security-dojo/tree/main/challenges/01-storewhat)


# CosmWasm Security Resources

The following is a list of interesting resources in case you want to start auditing CosmWasm smart contracts. I have not personally reviewed some of the resources, but those have been useful to others in the past and therefore worthy of mention.

 My recommended path looks like:

1. **Blockchain and smart contracts basics:** you first need to be familiar with the basic concepts of blockchain technologies and smart contracts in general. I started with Solidity and Ethereum myself as there are plenty of resources out there for absolute beginners.
    1. Not very sure which ones to recommend if you don´t have any experience… But I enjoyed Mastering Ethereum back in the day [https://github.com/ethereumbook/ethereumbook](https://github.com/ethereumbook/ethereumbook)
2. **Rust language:** you don´t need a high level of Rust programming to start (quite hard IMO) just be able to clearly understand Rust programs and do basic tasks
    1. There are a lot of free basic courses out there:
        1. [https://www.udemy.com/course/ultimate-rust-crash-course/](https://www.udemy.com/course/ultimate-rust-crash-course/) and its second part [https://www.udemy.com/course/ultimate-rust-2/](https://www.udemy.com/course/ultimate-rust-2/)
        2. [https://academy.terra.money/courses/rust-basics](https://academy.terra.money/courses/rust-basics)
    2. Then you can find nice code examples at [https://doc.rust-lang.org/rust-by-example/](https://doc.rust-lang.org/rust-by-example/)
    3. I loved Rustlings, as you get to learn Rust by actually fixing code snippets that you have to previously understand which is quite similar to auditing in a sense [https://github.com/rust-lang/rustlings](https://github.com/rust-lang/rustlings)
    4. Aaaand for any further questions that could come to your mind during this journey, the Rust Book will be your bible [https://doc.rust-lang.org/stable/book/](https://doc.rust-lang.org/stable/book/)
3. **CosmWasm:** now that you know about blockchain, smart contracts and rust, it is about time to actually get into CosmWasm.
    1. How the CosmWasm module fits within a Cosmos chain
    2. CosmWasm inner workings, actor model, msgs, submsgs and other basic concepts [https://book.cosmwasm.com/](https://book.cosmwasm.com/)
    3. CosmWasm smart contract programming. You should be able to write easy CW smart contracts although not being a brilliant Rust developer.
        1. [https://github.com/Callum-A/cosmwasm-zero-to-hero](https://github.com/Callum-A/cosmwasm-zero-to-hero)
        2. [https://cosmwasm.getlearnworlds.com/](https://cosmwasm.getlearnworlds.com/)
        3. [https://area-52.io/](https://area-52.io/)
        4. [https://academy.terra.money/courses/cosmwasm-smart-contracts-i](https://academy.terra.money/courses/cosmwasm-smart-contracts-i)
4. **CosmWasm security:** the last step is when you are ready to get into the actual security issues of CW smart contracts.
    1. The articles in the above section and any future ones in my medium [https://medium.com/@jcsec-audits](https://medium.com/@jcsec-audits)
    2. Practical examples
        1. [https://github.com/oak-security/cosmwasm-security-dojo](https://github.com/oak-security/cosmwasm-security-dojo)
        2. [https://github.com/punishell/DeFiVulnLabsCosmWasm](https://github.com/punishell/DeFiVulnLabsCosmWasm)
    3. Reading reports!
        1. [https://github.com/oak-security/audit-reports](https://github.com/oak-security/audit-reports)
        2. [https://github.com/SCV-Security/PublicReports/tree/main/CW](https://github.com/SCV-Security/PublicReports/tree/main/CW)
        3. [https://github.com/HalbornSecurity/PublicReports/tree/master/CosmWasm%20Smart%20Contract%20Audits](https://github.com/HalbornSecurity/PublicReports/tree/master/CosmWasm%20Smart%20Contract%20Audits)
        
    

[](https://www.notion.so/1c2aff0426e34f7fac690722fe79505f)
