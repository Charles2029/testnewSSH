# SSH key
如果已设置 SSH 密钥来与 GitHub 交互，你可能已经熟悉 ssh-agent。 这是一个在后台运行的程序，它将密钥加载到内存中，因此您不需要每次使用密钥时都输入密码。 
最妙的是，你可以选择让服务器访问你的本地 ssh-agent，就像它们已经在服务器上运行一样。 这有点像要求朋友输入他们的密码，以便您可以使用他们的计算机。
[Using SSH agent forwarding](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/using-ssh-agent-forwarding)

<img width="809" alt="image" src="https://github.com/Charles2029/testnewSSH/assets/111632432/89c62225-161e-43f8-a9e9-e466c092f597">

SSH agent forwarding can be used to make deploying to a server simple. It allows you to use your local SSH keys instead of leaving keys (without passphrases!) sitting on your server

//If you've already set up an SSH key to interact with Github, you're probably familiar with ssh-agent.
It's a program that runs in the background and keeps your key loaded into memory,
 so that you don't need to enter your passphrase every time you need to use the key. The nifty thing is,
 you can choose to let servers access your local ssh-agent as if they were already running on the server.
 This is sort of like asing a friend to enter their password so that you can use their computer.

 ## [Connecting to GitHub with SSH](https://docs.github.com/en/authentication/connecting-to-github-with-ssh)
 
 
 ## [Generating a new SSH key and adding it to the ssh-agent](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)
 Generating a new SSH key and adding it to the ssh-agent

When you  *generate an SSH key, you can add a passphrase* to further secure the key. Whenever you use the key, you must enter the passphrase. If your key has a passphrase and you don't want to enter the passphrase everytime you use the key, you can add your key to the SSH agent. The SSH agent manages your SSH keys and remembers your passphrase.
<img width="811" alt="image" src="https://github.com/Charles2029/testnewSSH/assets/111632432/e55fed77-af14-43a9-91f0-99ae218bc31b">
## Generating a new SSH key and adding it to the ssh-agent
Generating a new SSH key and adding it to the ssh-agent
After you've checked for existing SSH keys, you can generate a new SSH key to use for authentication, then add it to the ssh-agent.
After you've checked for existing SSH keys, you can generate a new SSH key to use for authentication, then add it to the ssh-agent.


## The process of generate the SSH Key


After you generate an [SSH key pair,](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account) you must add the public key to GitHub.com to enable SSH access for your account.
👍 After you generate an SSH key pair, you must **add the public key** to GitHub.com to enable SSH access for you account.



















