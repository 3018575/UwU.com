# UwU.com
This a really good game and you should visit this this is a really good game be sigma and play
import colorama
from colorama import Fore, Back, Style
import time

# Initialize colorama
colorama.init(autoreset=True)

# Define colorful text
colors = [Fore.RED, Fore.GREEN, Fore.YELLOW, Fore.BLUE, Fore.MAGENTA, Fore.CYAN, Fore.WHITE]

def print_colorful_text(text):
    for letter in text:
        color = colors[len(text) % len(colors)]
        print(color + letter, end='', flush=True)
        time.sleep(0.1)  # Wait for a short amount of time for effect

# Example usage
if __name__ == "__main__":
    colorful_text = "Hello, Colorful World!"
    print_colorful_text(colorful_text)
    print(Style.RESET_ALL)  # Reset to default style
