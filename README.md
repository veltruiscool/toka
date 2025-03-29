# **Toka – Secure Your Discord Token**  

**Toka** is an **open-source** Python tool designed to **protect your Discord user token** by encrypting it in the cache. This prevents malware and token grabbers from stealing your credentials, keeping your account secure.  

## **Why Use Toka?**  
Your Discord token grants **full access** to your account. If stolen, an attacker can:  
- **Take over your account without a password or 2FA.**
- **Send messages, delete servers, and change settings.**
- **Use your account for malicious activities.**

Toka encrypts your token, ensuring it stays safe even if your cache is compromised.  

## **Features**  
- **Encrypts Your Token** – Prevents direct access to your credentials.  
- **Protects Against Token Grabbers** – Stops malware from stealing your token.  
- **Lightweight & Fast** – Works without slowing down performance.  
- **Easy to Use** – Simple integration with Python-based Discord projects.  

## **Installation & Usage**  
### **Install**  
```sh
pip install toka
```  
### **Example in Python**  
```python
from toka import TokenEncryptor

encryptor = TokenEncryptor("your_secret_key")  

# Encrypt token
encrypted_token = encryptor.encrypt("YOUR_DISCORD_USER_TOKEN")

# Decrypt when needed
decrypted_token = encryptor.decrypt(encrypted_token)
```  

## **Get Involved**  
Toka is **open-source**! You can:  
- Report issues & suggest features on **GitHub**.  
- Join our **Discord community** for support.
