# Visual Studio Code + ASP.NET Core 1.0 - Windows Setup

Setup steps for ASP.NET Core 1.0 development with Visual Studio Code for Windows.

###1. Find a good command line tool (like Conemu) - Optional 
- https://conemu.github.io

###2. Install the latest version of .NET Command Line Interface (.NET CLI).
- https://github.com/dotnet/cli

###3. Install NPM (Node Package Manager)

- NPM can be installed using Installing Node.js and updating npm.
- https://docs.npmjs.com/getting-started/installing-node
- <i>npm install npm -g</i>

###4. Install Yeoman
- http://yeoman.io/learning/
- <i>npm install -g yo</i>

###5. Install Aspnet Yeoman generator
- https://github.com/omnisharp/generator-aspnet
- <i>npm install -g generator-aspnet</i>

###6. Install C# for Visual Studio Code (powered by OmniSharp)
- https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp
- Launch VS Code Quick Open (Ctrl+P), paste the following command, and type enter.
- <i>ext install csharp</i>

###7. Instructions for setting up the .NET Core debugger
- https://github.com/OmniSharp/omnisharp-vscode/blob/master/debugger.md

###8. Enable Portable PDBs
- https://github.com/OmniSharp/omnisharp-vscode/wiki/Portable-PDBs#net-cli-projects-projectjson

###9. Create ASP.NET Core 1.0 empty web application using Yeoman generator
- <i>yo aspnet</i>

- F5 will now run the website on http://localhost:5000 and the breakpoint will be hit.

"These steps can be replicated in Mac OS or Linux environments as Visual Studio Code and ASP.NET Core 1.0 are cross platform open source projects".

###Reference:
- http://www.mithunvp.com/asp-net-core-visual-studio-code-yeoman/

<p>
For fast UI development and page preview:
</p>

###Install Light-Server
- Lightweight development node server for serving a web app, providing a fallback for browser history API, loading in the browser, and injecting scripts on the fly.
- https://www.npmjs.com/package/lite-server
- https://github.com/johnpapa/lite-server

<p>
Now open wwwroot folder in console and run “lite-server”, it opens up browser and displays “index.html“.
</p>










