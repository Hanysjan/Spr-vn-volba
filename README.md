class Chat:
    def __init__(self, sender, receiver, message):
        self.sender = sender
        self.receiver = receiver
        self.message = message

    def send_message(self):
        print(f"{self.sender} sent a message to {self.receiver}: {self.message}")

# Example Usage
new_chat = Chat(

)
new_chat.send_message()
