    # Name: pkNFT1155
    Base Contracts: ERC1155, Ownable
    Compiler Version: 0.8.0
    License: MIT

Key Features:

    Token Metadata Storage:
        Metadata for each token is stored in _tokenMetadata mapping.
        Metadata includes image, description, and prompt.
        Supports encrypted prompts if encryptionEnabled is true.

    Encryption:
        Controlled by encryptionEnabled flag.
        Default state is disabled.
        Toggled by toggleEncryption function.

    Token Minting:
        mint function mints new tokens and stores metadata.
        Generates and sets a URI for the token.

    API Key Storage:
        Encrypted API keys stored in _apiKeys mapping.
        Accessible via storeEncryptedAPIKey and getEncryptedAPIKey functions.

    The pkNFT1155 contract implements a basic ERC1155 token with additional metadata and encryption features.
