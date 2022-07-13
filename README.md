# except_script_example
### VPN except script example (openconnect)

* Install Expect Script first
Ex: `sudo apt install expect`, `sudo pacman -S expect`

* Use expect script to automate vpn login.
  * spawn: Creates a new process by running a given program. Ex: spawn sudo openconnect ...
  * expect: If the output matches the specified sentence, input it via `send`.
  * send: Sends string to the current process. 
  * interact: This will give control of the current process over to the user for interaction.
