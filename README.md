# SA2-mon-6-2021

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        cout << "\nPlease enter your full name: ";
        getline(cin, fullName);

        cout << "Enter the number\n";
        int x, fact = 1;
        cin >> x;
        for (int y = x; y > 0; y--)
        {
            fact = y * fact;
        }
        cout << "The factorial is: " << fact;
    }
    //Exponents
    int num, pow, result = 1, count = 1;

    printf("Enter a number \n");
    scanf("%d", &num);

    printf("Enter the power of a number\n");
    scanf("%d", &pow);



    while (count <= pow) {

        result = result * num;
        count++;
    }

    printf("Result = %d", result);

    return 0;
    }
