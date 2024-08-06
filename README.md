# Challenge-Encriptador

This web application features an easy-to-use interface for encrypting and decrypting text with a custom encryption algorithm. It is designed to be user-friendly, prioritizing simplicity and accessibility. Users can input text into a textarea and choose to either encrypt or decrypt it with the click of a button. The application exclusively handles lowercase letters without accents, ensuring smooth operation.

### Features

+ **Text Encryption and Decryption:** Users can easily encrypt or decrypt their input text by clicking the corresponding button.

+ **User Interface**

    + **Responsive Design:**  The layout adjusts gracefully to different screen sizes, ensuring usability on both desktop and mobile devices.
    + **Animations:** Subtle animations enhance user experience, including a rotation animation for the logo and slide animations for text input and output areas.

+ **Footer:** A fixed footer contains copyright information and links to social media profiles, staying at the bottom of the page for easy access.

+ **Copy to Clipboard:** A button that copies the encrypted/decrypted text to the clipboard, having the same functionality as ctrl+C or the "copy" option from application menus.

+ **Technology Stack:**

    + **Frontend:**  HTML and CSS are used to create a clean and responsive design.
    + **JavaScript:** Manages the encryption and decryption logic.

## Getting Started
Download the project from 
[the repository.](https://github.com/Richi025/Challenge-Encriptador)

You can also clone the file using the following command.

```
git clone https://github.com/Richi025/Challenge-Encriptador.git  
```

Once you have the cloned project in your repository. 

Open the index.html file on your browser:
![Encryptor](./img/image.png)



### Test

![Test](./img/imageP.png)

## Encryption Keys

The requested encryption keys are as follows:

- The letter "**a**" is converted to "**ai**".
- The letter "**e**" is converted to "**enter**".
- The letter "**i**" is converted to "**imes**".
- The letter "**o**" is converted to "**ober**".
- The letter "**u**" is converted to "**ufat**".


## Requirements

The project has the following requirements for use:

- It must work only with lowercase letters.
- Letters with accents or special characters should not be used.
- It should be possible to convert a word to the encrypted version and also convert an encrypted word back to its original version.



    ```
    For example:
    "gato" => "gaitober"
    "gaitober" => "gato"
    ```


- The page must have fields for inserting the text to be encrypted or decrypted, and the user must be able to choose between the two options.
- The result must be displayed on the screen.


## Author

* **Jose Ricardo Vasquez Vega**  - [Richi025](https://github.com/Richi025)

## Date

August 06, 2024

## License

This project is licensed under the GNU License - see the [LICENSE.txt](LICENSE.txt) file for details.
