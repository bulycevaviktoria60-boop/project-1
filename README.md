class Animal:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def eat(self):
        pass

    def sleep(self):
        pass


class Bird(Animal):
    def fly(self):
        pass


class Fish(Animal):
    def swim(self):
        pass


class Mammal(Animal):
    def walk(self):
        pass


if __name__ == "__main__":
    parrot = Bird("Кеша", 2)
    shark = Fish("Джо", 5)
    lion = Mammal("Симба", 4)

    print(f"{parrot.name} (Возраст: {parrot.age})")
    parrot.eat()
    parrot.sleep()
    parrot.fly()

    print(f"\n{shark.name} (Возраст: {shark.age})")
    shark.eat()
    shark.swim()

    print(f"\n{lion.name} (Возраст: {lion.age})")
    lion.sleep()
    lion.walk()
