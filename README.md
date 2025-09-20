# Crytography-game

 
What is Cryptography?
Cryptography is the art and science of securing information by transforming it into an unreadable format for unauthorized users, while allowing authorized parties to access the original information. The word comes from the Greek words "kryptos" (hidden) and "graphein" .

Key Concepts:
Encryption: Converting plain text into coded text (ciphertext)
Decryption: Converting coded text back to plain text
Cipher: An algorithm used for encryption and decryption
Key: A piece of information that controls the cryptographic process
Types of Cryptography:
Symmetric Cryptography: Same key for encryption and decryption
Asymmetric Cryptography: Different keys (public/private key pairs)
Hash Functions: One-way cryptographic functions
Historical Examples:
Caesar Cipher: Shifting letters by a fixed number
Substitution Cipher: Replacing each letter with another letter/symbol
Vigenère Cipher: Using a keyword to vary the substitution
Modern Applications:
Internet Security: HTTPS, SSL/TLS protocols
 Banking: Secure transactions and data protection
 Mobile Communications: End-to-end encryption in messaging apps
Password Protection: Hashing algorithms for secure storage
 Digital Signatures: Verifying authenticity and integrity
Cryptography Game: How It Works
Game Concept
This is a Substitution Cipher Game where players decode encrypted messages by figuring out the number-to-letter mapping.

Game Mechanics
1. Encryption Process
Original Phrase: "HELLO WORLD"
↓
Number Mapping: H=3, E=7, L=1, O=9, W=4, R=8, D=2
↓
Encrypted Result: "37119 49812"
2. Core Algorithm
Step 1: Random Phrase Selection

Game randomly selects from predefined phrases:
"I AM HAPPY"
"GOOD DAY"
"HELLO WORLD"
"BE CREATIVE"
"STAY POSITIVE"
Step 2: Unique Letter Extraction

Extracts all unique letters from the chosen phrase
Example: "HELLO WORLD" → [H, E, L, O, W, R, D]
Step 3: Random Number Assignment

Creates array of numbers 0-9: [0,1,2,3,4,5,6,7,8,9]
Shuffles this array randomly
Maps each unique letter to a random number
Step 4: Encryption

Replaces each letter with its assigned number
Preserves spaces between words
3. Game Features
 Main Gameplay

Player sees encrypted number sequence
Types their guess for the original phrase
Game checks if answer matches exactly

 Hint System

Auto Hints: Game automatically reveals 2-4 letter-number mappings at start
Manual Hints: Player can request additional hints one at a time
Full Reveal: Shows complete answer if player gets stuck

 Dark Mode Toggle

Visual theme switcher for better user experience
4. Code Structure
Key Functions:

generateMapping(): Creates random letter-to-number assignments
encryptPhrase(): Converts text to numbers using the mapping
newPuzzle(): Initializes a fresh game round
checkAnswer(): Validates player's solution
revealSomeHints(): Provides initial helpful clues
5. Learning Value
This game teaches:

Pattern Recognition: Identifying common letter frequencies
Logical Deduction: Using partial clues to solve complete puzzles
Cryptanalysis Basics: Understanding substitution cipher vulnerabilities
Problem-Solving: Systematic approach to decoding encrypted messages
6. Strategy Tips for Players
Look for single letters → Likely "I" or "A"
Find short words → Common words like "THE", "AND", "IS"
Analyze letter frequency → "E" is most common in English
Use provided hints → Build upon known mappings
Try common phrases → Think of everyday expressions
This game provides an engaging introduction to cryptography concepts while developing analytical thinking skills! 
<img width="959" height="501" alt="1" src="https://github.com/user-attachments/assets/4406459c-f947-45ff-8793-70dbe5005e58" />
<img width="958" height="500" alt="2" src="https://github.com/user-attachments/assets/5d9d9c68-45cf-47e3-b02e-897f7eae87f9" />
<img width="959" height="490" alt="3" src="https://github.com/user-attachments/assets/94c49916-8754-4b0f-8f77-48df7a17fec6" />
<img width="956" height="499" alt="4" src="https://github.com/user-attachments/assets/bfbb5a91-8221-4aa8-99f8-633774dd5fd2" />

<img width="955" height="506" alt="5" src="https://github.com/user-attachments/assets/0d7a3c3a-a7fe-403d-bcc7-49375a51e52c" />




