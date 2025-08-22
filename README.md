# qr-code-generator (BUCC project)

# QR Code Generator – Tutorial
This is a simple QR Code Generator Web project.

# What the project does
1. First enter any text or URL.
2. It instantly generates a scannable QR code using an online API  (https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=)
3. The QR code can be scanned with a mobile device to open the text/URL and can be converted to a downloadable image.

# Tools / Languages used
1. HTML -> for structure.
2. CSS -> for styling and layout
3. JavaScript -> for QR code generation logic
4. QR Server API (api.qrserver.com) -> to create the QR code

# Steps to build and run it
1.	Download the files from repository: https://github.com/showmitg/qr-code-generator
2.	Open the project folder.
3.	Open index.html in browser.
4.	Enter text/URL in the input box. Click “Generate QR code”  button or press enter.
5.	A QR code will appear instantly.

#  Key Features:
1. Simple and clean.
2. Works instantly without any backed integration.
3. Error animation if no input is given.
4. Uses free and reliable API.

# Challenges faced:
1. What happens if the user clicks "Generate QR code" with no text/URL.
2. Separately integrating Enter key.
3. Size of the box and text was a bit confusing for me.
4. Creating animation.
5. Image popup had to be smooth. But the QR was popping up suddenly.
6. To ensure it works both in Mobile and Desktop I had to add “viewport”.

#Future Problems (Not solved yet)-
1. Preventing download before a QR code is generated.
2. Integrated API may have some limitations.
3. Offline usage (current API requires internet).



