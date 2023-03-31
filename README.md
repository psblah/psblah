### Hi there 👋

 ___     _____    ____     _          ___     _    _ 
|    |  /  ___|  |  _ \\  | |        /   |   | |  | |
| /| |  \\ `--.  | |_) |  | |       / /| |   | |__| |
| ___|   `--. \\ |  _ <   | |      / / | |   |  __  |
| |     /\\__/ / | |_) |  | |___  /  ___ |   | |  | |
|_|     \\____/  |____/   |_____| \\/  |_|   |_|  |_|



```python
def main():
    characters = {
        'P': ['  P P  ', ' P   P ', ' P   P ', ' PPPPP ', ' P     ', ' P     ', ' P     '],
        'S': [' SSSSS ', 'S     S', 'S      ', ' SSSSS ', '      S', 'S     S', ' SSSSS '],
        'B': ['BBBBB  ', 'B    B ', 'B    B ', 'BBBBB  ', 'B    B ', 'B    B ', 'BBBBB  '],
        'L': ['L      ', 'L      ', 'L      ', 'L      ', 'L      ', 'L      ', 'LLLLLL '],
        'A': ['   A   ', '  A A  ', ' A   A ', ' AAAAA ', 'A     A', 'A     A', 'A     A'],
        'H': ['H     H', 'H     H', 'H     H', 'HHHHHHH', 'H     H', 'H     H', 'H     H']
    }

    message = 'PSBLAH'
    for i in range(7):
        line = ''
        for char in message:
            line += characters[char][i]
            line += ' '
        print(line)

if __name__ == '__main__':
   main()
```


<!--
**psblah/psblah** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
