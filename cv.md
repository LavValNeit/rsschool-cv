# **Ilya Kuzmin**
## **Contacts**

* **Location:** Samara, Russia
* **Phone:** +79277935408
* **Email:** ilya.kuzmin.03@yandex.ru

## **About Me**

I'm just a student that want to learn JS, HTML and React

## **Skills**
* HTML
* JAVA
* .NET
* JavaScript (Basic)
* TASM
* AVR Assembler

## Code Example

```c++
HCRYPTHASH hCryptHash;
		CryptCreateHash(hCryptProv, CALG_MD5, NULL, 0, &hCryptHash);
		CryptHashData(hCryptHash, (BYTE*)data, dataSize, CRYPT_USERDATA);
		DWORD hashSize = 16;
		BYTE* hashValue = new BYTE[hashSize];
		CryptGetHashParam(hCryptHash, HP_HASHVAL, hashValue, &hashSize, 0);
		cout << "# MD5 хеш: ";
		for (int i = 0; i < hashSize; i++)
			printf("%X%X", hashValue[i] >> 4, 0xF & hashValue[i]);
		cout << endl;
```

## **Experience**

## **Education**

* **University:** Samara State University, Informatics And Computer Engineering

## **English**

**B2**