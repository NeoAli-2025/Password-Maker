---

## 🧩 About the Project

**NeoAli Secure Password Generator** is a high-security password tool built in Python,  
designed to ensure tamper protection and encrypted personalization.

Unlike typical password generators, this one includes:
- 🔒 **Encrypted configuration** – personal data is AES-encrypted and protected with Ed25519 signatures.  
- 🧬 **Signature verification** – detects any unauthorized modifications automatically.  
- ⚙️ **User encryption key** – only you can decrypt your personalized section.  
- ⚡ **Strong random generation** – powered by `secrets` for cryptographically secure randomness.

---

## 🧠 Tech Stack

| Category | Technology |
|-----------|-------------|
| Language | Python 3.12+ |
| Crypto | `cryptography`, `Ed25519`, `Fernet` |
| Styling | `colorama` |
| Security | Key signing, local encryption |
| Versioning | Git & GitHub |

---

## 🚀 How to Use

1. **Generate your keys**
   ```bash
   python generate_keys.py


