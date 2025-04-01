# O
name = (input('What is your name?'))
surname = (input('What is your surname?'))
nickname = name[0][:1].capitalize() + name[1][:2] + surname[0][:1].capitalize() + surname[1][:2]
print('Hello',name.capitalize(),surname.capitalize(),'\n','Hello',nickname)
