![ApolloExec](/doc-payload/apolloexec/apolloexec-landscape.svg)

ApolloExec is a Windows agent written in C# using the 4.0 .NET Framework designed to be used in SpecterOps training offerings. A .NET Framework 4.0 Windows Agent for remote code Execution 

# Installation
To install ApolloExec, you'll need Mythic installed on a remote computer. You can find installation instructions for Mythic at the [Mythic](https://github.com/byt3n33dl3/Mythic/) project page.

From the Mythic install directory, use the following command to install ApolloExec as the **root** user:

```
./ApolloExec install github https://github.com/byt3n33dl3/ApolloExec.git
```

From the Mythic install directory, use the following command to install ApolloExec as a **non-root** user:

```
sudo -E ./ApolloExec install github https://github.com/byt3n33dl3/ApolloExec.git
```

Once installed, restart Mythic to build a new agent.

# Notable `Features`
- P2P Communication
- Credential Tracking and Manipulation
- Unmanged PE, .NET Assembly, and PowerShell Script Execution
- User Exploitation Suite
- SOCKSv5 Support

# Special `Thanks`

A big thanks goes to those who have contributed to the project in both major and minor ways.

- Sulaiman Aziz, [@byt3n33dl3](https://twitter.com/byt3n33dl3)
- Cody Thomas, [@its_a_feature_](https://twitter.com/its_a_feature_)
- Calvin Hedler, [@001SPARTaN](https://twitter.com/001spartan)
- Lee Christensen, [@tifkin_](https://twitter.com/tifkin_)
- Brandon Forbes, [@reznok](https://twitter.com/rezn0k)
- Thiago Mayllart, [@thiagomayllart](https://twitter.com/thiagomayllart)
- Matt Hand, [@matterpreter](https://twitter.com/matterpreter)
- Hope Walker, [@IceMoonHSV](https://twitter.com/IceMoonHSV)
- Jack Ullrich, [@winternl_t](https://twitter.com/winternl_t)
- Elad Shamir, [@elad_shamir](https://twitter.com/elad_shamir)
- Ben Turner [@benpturner](https://twitter.com/benpturner)
- Ian Wallace [@strawp](https://twitter.com/strawp)
- m0rv4i [@m0rv4i](https://twitter.com/m0rv4i)
- Harley Lebeau [@r3dQu1nn](https://twitter.com/r3dQu1nn)
- Antonio Quina [@st3r30byt3](https://twitter.com/st3r30byt3)
- Sean Pierce [@secure_sean](https://twitter.com/secure_sean)
- Evan McBroom, [@EvanMcBroom](https://gist.github.com/EvanMcBroom)
- Matt Ehrnschwender, [@M_alphaaa](https://x.com/M_alphaaa)