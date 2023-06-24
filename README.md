## Paisa

<img width="956" alt="Screenshot 2023-06-24 at 11 37 46 PM" src="https://github.com/shivanshxyz/paisa/assets/24312840/a60245eb-ab94-484b-b95a-703f8637cb52">


## Problem Statement
- Modern wallet app transaction procedure is very alien for people who barely know how to even use a phone
- This is a huge roadblock when is comes to mass adoption of cUSD among small business owners
- Present solution has way more friction when compared to using cash


## Solution
- An easy to use POS system where there is no need to even install an app. Everyone can start accepting payments within seconds
- I implemented way to get transaction alerts without even opening your phone so that you can shift your focus on stuff that truly matters
- The system is so effortless that everyone can use it


## How it works
The system is divided into two parts
|                                               **Web based payment kiosk**                                               |                                               **Low cost payment alert soundbox**                                              |
|:-----------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------:|
|                 No nonsense payment requests through an intuitive interface. Just get started right away                | A smart speaker that makes automated sound alerts whenever the vendor receives any amount in their wallet using text to speech |
| Just enter your .celo/.soul name and the amount you want to receive and the kiosk will generate a custom amount QR code |                                 Uses very low cost hardware microcontrollers like Raspberry pi                                 |
|             The customer uses the QR code scanner from their phone and can pay through their celo wallet app            |                      The smart speaker uses Quicknode’s Quickalerts service to monitor wallet transactions                     |
|                                                                                                                         | No need to check your wallet every after every transaction so that you can focus on stuff that truly matters                   |

<img width="958" alt="Screenshot 2023-06-24 at 11 38 08 PM" src="https://github.com/shivanshxyz/paisa/assets/24312840/d632bcc3-f68c-4925-9405-74475ea2d3d1">

<img width="959" alt="Screenshot 2023-06-24 at 11 38 21 PM" src="https://github.com/shivanshxyz/paisa/assets/24312840/feb0e9bd-d0bf-4e47-8584-f51163713ace">



## Tech Stack
- POS app
  - react
  - Masa-sdk

- Smart speaker
  - Quicknode-sdk
  - Python ttsx3 library
  - Raspberry pi
