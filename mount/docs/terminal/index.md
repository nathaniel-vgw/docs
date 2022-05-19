# Terminal Tools
This section technically is applicale to any Unix based terminal. There will be options of MacOS and Linux (Ubuntu) in this section as you go through.

## Zsh
Zsh is installed by default after after Catalina but is very powerful compared to bash. Zsh also called the Z shell, is an extended version of the Bourne Shell (sh), with plenty of new features, and support for plugins and themes. Since it’s based on the same shell as Bash, ZSH has many of the same features, and switching over is a breeze.

***Install***

=== "Linux"
    ```bash
    sudo apt install zsh
    ```

## Oh My Zsh!
Oh My Zsh is an open source, community-driven framework for managing your zsh configuration.

Sounds boring. Let's try again.

Oh My Zsh will not make you a 10x developer...but you may feel like one.

Once installed, your terminal shell will become the talk of the town or your money back! With each keystroke in your command prompt, you'll take advantage of the hundreds of powerful plugins and beautiful themes. Strangers will come up to you in cafés and ask you, "that is amazing! are you some sort of genius?"

^ Ripped Directly from their GitHub Page

***Install***

=== "curl"
    ```bash
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```
=== "wget"
    ```bash
    sh -c "$(wget -O- https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```
=== "fetch"
    ```bash
    sh -c "$(fetch -o - https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```

***Links***

- [Github](https://github.com/ohmyzsh/ohmyzsh)