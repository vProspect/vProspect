## Disclaimer 

Around late december of 2025, a few exploiters emerged using the infamous "desync" hack. This tool was created to combat such exploiters. Only use this tool when you come across a person using desync specifically in SSL.

# Usage

*This tool was created for windows 10-11 (not mobile). Use ONLY if you come across a desync exploiter, it is useless otherwise.*

1. Download the latest release
2. Extract the file into a folder
3. **Wait** until you are in a match, then run `VisualProspect.exe`

*You are able to stay in a queue for rank. When you transport to the new server, you will have to "attach" again.*

## Notes

`vProspect` works using server-sided validation. It leverages the weakness that desync exploiters interact with something the server can see at anytime. vProspect modifies bytecode inside Roblox to create a lua environment. The downside is that vProspect will not work if roblox updates. You will need to wait until *I* or a contributor pushes an update. As of 1/10/2026, this tool is currently **NOT** bannable. When using third-party antivirus software such as malwarebytes, it is required to explicitly allow both `Retrograde.dll` and `VisualProspect.exe` to avoid false positives. On each release, specific files are sent to microsoft to validate and remove false detections. Thus windows defender will not flag this software as malicious.

### Contributors

- filefilza (core logic, external execution environment, teleport handler)
