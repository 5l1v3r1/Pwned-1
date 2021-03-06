# Pwned - Check Your Passwords

Pwned is a simple command-line python script to check if you have a password that has been compromised in a data breach. This script uses [haveibeenpwned](https://haveibeenpwned.com/API/v3) API to check whether your passwords were leaked during one of the many breaches of online services.

This API uses [k-Anonymity model](https://en.wikipedia.org/wiki/K-anonymity) that allows a password to be searched for by partial hash in order to anonymously verify if a password was leaked without disclosing the searched password.

<p align="center">
  <img src="https://user-images.githubusercontent.com/55880211/78676221-c7131200-7903-11ea-9475-c86fb0be3962.png">
</p>

## How pwned script works
<p align="center">
  <img src="https://user-images.githubusercontent.com/55880211/78675721-1573e100-7903-11ea-8f9d-4e411b897e6f.png">
</p>

### Git Installation
```
# clone the repo
$ git clone https://github.com/sameera-madushan/Pwned.git

# change the working directory to Pwned
$ cd Pwned

# install the requirements
$ pip3 install -r requirements.txt
```

## Usage

```
python pwned.py -p <your password here>
```

### Support & Contributions
- Please ⭐️ this repository if this project helped you!
- Contributions of any kind welcome!

## License
MIT ©[sameera-madushan](https://github.com/sameera-madushan)
