This is based on the Angular template created with 'dotnet new angular'.

It uses ASP.NET Core 2 and Angular 7.

It also uses an SSL certificate for secure connection.

Instructions how to create the certificate are here:

https://www.humankode.com/asp-net-core/develop-locally-with-https-self-signed-certificates-and-asp-net-core

Warning:

OmniSharp in VS Code gives errors as described here:

https://github.com/OmniSharp/omnisharp-vscode/issues/2965

Replace: sudo apt-get install dotnet-sdk-2.2 

With: sudo apt-get install dotnet-sdk-2.2=2.2.105-1

Do not update if prompted by the OS, until this is resolved!

Finally, I just love to see the green padlock and the message "Connection is secure". After all, this is why I search high and low to find how to implement an SSL Certificate!
