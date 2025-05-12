# Instructions_Inventary_Software

## Description
The porposite of the program is an inventory of a store that allows adding products, to eliminate and update products. 

## Initialization
To get started with this project, follow these steps:

1. **To descompress the archive.zip**
2. **To open the new discompress archive**
3. **Open with your favorite EditorCode**
4. **Once the file is opened run it through a dedicated terminal**
5. **Ready up**

## Documented input and output data example
        1.()op = input("Choose an option: ")#creation de variable op for the interaction the menu options
        print()
        print(YELLOW+f"Welcome to ColombianShop"+RESET)
        print()
        print(YELLOW+f"1. Add products"+RESET)
        print(YELLOW+f"2. Consult Products"+RESET)
        print(BLUE+f"3. Update prices"+RESET)
        print(BLUE+f"4. Delete products"+RESET)
        print(DANGER+f"5. Total value of inventary"+RESET)
        print(DANGER+f"6. Exit"+RESET)
        
        2.()if op=='1':
           #add the arguments that we need for operate with the user
           name_product=input("Input the name of product: ")
           price=int(input("Input the price of product: "))
           inventary=int(input("Input the avaible inventary for the product: "))
           add_product(name_product,price,inventary)#call the function

        3.()elif op=='2':
         
         name_product=input("Input the name product of you need search: ").lower()#.lower() for except 
         the problems with the capital letters and lowers in the searching of the product
         consult_product(name_product)

         4.()elif op=='3':

         name_product=input("Input the name product that you need update: ").lower()
         new_price=int(input("Input the new price of product: "))
         updated_price(name_product,new_price)


         5.()elif op=='4':
         name_product=input("Input the name of product that you need remove: ").lower()
         remove_product(name_product)

         6.()elif op=='5':
           calculate_total_value()

          7.()elif op=='6':
           print(YELLOW+f"Close system..."+RESET)#option for exit of the system
          else:
           print(DANGER+f"Invalid option..."+RESET)
           


         menu()#menu activation 


       























   
