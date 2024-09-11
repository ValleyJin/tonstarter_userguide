# Launch (Simplified)
TONStarter sets default values to make launching your project quick and easy.

1. Prepare to Launch
First, enter the TONStarter Launch page as shown below.
![image](https://github.com/user-attachments/assets/ab3bd4bf-42da-42fd-937d-164f241884f5)


Connecting a crypto wallet

On the Launch screen, tap the Connect Wallet button in the upper right corner to connect your cryptocurrency wallet first.

The address to which future funded tokens will be sent will be the address of your currently linked crypto wallet. A warning window will appear asking you to agree to this. Confirm the wallet address and press the confirm button if you agree.

Future funding will be sent to the associated cryptocurrency wallet address, so make sure it's the correct one you want.


Warning window (confirms that the currently linked wallet address is the one that will receive future funded tokens)
A window will appear with the Terms of Use. Read it, check if you agree, and hit the confirm button.


Terms of Use modal window
2. Understanding the launch process and default values
Projects are launched in a three-step process, each step requiring you to set various parameters for the project to launch.

⓵ 3 Steps to Launch

Project & Token 

Enter the basics: the name of your project and token, and your funding schedule.

Token Economy

Determine the funding goal, the total supply of tokens, and the allocation of tokens for various purposes (Vault).

Deploy

This is the stage where the smart contract that reflects the above settings is deployed, and the project is ready for launch at the end of this process.

Creating a project consists of 3 steps, and each step has a Save button to allow you to save between steps. Please note that if you refresh without saving, your input values may be lost.

⓶ Default values 

To launch a project, you need to make a number of settings. To help you launch your project quickly, TONStarter Launch has already filled in the most common values as defaults.

If you don't want to use the default values and want to fine-tune the parameters to suit the nature of your project, you can click the Advanced mode button. However, once you move to Advanced mode and proceed with the project settings, you cannot return to the default mode.

The project launch parameter values that are set to default are shown below.

Step	Parameter	Default values
01. Project & Token

Token Type 
(not adjustable)

Type A 

Token Funding Price
(in TON)

No default (just user input field)

Token Listing Price 
(in TOS)

No default (just user input field)

Initial Liquidity Pool 

10% of Funded TON

02. Token Economy

Vaults and Toke Allocation 
(not adjustable)

Public(30%) Ecosystem(35%) Team(15%) Liquidity(15%)

Initial Liquidity(3.0%)

Token-TOS LP Reward(12.0%) 

TONStarter(5%) 

 WTON-TOS LP reward : 2.5% 

TON Staker : 1.25% 

TOS Staker : 1.25%

Snapshot 

At least 11 days later than the current time - If adjusted, Snapshot should be 8 days or more later than the current time

Whitelist 
(not adjustable)

1 second after Snapshot ~ 1 second before Public Sale 1. (But this duration should be at least 2 days or more.)

Token Allocation between Public Sale 1, 2 
(not adjustable)

Public Sale 1 : 50% Public Sale 2 : 50%

Public Sale 1 (adjustable)

1 second after Whitelist has finished ~ 2 days

Public Sale 2 (adjustable)

1 second after Public sale 1 has finished ~ 2 days

Vesting Round 1 
(not adjustable)

1 second after the end of the Public Sale 2 

Claim limit : 40% 

Vesting Round 2~4 
(not adjustable)

360 days after the previous round

Claim limit : Round 2 (20%),  Round 3 (20%) , Round 4 (20%)

Send Tokens to Initial Liquidity 
(not adjustable)

1 second after the end of the Public Sale 2

Token Generation Event (TGE : The time to Unlock Vaults Starts) 

(not adjustable)

1 second after the end of the Public Sale 2

03. Deploy - Initialize each vaults

Claim schedule (49 rounds) for each vaults

schedule file 

There are three types of tokens 

Type A : Burnable, approveAndCall, Snapshot, Permit, Non mintable

Type B: Burnable, Snapshot, Mintable

Type C: Burnable, Mintable

(Note 1) Vesting & Claim details after deployment and launch
The Deploy phase is a process in which various smart contracts are deployed, and it is further divided into three phases: Deploy, where smart contracts are deployed, Send, where project tokens are sent to each vault, and Initialize, where each vault is initialized, as shown in the figure below.

At TONStarter, we have prepared a UX/UI that makes it easy for anyone to go through these steps one by one with the click of a button.


Flow Diagram of Deploy, Vesting, and Claim
Once this is complete, you're all set to launch your project. Once your project is open and subsequently funded, the vesting and claiming process will follow, as follows.

(Vesting)  For the project team, the vesting process begins, where the funding raised by the TON is spread out over a period of time. This is to incentivize diligent project progress and will be opened in four installments over three years. Vesting rate per installment: 1 time (40%), 2-4 times (20% each). The one-time vesting rate is up to 50%, and can be increased but not decreased over a total of four rounds. 

(Claim) Investors who have invested in the project will also be able to claim their project tokens to their crypto wallets in installments over a period of time. There will be seven installments over three years. You can claim the unclaimed portion at any time, and you can claim together in the next round.


Claims and vesting timeline
