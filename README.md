# Elite101-Prework
# Added Chatbot structure, enviroment and psudeocode:
#Import necessary libaries 


#Define a function to great the user (Pseudocode)
def greet(): 
  print("Hello! I am your virtual chatbot. Can't wait to assist you!")
  print("But First Answer a Few Questions Below ↓")
  print("")
greet()

#Define a function to take user input (Pseudocode)
def get_user_input(): 
  user_input = input(" What is your preferred name?: ")
  print('')
  print(f'Nice to meet you {user_input} 👋')
  print('')
  user_input_2 = input("How old are you?: ")
  return user_input, user_input_2

#Define a function to process user-input and Generate a response 
def generate_response(user_input): 
 pass #write func. code here 

#Define a function to displau the Bot's response 
def display_response(response): 
  pass #write func. code here 

#Define the Main Chat Loop 
def main(): 
  greet()

while True: 
  user_input = get_user_input() 

if user_input.lower() == 'exit': 
   print("Goodbye! Have a nice day :)")

response = generate_response(user_input)
display_response(response)

#Entry point of the program 
if __name__ == "__main__":
  
  main()
