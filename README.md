# Regex-for-Common-Use-Case


```

if (name.isBlank() || !Pattern.matches("^[\\p{L} .'-]+$",name)) {
         //  Invalid first name
}

if (phone.isBlank() || !Pattern.matches("^[0-9]{10}$",phone)) {
  //Invalid phone number
} 

if (email.isBlank() || !android.util.Patterns.EMAIL_ADDRESS.matcher(email).matches()) {
 //Invalid email
}

if (password.isBlank() || !Pattern.matches("^(?=.*[A-Z])(?=.*[!@#\$&*])(?=.*[0-9])(?=.*[a-z]).{8,15}\$",password)) {
//Strong password required, include special characters, numbers,uppercase and lowercase letters
}

```
