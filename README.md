# hello.py-This-program-says-hello-and-asks-for-my-name.-print-Hello-world-print-What-is-your-
# This program says hello and asks for my name.
print('Hello world!')
print('What is your name?')
myName = input()
print('It is good to meet you, ' + myName)

import sys

# Define a main() function that prints a little greeting.
def main():
  # Get the name from the command line, using 'World' as a fallback.
  if len(sys.argv) >= 2:
    name = sys.argv[1]
  else:
    name = 'World'
  print 'Hello', name

# This is the standard boilerplate that calls the main() function.
if __name__ == '__main__':
  main()
  


