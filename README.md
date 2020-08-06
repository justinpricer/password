# password
I ended up placing way more than I needed into the javascript file and it was causing the function to not work correctly. It would continue to loop and not generate the password the way it was supposed to in the end. I shortened it and was able to get it to work correctly.

// Else if for 4 negative options
    // if (!confirmCharacter && !confirmNumber && !confirmUppercase && !confirmLowercase) {
    //     choices = alert("You must choose a criteria!");

    // }
    // // First if statement that uses user input prompts to determine choices
    // // Else if for 4 positive options
    // else if (confirmCharacter && confirmNumber && confirmUppercase && confirmLowercase) {

    //     choices = character.concat(number, alpha, alpha2);
    // }
    // // Else if for 3 positive options
    // else if (confirmCharacter && confirmNumber && confirmUppercase) {
    //     choices = character.concat(number, alpha2);
    // }
    // else if (confirmCharacter && confirmNumber && confirmLowercase) {
    //     choices
    //      = character.concat(number, alpha);
    // }
    // else if (confirmCharacter && confirmLowercase && confirmUppercase) {
    //     choices = character.concat(alpha, alpha2);
    // }
    // else if (confirmNumber && confirmLowercase && confirmUppercase) {
    //     choices = number.concat(alpha, alpha2);
    // }
    // // Else if for 2 positive options 
    // else if (confirmCharacter && confirmNumber) {
    //     choices = character.concat(number);

    // } else if (confirmCharacter && confirmLowercase) {
    //     choices = character.concat(alpha);

    // } else if (confirmCharacter && confirmUppercase) {
    //     choices = character.concat(alpha2);
    // }
    // else if (confirmLowercase && confirmNumber) {
    //     choices = alpha.concat(number);

    // } else if (confirmLowercase && confirmUppercase) {
    //     choices = alpha.concat(alpha2);

    // } else if (confirmNumber && confirmUppercase) {
    //     choices = number.concat(alpha2);
    // }
    // // Else if for 1 positive option
    // else if (confirmCharacter) {
    //     choices = character;
    // }
    // else if (confirmNumber) {
    //     choices = number;
    // }
    // else if (confirmLowercase) {
    //     choices = alpha;
    // }
    // // Created space variable to fill uppercase conversion
    // else if (confirmUppercase) {
    //     choices = space.concat(alpha2);
    // };

    // password variable is an array placeholder for user generated amount of length

}
// This puts the password value into the textbox
// Changed function input to use textcontent
// function UserInput(ps) {
//     document.getElementById("password").textContent = ps;

// }
