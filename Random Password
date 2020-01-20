#!/bin/python3
def main():
	import random
	chars = "abcdefghijkmnopqrstuvwxyz1234567890ABCDEFGHJKLMNOPQRSTUVWXYZ!@#$%^&*"
	length = input("How many characters would you like your password to be?")
	length = int(length)
	amount = input("How many passwords do you need?")
	amount = int(amount)

	for p in range(amount):
		password = ''
		for c in range(length):
			password += random.choice(chars)
		print(password)

	repeat = input("Would you like to generate new passwords?")
	if repeat == "yes" or "y":
		main()


main()
