# Caesar Cipher (Python)

This project is my take on the original Caesar Cipher. A simple encryption technique where each letter in a message is shifted by the user's chosen amount. I built this to practice loops, modular arithmetic, and a user interaction in Python. It supports both encoding and decoding, handles symbols, and has a little ASCII art to represent what the program is.

---

## What It Does

- Encrypts and decrypts text using the Caesar Cipher
- Allows the user to choose any shift amount
- Preserves spaces, numbers and symbols
- Runs in a loop until you decide to stop
- Displays an ASCII art logo

---

## Project Structure

```
Caesar_Cipher/
│
├─ Caesar_Cipher.py            # Main cipher logic
└─ Caesar_Cipher_Art.py        # ASCII art logo
```

This structure is very short, with only two files required.

---

# How To Run It

Make sure both of the files are in the same folder, then run:

```
Caesar_Cipher.py
```

You'll be asked whether you want to encode or decode, then your message, and your shift amount.

---

## Example Image

<img width="1740" height="902" alt="caesar cipher pic" src="https://github.com/user-attachments/assets/7f710945-4e96-4e31-bd43-0e1d7b25c3d7" />

This what happens when the program runs and the user responds.

---

## Future Thoughts

I intentionally made this project simple, but I'd like to expand it with:
- Uppercase letter support
- Input validation
- A GUI version using Tkinter or PyQT
