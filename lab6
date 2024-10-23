#Valeria
def encode_func(password):
    result=''
    for digit in (password):
        newdig= (int(digit)+3)%10#to avoid double digits for ex 8+3=11, will print only 1
        result+=str(newdig)
    return result

def print_menu():
    print('Menu')
    print('-------------')
    print('1. Encode')
    print('2. Decode')
    print('3. Quit')

def decode_function():

    pass
 #Hi vincent, please place your function here


def main():
    password=''
    decoded_password=''
    while True:
        print_menu()
        print()
        selection=input('Please enter an option: ')
        if selection=='1':
            password=(input('Please enter your password to encode: '))
            encoded_password=encode_func(password)
            print('Your password has been encoded and stored!')
            print()
        if selection=='2':
            decoded_password=decode_function(encoded_password)
            print(f'The encoded password is {encoded_password}, and the original password is {decoded_password}')


main()