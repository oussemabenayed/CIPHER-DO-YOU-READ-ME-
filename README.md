def unlock_protocol():
    import os
    print("Payload Received Successfully.")
    print(f"Current Directory: {os.getcwd()}")
    return "CIPHER_IS_LIVE"

if __name__ == "__main__":
    print(unlock_protocol())
