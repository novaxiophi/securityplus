<link rel="stylesheet" href="https://github.com/novaxiophi/securityplusTraining.githubpages.io/blob/master/todo/styles.css">

1. Start by importing the hashlib library:

```python
import hashlib
```

2. Next, let's input the password you want to hash:

```python
password = "mysecretpassword"
```

3. Now, let's hash the password using the SHA-256 algorithm:

```python
hashed_password = hashlib.sha256(password.encode()).hexdigest()
```

4. Finally, let's print the hashed password:

```python
print("Original Password:", password)
print("Hashed Password:", hashed_password)
```

Here's what the output will look like after you run the code:

Original Password: mysecretpassword

Hashed Password: 0f9f4fe8075b023a47b58f0b202c23a903d4b11b83ed5a83a5c87840da4cdbe9

<details>
  <summary>Click to see explanation</summary>
  
    
  In this example, we're using the SHA-256 algorithm from the `hashlib` library to hash a password. The `hexdigest()` method returns the hashed result as a hexadecimal string. Hashing is a common technique used to secure sensitive data like passwords.

  Additionally, hashing is commonly used to verify the integrity of software. By comparing the hash of a downloaded software with the original hash provided by the software provider, users can ensure that the software has not been tampered with during download or distribution.

</details>

---
<details>
  <summary>Click to see explanation</summary>
  
    
there exists a wizard known as Seamus O'Crypt, a keeper of secrets and a master chef. His methods are whispered but unkown, he harnesses the spirits of dead rats to weave his dark spells.

Picture Seamus, draped in shadows, his computer brewing with the remains of rats that once roamed the desolate alleys of forsaken code. With bony fingers, he inscribes the ancient spell "Rathash-256" onto tattered pages, a pact that binds the dead rats' essence to the ethereal world of encryption.

As passwords and codes are fed into his sinister "incantation" aparatus, the spirits of the rats intertwine, forming twisted knots of secret symbols that defy understanding. It's a forbidden dance of death and data, a wretched symphony that echoes the torment of the rats' demise.
as they dance in a symphony of quick sqeals and squeaks. their blood splatter the pages leaving uncomprihensible markings 

But Seamus doesn't stop there. He possesses the power to infuse anything—pages, archives, spells, and even elements digitally represented. He can intertwine their very essence with the cursed vitality of the rats. The outcome is a maleficent seal, an indelible mark that eternally brands whatever is infused. Thus, it becomes a creation born from the most obscure corners of code

In the darkness, a harsh lesson emerges. Those who meddle with Seamus's dark arts soon discover that the dead rats' vengeance isn't easily silenced. In the haunted hours of the night, they hear spectral squeaks and scuttles, the whispers of the rats seeking retribution for their misuse.

And so, the tale of Seamus O'Crypt serves as a somber reminder that even in the digital realms, dark deeds bear consequences. The dead rats' essence, entwined with codes and curses, stands as a haunting testament to the price paid for tampering with forbidden knowledge.

</details>

---
<details>
  <summary>Fill in your explanation</summary>

Here is my explanation

Think of hashing like creating a secret recipe for your favorite dish. When you cook that dish, you follow the recipe exactly, and it tastes the same every time.

In our example, instead of a recipe, we're dealing with passwords and computer programs. Imagine you have a secret word, and you want to keep it safe. Hashing is like putting that word through a magical machine that turns it into a special code. This code is unique and looks like a bunch of random symbols.

Now, let's talk about computer programs. Just like how we want to make sure our secret word stays safe, we want to make sure our computer programs are safe to use. Hashing helps with this too! When we download a program, we can use the magical machine to turn its code into a special code. We can compare this code to the one given by the program maker. If they match, it means the program hasn't been changed by anyone, like a seal of approval. It's like checking a toy's seal to make sure it's not broken before playing with it.

So, hashing is like creating secret codes to protect things we care about, whether it's our passwords or the computer programs we use.

</details>

---
Please note that the hashed value provided in the example is for illustration purposes only and may not match the actual hash you would get when running the code. Update the hashed value with the correct result after running the code snippet.
