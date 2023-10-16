# OTP Generator

## Introduction

The OTP Generator is a fun and interactive tool designed to create personalized One-Time Passwords (OTPs). In today's world, the use of OTPs for secure access and verification is ubiquitous, making it essential to have a reliable and customizable OTP generator at your disposal. This Java-based program empowers users to create OTPs with ease.

## Features

- **Customizable Length:** You can specify the length of the OTP you want to generate. This tool is adaptable to your security requirements.

## Getting Started

1. Clone the repository to your local machine:

   ```sh
   git clone https://github.com/dollpriyanka/otp_generate.git
   ```

2. Compile the Java program:

   ```sh
   javac otp.java
   ```

3. Run the program:

   ```sh
   java otp
   ```

4. The generated OTP will be displayed in the console.

## Usage

You can customize the length of the OTP by modifying the `length` variable in the Java code. By default, it generates a 4-digit OTP. To generate OTPs of different lengths, simply change the value of `length` in the `main` function.

```java
int length = 4; // Change this to your desired OTP length
System.out.println(OTP(length));
```

## Contributions

Contributions are welcome! If you'd like to improve this OTP generator or add new features, please open a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License

This OTP Generator is open-source and available under the [MIT License](LICENSE).
