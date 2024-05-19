# Valhalla Foundation Bot

## Description
Kalo kalian make ini auto langsung kelar task yang di website nya sirr. Bot nya make bearer token nanti ada tutornya dibawah dan masukan bearer ke `accounts.json` file.

## Features
- Secara otomatis menyelesaikan dan mengklaim quest Social dan Seasonal.
- Support buat langsung ngegarap banyak akun(tinggal masukan bearer sesuai akun).

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/rmndkyl/Valhalla-BOT.git
    cd Valhalla-BOT
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

## Setup
1. Create an `accounts.json` file in the root directory. This file should contain an array of bearer tokens for the accounts you want to automate. Example:
    ```json
    [
      "Bearer eyJblablabla",
      "Bearer eyJblablabla"
    ]
    ```

2. To obtain your bearer token:
    1. Buka Web browser kalian dan Login ke [Infinigods platform]([url](https://www.valhallafoundation.xyz/missions?referrer=mandayy72)).
    2. Buka Developer Tools (Klik-kanan di Website dah klik "Inspect" atau tekan `Ctrl+Shift+I`).
    3. Pergi ke "Network" tab.
    4. Refresh website nya dengan mencet tombol di keyboard Ctrl+R.
    5. Cari permintaan dengan header `Authorization` dalam header permintaan.
    6. Salin nilai dari header `Authorization`. Ini harus dimulai dengan `Bearer eyblabla`.

3. Paste Bearer yang sudah di copy ke `accounts.json` file.

## Usage
Start the bot by running:
```bash
npm start
```
