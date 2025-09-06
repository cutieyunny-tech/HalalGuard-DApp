HalalGuard: Privacy-First Recommendations
Project Concept
This is a Decentralized Application (DApp) that provides Halal food recommendations while protecting user privacy. It uses a Zero-Knowledge (ZK) proof mechanism to verify a user's dietary preferences without ever revealing their personal data.

This project was built for the Midnight Network's "Privacy First" Challenge.

How to Run the DApp
It's very simple! This DApp is a single HTML file.

Download the protect_that_data.html file from this repository.

Open the file directly in your web browser (like Chrome, Firefox, or Safari).

That's it! No installation or setup is needed.

How It Works
1. User Input
The user selects their dietary preferences (e.g., "no alcohol"). This input is private and never leaves the user's browser in a readable form.

2. The ZK Proof (Simulated)
Instead of sending the raw data, the DApp simulates a process to generate a zero-knowledge proof. This proof is a cryptographic guarantee that says, "I have the correct preferences, but I'm not going to show you what they are."

In a real DApp built on Midnight, this is where Midnight's Compact language and MidnightJS would be used to create the proof. The proof would then be verified on a smart contract.

3. The Recommendation
The DApp checks if a product matches the proof's criteria. It can then show a result like "Product A is Halal Compliant" without ever knowing the user's specific dietary preference.

This is the core of the privacy-preserving mechanism.

Use of Technology
This project demonstrates the core concepts of privacy-first DApps using:

A user-friendly UI.

A simulated zero-knowledge proof mechanism.

A clear focus on data privacy, a key feature of the Midnight Network.

License
This project is open-sourced under the Apache 2.0 license.
