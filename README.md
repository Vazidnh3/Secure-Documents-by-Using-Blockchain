# Secure Documents by Using Blockchain

## Introduction
In this groundbreaking project, I have developed a robust file storage mechanism designed to ensure data security through decentralized means. This cutting-edge approach leverages blockchain technology, positioning us at the forefront of data protection and accessibility. 🔒🌐

Our innovative solution incorporates the use of Pinata's API for decentralized data storage, offering enhanced security and reliability. Furthermore, we've seamlessly integrated Metamask to facilitate user creation and authentication, reinforcing the project's commitment to robust data management. 🗝️🔐

The core of our system relies on blockchain transactions for data storage, a tamper-resistant approach that guarantees the immutability of data once it's pushed onto the blockchain. This ensures data integrity and permanence, while still allowing for authorized modifications when necessary. 📦🔒

To ensure the robustness and reliability of our project, we've employed the Hard Hat network for rigorous testing and efficient deployment onto the blockchain. 🛠️🚀

With these cutting-edge technologies and methodologies at the project's foundation, we're ushering in a new era of data security and accessibility, setting the stage for a more secure and decentralized digital world. 🌟🌍

## Changes in the Code
In your project's "FileUpload.js" file, located in the "src" directory, lines 19 and 20 contain placeholders "pinata_api_key" and "pinata_secret_api_key." To make your project work, replace these placeholders with your actual Pinata API key and secret API key, which you can obtain from Pinata's platform. 

## Running the Code
### Step 1
After importing the project onto your local machine, open it in Visual Studio Code (VSCode). Next, access the terminal within VSCode and execute the following command:

```npm install --save-dev hardhat@2.12.4```

This command is crucial for setting up the necessary development dependencies. It enables you to utilize Hardhat, a development environment for Ethereum smart contracts, to effectively build, test, and deploy your blockchain-based project.

After executing the previous command, proceed to run 'npm install create-react-app.' This command is pivotal to the project's functionality.

Here's how you should utilize it:

Install Create React App: Run the following command to install Create React App:

```npm install create-react-app```

Once you've completed this step, you're ready to set up the project.

Navigate to the Client Folder: To work on the client side of the project, change directories to the 'client' folder. You can do this using the following command:

```cd client```

Start the Development Server: Launch the development server by running:

```npm start```

After successfully executing these three commands, your web server will be up and running, and you can begin working on your project.

### step 2

Step 2: Launch a Local Ethereum Node

Open a new terminal window and run the following command:

```npx hardhat node```

This command is used to start a local Ethereum node, which is essential for running and testing your Ethereum smart contracts in a development environment. It provides a sandboxed Ethereum blockchain for testing and development purposes.

### step 3
Step 3: Deploy Smart Contracts to the Local Ethereum Node

In a separate terminal window, execute the following command:

```npx hardhat run --network localhost scripts/deploy.js```

This command is used to deploy your Ethereum smart contracts to the local Ethereum node running on your machine. It invokes the deployment script specified in scripts/deploy.js, enabling you to test and interact with your smart contracts in the local development environment.

Users are required to set up a Metamask account.


## Technologies
**Metamask** is a versatile cryptocurrency wallet and 🌐 web3 provider that plays a crucial role in the 🪙 blockchain ecosystem. It acts as a secure bridge between users and blockchain networks, with a primary focus on Ethereum. Users can easily manage their Ethereum accounts, interact with decentralized applications (DApps), and securely store private keys, all within a user-friendly browser extension. Metamask's flexibility extends to various Ethereum networks, including the Ethereum Mainnet and testnets, providing both developers and users with seamless access to a wide array of blockchain-based services. 🔐💼

**Pinata** is a versatile web3 service at the core of blockchain data storage. It simplifies **decentralized data management**, especially on Ethereum, with an easy-to-use interface and API. Developers and users benefit from its cross-network compatibility, ensuring secure and reliable data storage, enhancing decentralized applications (DApps) and smart contract functionality, all while prioritizing data security and integrity. 🔐📂

**Ethereum** and **Hardhat** form a powerful duo in blockchain development, with Ethereum serving as the foundation for decentralized applications and smart contracts, and Hardhat providing a robust toolkit for testing and deploying these blockchain solutions. Hardhat streamlines the development process, offering automated testing and a user-friendly environment, making it an essential companion for Ethereum developers. 

## Screenshots
![Screenshot (3)](https://github.com/Vazidnh3/Secure-Documents-by-Using-Blockchain/assets/111126298/56dce454-e048-41a7-a43a-b6febbb5e150)

![Screenshot (4)](https://github.com/Vazidnh3/Secure-Documents-by-Using-Blockchain/assets/111126298/a2a78752-8b15-4b4e-97a3-9fc6a54f30e6)

![Screenshot (5)](https://github.com/Vazidnh3/Secure-Documents-by-Using-Blockchain/assets/111126298/de4bffdd-2c3b-4d3b-a4ad-478f9e3b0b17)

![Screenshot (6)](https://github.com/Vazidnh3/Secure-Documents-by-Using-Blockchain/assets/111126298/75a96573-08b7-4228-b402-7debcfc2bcbf)

## Conclusion
In summary, this project showcases the effective combination of Metamask, Pinata, Ethereum, and Hardhat to create a secure and functional blockchain-based application. By replacing placeholder API keys with their own from Pinata, users ensure data integrity and storage reliability. This integration enhances blockchain app security and functionality, fostering growth and innovation within the decentralized ecosystem. 🔒🌐🚀💡

## Technology Stack
https://metamask.io/

https://app.pinata.cloud
