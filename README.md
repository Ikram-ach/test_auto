# test_auto
def addition(a, b):
    return a + b

def soustraction(a, b):
    return a - b
def division(a, b):
    if b == 0:
        raise ValueError("Division par éro")
    return a / b