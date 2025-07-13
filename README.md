#print("Welcome to the Rule-Based Chatbot!")
print("Type 'bye' to exit.\n")

while True:
    user_input = input("You: ").lower()

    if "hello" in user_input:
        print("Bot: Hi there! How can I help you?")
    elif "how are you" in user_input:
        print("Bot: I'm good, thank you for asking!")
    elif "name" in user_input:
        print("Bot: I'm a simple chatbot made by you!")
    elif "bye" in user_input:
        print("Bot: Goodbye! Have a nice day!")
        break
    else:
        print("Bot: Sorry, I don't understand that.")
