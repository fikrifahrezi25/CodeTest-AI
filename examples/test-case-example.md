def calculate_discount(price, discount):
    if price < 0:
        raise ValueError("Price cannot be negative")

    if discount < 0 or discount > 100:
        raise ValueError("Invalid discount")

    return price - (price * discount / 100)Analisis kode Python berikut.

Buat test case yang mencakup:
1. normal case
2. boundary case
3. edge case
4. invalid input
5. error handlingGunakan format yang telah ditentukan dan lakukan Coverage Review setelah membuat test case.
