# Auxiliary Project 1 - Linux Shell Scripting

This is a project where I automated user creation and onboarding with Linux shell scripting.

Instead of adding users one by one into the server (which is very tedious), I automated the process to add a list of users to the server with the required privileges. This is far more efficient as a large number of users can be added with just a single click.

The script is written in a way that it checks the system first if the user exists and if they do, it returns a message saying the user exists. If the user doesn't exist, it creates the user with the required privileges and adds them to an already created group called `developers`.

Kindly watch `AuxProjDemo` for a demonstration on the workings of the script.