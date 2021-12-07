# Python-XOR-encryption-decryption-script
Python encrypt.py/decrypt.py scripts that take a key and a command line as a parameter file and performs XOR encryption / decryption using the given key. The program will use the key to encrypt the contents of the file.
# Team members
* Crivoi Carla
* Cucoș Maria-Marianita
* Nechita Maria-Ilinca
# Running methods
* Script encryption :
python encrypt password input.txt output
* Script decryption :
python decrypt output password input_recuperat.txt
# Description of encryption
Extract from the command line the file that contains the text to be encrypted and the key. The function in which each character in the initial text is encrypted by the xor operation with a key character is called. The encrypted text is displayed in the indicated file.
# Description of decryption
Read the text to be decrypted from the file indicated in the command line and the key. The function that uses the xor operation to decrypt the text is called.
The decoding is displayed in the file indicated on the command line.
# Documentation
* https://www.geeksforgeeks.org/python-sys-module/
* https://www.geeksforgeeks.org/convert-binary-to-string-using-python/
* https://www.geeksforgeeks.org/xor-cipher/
* https://samsclass.info/124/proj14/VPxor.htm
* https://youtu.be/PZtei6ijmSY
# Partea 1
* Numele echipei : Ethical Hacker
* Numele echipei adverse : ASCProiect
* Parola echipei adverse : proiectuni
* Mod de lucru : Am folosit operatia xor intre elementul de pe pozitia i din textul input si elementul de pe pozitia i din textul output, astfel obtinand cheia de mai multe ori. Am refolosit algoritmul de criptare din partea 0 a proiectului cu usoare modificari ( in loc de cheie, s-a folosit textul din output).
