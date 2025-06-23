class Queue:
    def __init__(self):
        self.numbers = []
        self.tasks = []
        self.names = []
        self.letters = []
        self.objects = []

    # Add items
    def add_number(self, item):
        self.numbers.append(item)

    def add_task(self, item):
        self.tasks.append(item)

    def add_name(self, item):
        self.names.append(item)

    def add_letter(self, item):
        self.letters.append(item)

    def add_object(self, item):
        self.objects.append(item)

    # Remove items
    def remove_number(self):
        self.numbers.pop(0)

    def remove_task(self):
        print(self.tasks.pop(0))

    def remove_names(self):
        c = 0
        while c < 4:
            self.names.pop(0)
            c += 1

    def remove_letter(self):
        self.letters.pop(0)

    def remove_object(self):
        self.objects.pop(0)


# Numbers
queue = Queue()
queue.add_number(10)
queue.add_number(20)
queue.add_number(30)
queue.add_number(40)
queue.add_number(50)
queue.remove_number()
queue.remove_number()
print(queue.numbers)

# Tasks
queue.add_task("Wash dishes")
queue.add_task("Study")
queue.add_task("Run")
queue.remove_task()
print(queue.tasks)

# Names
queue.add_name("Ana")
queue.add_name("Bruno")
queue.add_name("Carlos")
queue.add_name("Diana")
queue.remove_names()
print(queue.names)

# Letters
queue.add_letter("X")
queue.add_letter("Y")
queue.add_letter("Z")
queue.remove_letter()
queue.add_letter("W")
queue.add_letter("V")
print(queue.letters)

# Objects
queue.add_object("Phone")
queue.add_object("Charger")
queue.add_object("Headphones")
queue.add_object("Tablet")
queue.remove_object()
queue.remove_object()
queue.add_object("Laptop")
print(queue.objects)
