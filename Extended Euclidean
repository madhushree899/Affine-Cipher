def extended_gcd(a, b):
    if a == 0:
        return b, 0, 1
    else:
        gcd, x, y = extended_gcd(b % a, a)
        return gcd, y - (b // a) * x, x
 
 
if _name_ == '_main_':
 
    gcd, x, y = extended_gcd(20, 30)
    print('The GCD is', gcd)
    print(f'x = {x}, y = {y}')
