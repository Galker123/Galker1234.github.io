<head><meta charset="utf-8"><meta name="viewport" content="width=device-width, initial-scale=1"><link rel="preload" href="/_next/static/media/c9a5bc6a7c948fb0-s.p.woff2" as="font" crossorigin="" type="font/woff2"><link rel="preload" as="image" href="/_next/static/media/locker-logo.ccc5c962.svg" fetchpriority="high"><link rel="stylesheet" href="/_next/static/css/24b4f7d9d684f685.css" crossorigin="" data-precedence="next"><link rel="preload" as="script" fetchpriority="low" href="/_next/static/chunks/webpack-f7275cbe2200c282.js" crossorigin=""><script src="/_next/static/chunks/fd9d1056-25315113ca25227d.js" async="" crossorigin=""></script><script src="/_next/static/chunks/8069-c75fbabd542575b1.js" async="" crossorigin=""></script><script src="/_next/static/chunks/main-app-e9c88439a17e41c2.js" async="" crossorigin=""></script><script src="/_next/static/chunks/0e5ce63c-38a315b7e6dc909a.js" async=""></script><script src="/_next/static/chunks/97586-af9450440a53ead4.js" async=""></script><script src="/_next/static/chunks/24608-12aef5068d56b222.js" async=""></script><script src="/_next/static/chunks/90874-54dc6d24d5afebcd.js" async=""></script><meta name="next-size-adjust"><script src="/_next/static/chunks/polyfills-c67a75d1b6f99dc8.js" crossorigin="" nomodule=""></script><style id="_goober"> @keyframes go2264125279{from{transform:scale(0) rotate(45deg);opacity:0;}to{transform:scale(1) rotate(45deg);opacity:1;}}@keyframes go3020080000{from{transform:scale(0);opacity:0;}to{transform:scale(1);opacity:1;}}@keyframes go463499852{from{transform:scale(0) rotate(90deg);opacity:0;}to{transform:scale(1) rotate(90deg);opacity:1;}}@keyframes go1268368563{from{transform:rotate(0deg);}to{transform:rotate(360deg);}}@keyframes go1310225428{from{transform:scale(0) rotate(45deg);opacity:0;}to{transform:scale(1) rotate(45deg);opacity:1;}}@keyframes go651618207{0%{height:0;width:0;opacity:0;}40%{height:0;width:6px;opacity:1;}100%{opacity:1;height:10px;}}@keyframes go901347462{from{transform:scale(0.6);opacity:0.4;}to{transform:scale(1);opacity:1;}}.go4109123758{z-index:9999;}.go4109123758 > *{pointer-events:auto;}</style><style data-emotion="css szj68g animation-plwpox" data-s="">.css-szj68g{all:unset;cursor:pointer;display:-webkit-inline-box;display:-webkit-inline-flex;display:-ms-inline-flexbox;display:inline-flex;-webkit-align-items:center;-webkit-box-align:center;-ms-flex-align:center;align-items:center;-webkit-box-pack:center;-ms-flex-pack:center;-webkit-justify-content:center;justify-content:center;border-radius:8px;padding:14px 14px;font-size:16px;font-weight:500;box-sizing:border-box;-webkit-tap-highlight-color:transparent;line-height:normal;-webkit-flex-shrink:0;-ms-flex-negative:0;flex-shrink:0;-webkit-transition:border 200ms ease;transition:border 200ms ease;gap:0;text-align:center;max-width:100%;background:#eeeef0;color:hsl(230deg 11.63% 8.43%);-webkit-animation:animation-plwpox 300ms ease;animation:animation-plwpox 300ms ease;}.css-szj68g:active{-webkit-transform:translateY(1px);-moz-transform:translateY(1px);-ms-transform:translateY(1px);transform:translateY(1px);}.css-szj68g[disabled]{cursor:not-allowed;}.css-szj68g[data-disabled='true']{background:hsl(230deg 11.63% 12%);color:#7c7a85;border-color:transparent;box-shadow:none;}.css-szj68g[data-disabled='true']:hover{border-color:transparent;}@-webkit-keyframes animation-plwpox{from{opacity:0;}to{opacity:1;}}@keyframes animation-plwpox{from{opacity:0;}to{opacity:1;}}</style><style data-emotion="css w3jvbs animation-uey69n" data-s="">.css-w3jvbs{-webkit-animation:animation-uey69n 2s linear infinite;animation:animation-uey69n 2s linear infinite;width:1em;height:1em;}@-webkit-keyframes animation-uey69n{100%{-webkit-transform:rotate(360deg);-moz-transform:rotate(360deg);-ms-transform:rotate(360deg);transform:rotate(360deg);}}@keyframes animation-uey69n{100%{-webkit-transform:rotate(360deg);-moz-transform:rotate(360deg);-ms-transform:rotate(360deg);transform:rotate(360deg);}}</style><style data-emotion="css 1s0kaq5 animation-dfl6wh" data-s="">.css-1s0kaq5{stroke-linecap:round;-webkit-animation:animation-dfl6wh 1.5s ease-in-out infinite;animation:animation-dfl6wh 1.5s ease-in-out infinite;}@-webkit-keyframes animation-dfl6wh{0%{stroke-dasharray:1,150;stroke-dashoffset:0;}50%{stroke-dasharray:90,150;stroke-dashoffset:-35;}100%{stroke-dasharray:90,150;stroke-dashoffset:-124;}}@keyframes animation-dfl6wh{0%{stroke-dasharray:1,150;stroke-dashoffset:0;}50%{stroke-dasharray:90,150;stroke-dashoffset:-35;}100%{stroke-dasharray:90,150;stroke-dashoffset:-124;}}</style><style data-emotion="css" data-s=""></style></head><!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ERC-20 Token Lock</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      padding: 20px;
      background-color: #f4f4f4;
    }
    button {
      padding: 10px 20px;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
      font-size: 16px;
      border-radius: 5px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h1>ERC-20 Token Lock</h1>
  <p>Connect your wallet and lock/unlock your tokens.</p>

  <button id="connectButton">Connect Wallet</button><br><br>

  <input type="text" id="tokenAddress" placeholder="Enter Token Address" /><br><br>
  <input type="number" id="lockAmount" placeholder="Amount to Lock" /><br><br>
  <button id="lockButton" style="display:none;">Lock Tokens</button>

  <h3>Your Locked Balance: <span id="lockedBalance">0</span></h3>
  <input type="number" id="unlockAmount" placeholder="Amount to Unlock" /><br><br>
  <button id="unlockButton" style="display:none;">Unlock Tokens</button>

  <script src="https://cdn.jsdelivr.net/npm/ethers@5.7.2/dist/ethers.umd.min.js"></script>
  <script>
    let provider;
    let signer;
    let contract;
    const tokenLockAddress = "YOUR_TOKEN_LOCK_CONTRACT_ADDRESS"; // Replace with your TokenLock contract address
    const tokenLockABI = [
      {
        "constant": false,
        "inputs": [{"name": "token", "type": "address"}, {"name": "amount", "type": "uint256"}],
        "name": "lockTokens",
        "outputs": [],
        "payable": false,
        "stateMutability": "nonpayable",
        "type": "function"
      },
      {
        "constant": false,
        "inputs": [{"name": "token", "type": "address"}, {"name": "amount", "type": "uint256"}],
        "name": "unlockTokens",
        "outputs": [],
        "payable": false,
        "stateMutability": "nonpayable",
        "type": "function"
      },
      {
        "constant": true,
        "inputs": [{"name": "user", "type": "address"}],
        "name": "getLockedBalance",
        "outputs": [{"name": "", "type": "uint256"}],
        "payable": false,
        "stateMutability": "view",
        "type": "function"
      }
    ];

    const connectButton = document.getElementById("connectButton");
    const lockButton = document.getElementById("lockButton");
    const unlockButton = document.getElementById("unlockButton");
    const tokenAddressInput = document.getElementById("tokenAddress");
    const lockAmountInput = document.getElementById("lockAmount");
    const unlockAmountInput = document.getElementById("unlockAmount");
    const lockedBalanceSpan = document.getElementById("lockedBalance");

    async function connectWallet() {
      if (window.ethereum) {
        provider = new ethers.providers.Web3Provider(window.ethereum);
        await provider.send("eth_requestAccounts", []);
        signer = provider.getSigner();
        contract = new ethers.Contract(tokenLockAddress, tokenLockABI, signer);
        connectButton.style.display = "none";
        lockButton.style.display = "inline-block";
        unlockButton.style.display = "inline-block";
        updateLockedBalance();
      } else {
        alert("Please install MetaMask!");
      }
    }

    async function lockTokens() {
      const tokenAddress = tokenAddressInput.value;
      const amount = ethers.utils.parseUnits(lockAmountInput.value, 18);
      try {
        await contract.lockTokens(tokenAddress, amount);
        alert("Tokens locked successfully!");
        updateLockedBalance();
      } catch (error) {
        console.error(error);
        alert("Failed to lock tokens");
      }
    }

    async function unlockTokens() {
      const tokenAddress = tokenAddressInput.value;
      const amount = ethers.utils.parseUnits(unlockAmountInput.value, 18);
      try {
        await contract.unlockTokens(tokenAddress, amount);
        alert("Tokens unlocked successfully!");
        updateLockedBalance();
      } catch (error) {
        console.error(error);
        alert("Failed to unlock tokens");
      }
    }

    async function updateLockedBalance() {
      const userAddress = await signer.getAddress();
      const lockedBalance = await contract.getLockedBalance(userAddress);
      lockedBalanceSpan.textContent = ethers.utils.formatUnits(lockedBalance, 18);
    }

    connectButton.addEventListener("click", connectWallet);
    lockButton.addEventListener("click", lockTokens);
    unlockButton.addEventListener("click", unlockTokens);
  </script>
</body>
</html>
