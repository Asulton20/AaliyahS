# AaliyahS Module 8 
#Aaliyah Sulton
#12/10/2022

class character:"Alex"
    def __init__(self, nickname, weapons, weaknesses):
        self.nickname = nickname
        self.weapons = weapons
        self.weaknesses = weaknesses

    def get_model(self):
        return self.nickname

    def get_year(self):
        return self.weapons

    def get_color(self):
        return self. weaknesses

    def profile(self):
        return self.nickname, self.weapons, self. weaknesses

player1 = character("Alex")
player1.nickname = 'Bragger'
player1.weapons = ['bowling ball', 'car keys', 'pocket knife', 'rope', 'candy bar']
player1.weaknesses = ['slow']
for item in player1.weapons:
    print("bowling ball: ", item)

for debuff in player1.weaknesses:
    print("slow: ", debuff)
player2= character("Maddy")
player2.nickname= 'Thunder'
player2.weapons = ['bowling ball','keys','pocket knife','wallet']
player2.weaknesses=["fast"]
for item in player2.weapons:
    print("bowling ball: ",item)
player3= character("Jay")
player3.nickname= 'Kobe'
player3.weapons= ["bowling ball","wallet","bottle water","rope","candy bar"]
player3.weaknesses=["slow"]
for item in player3.weapons:
    print("bowling ball: ",item)
player4=character("Jeremiah")
player4.nickname='Fire'
player4.weapons=["bowling ball","wallet","bottle water","100 dollars"]
player4.weaknesses=["slow"]
for item in player4.weapons:
    print("bowling ball:",item)
