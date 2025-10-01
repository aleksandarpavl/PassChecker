# PassChecker


This project demonstrates a privacy‑aware approach to checking whether a password has appeared in public breaches. The application computes a SHA‑1 hash of the supplied password locally and queries the Have I Been Pwned API using the k‑anonymity range method (only the first 5 characters of the hash are sent). The response is parsed to find whether the hash suffix exists and how many times the password appeared in breach datasets. It’s a small but practical example of secure API usage, hashing, and parsing network responses in Python.
