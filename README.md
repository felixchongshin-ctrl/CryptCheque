# CryptCheque - Secure Electronic Cheque System

A provably secure electronic cheque system built with Rust, implementing Ed25519 digital signatures, X25519 key exchange, and AES-256-GCM encryption.

## Download

Go to [Releases](../../releases) and download the latest zip file.

## Setup

1. Install and start **XAMPP** (https://www.apachefriends.org)
2. Start **Apache** and **MySQL** in the XAMPP Control Panel
3. Open http://localhost/phpmyadmin, click the **SQL** tab, paste the contents of `schema.sql`, click **Go**
4. Extract the downloaded zip and double-click `cryptcheque.exe`
5. The system opens automatically in your browser

## Default Accounts

- Bank admin is created automatically on first run: username `bank_admin`, password `admin123`
- Register new Payer and Payee accounts through the registration page
- Payer accounts start with a demo balance of RM 10,000
