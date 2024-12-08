# Currency-Conversion-Tool
I designed and implemented the input handling section of the currency converter program. This includes:
1.	Developing a user-friendly menu with clearly labelled options for various currency conversions to ensure ease of navigation:
printf("Currency Exchange Tool\n");
printf("Choose an option:\n");
printf("1: USD to INR\n2: INR to USD\n3: EUR to INR\n4: INR to EUR\n");
printf("5: GBP to INR\n6: INR to GBP\n7: AUD to INR\n8: INR to AUD\n");
printf("9: CAD to INR\n10: INR to CAD\n");
scanf("%d", &option);

2.	Implementing functionality to read the user’s selection and the input amount, ensuring accurate data is captured for processing:
printf("Enter the amount to convert: ");
scanf("%f", &value);

3.	Crafting robust and intuitive input prompts to enhance the overall user experience and reduce potential input errors.
default: 
    printf("Invalid selection. Try again.\n");
    return 0;

This contribution ensures that users can interact seamlessly with the program and select their desired operations with clarity and ease.

I also created the whole powerpoint presentation.
