**FBX to M3G Converter - Complete Setup Guide**

-Requirements
Before you begin, make sure you have installed:

•C# programming language support

•.NET SDK 7 or 8

•VS Code with C# extension and C# dev kit logged on your Microsoft account 

•All applications properly added to your system PATH

•(Follow this tutorial exactly and you'll be good to go!)

-Step-by-Step Conversion Process

•Step 1: Open Command Prompt
Press Windows + R, type cmd and press Enter to open Command Prompt.

•Step 2: Run the Conversion Command
Copy and paste this command: cd C:\Users\Rolero\Downloads\FBX2M3G
dotnet build "C:\Users\Rolero\Downloads\FBX2M3G\FBX2M3G.csproj" -c Release
dotnet run --project "C:\Users\Rolero\Downloads\FBX2M3G\FBX2M3G.csproj" -- input.fbx output.m3g

-Important Notes

•File Naming Rules:
Replace the username in \Users\Rolero\Downloads with the your actual one in the code you'll copy, (example: \Users\Example\Downloads\FBX2M3G...)

Replace input.fbx with your actual FBX file name

Replace output.m3g with your desired output name

Keep the .fbx and .m3g extensions

You can use any names you want

Make sure your FBX file is in the same folder as the converter

-Expected Results:

✅ If successful: You'll see "Conversion completed successfully!" message

✅ Output: A new .m3g file will be created in the same folder

❌ If errors: Check that all requirements are installed correctly

-Troubleshooting
Make sure you installed all required apps and extensions

Make sure everything is in your system PATH

Make sure your FBX file exists in the correct folder

Make sure your C# Dev Kit logged in with a Microsoft account 

Provide feedback about your results - it might work or might need adjustments

-Final Check
Before running, verify:

.NET SDK 8 or 7 is installed

VS Code with C# extension with C# Dev Kit is ready

You're in the correct folder in Command Prompt

Your FBX file is available

You're using the correct file names in the command

The process is easy once everything is set up correctly! Just follow these steps and you should be able to convert your FBX files to M3G format, Enjoy!! :D (I'll soon find a way to make an app for this to easily open it instead of doing codes)
