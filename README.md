## rideonchain
**RideOnChain - Verifiable crowd meters for CNE rides, powered by blockchain trust**
--------------------------------------------------------------------------------------------------------------------------------------------------------------------
## ProjectDescription
**RideOnChain** is a mobile app designed to help visitors at the **Canadian National Exhibition(CNE)** make smarter choices about which rides to enjoy by providing **real-time, verifiable crowd data**. Long wait times are one of the biggest frustrations at CNE, where visitors often spend more time in line than actually riding. Unlike existing solutions that rely on estimates or private data feeds, RideOnChain delivers real-time, verifiable information that users can **trust**.

The app uses **XION's Mobile Dev Kit**, **zkTLS verification**, and **on-chain proof logging** to power a ride "Crowd Meter." Each Ride shows a live status (Low, Medium, High) and a computed wait time derived from verified inputs, such as ride entry and exit scans. Scanner data is zkTLS-verified and anchored on-chain to ensure accuracy and transparency, so visitors can trust the numbers behind the estimates.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Target Audience
- CNE visitors who want to maximize fun and minimize wait times.
- CNE organizers who want crowd insights to improve flow and safety.

Going forward, RideOnChain has the potential to scale beyond CNE, first to **other fairs, theme parks, and festivals worldwide**, and later to the **Toronto TTC Transit System** to help commuters trust real-time crowd data. By bridging everyday experiences with verifiable technology, RideOnChain saves time, reduces frustration, and builds confidence in information that matters most.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Team Information
- **Team Name** : RideOnChain
- **Caroline Nkan** - *Founder, Product Lead & Builder*
- 📧 : **Carolinenkan805@gmail.com**
- **Leading product vision, design, development, blockchain integration, and pitching**
  
 **One Woman. One Vision. Many Hats.**
 
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Problem Statement
At the **Canadian National Exhibition(CNE)**, visitors waste hours in long, unpredictable ride lines. Sure, we can wander off to food stands or games, hoping the line gets shorter by the time we get back, but without magic, we usually come back to find it even longer, and our spot's gone. 
**RideOnChain** solves this by using **zkTLS** and **on-chain proofs** to provide verifiable, transparent crowd data, so visitors can trust the info and organisers can better manage flow.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Tech Stack
- **XION Mobile Dev Kit** - Core Toolkit for building iOS & Android apps with verifiable data.
- **React** -Platform for mobile UI.
- **Mock JSON API/Node.js** - Simulated ride entry and exit scanner events for checkpoint2 demo.
- **zkTLS** - Verifies ride crowd data at source without exposing sensitive info.
- **XION Testnet(on-chain proofs)** - Stores verified crowd data immutably on-chain.
- **Figma/Canva** - For Wireframes & UI mockups.
- **Youtube** - Hosting demo video.
  
  -----------------------------------------------------------------------------------------------------------------------------------------------------------------
  ## Installation Instructions
  - Clone the repository and install dependencies
  - ```bash
  - git clone https://github.com/buildwithcaroline/rideonchain.git
  - cd rideonchain/app
  - npm install
  - npx start
  
