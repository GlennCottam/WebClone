# WebClone
A full fledged web interface for RClone with task scheduling, host configuration, and endpoint specification.

# Inspiration
Years ago, I decided to try out the official RClone webgui and did not have much success with it. I find it could be heavily updated with unique features and abilities.

The general idea came from an application I was working on. It runs locally on desktop and automates copying of files depending on a few logistics. Overall, I put a lot of work into it, when I should have started working on my OWN WebGUI.

Hind sight 20/20 eh?

This project aims to do what the official RClone WebGUI cannot, on its own platform, and hopefully in the future be docker friendly.

# Scope
- WebGUI with the following functions:
  - Host specification (where)
  - Task scheduling (when)
  - RClone configuration [ie. SMB, SFTP etc...] (how)
- Run on Python
- Log and track success / failure rates
- Email notification configuration
