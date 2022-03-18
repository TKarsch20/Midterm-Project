@@ -1,37 +1,13 @@
## Thatcher Karsch

You can use the [editor on GitHub](https://github.com/TKarsch20/Midterm-Project/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
import math

def get_nonnegative_float_from_user(prompt):
    while True:
        try:
            input_value = float(input(prompt))
            if (input_value < 0):
                print("Only nonnegative values are allowed. Please re-enter the value.")
                continue
            break
        except ValueError:
            print("Please enter a nonnegative numerical value.")
            continue
    return input_value

def perform_calculation():
        radius = get_nonnegative_float_from_user("Enter the cylinder's radius: ")
        height = get_nonnegative_float_from_user("Enter the cylinder's height: ")

        area = (2 * math.pi * radius * height + 2 * math.pi * radius **2)
        print ("The area of the cylinder is" ,area, "feet^2.")

        pints = (area / 5) 
        (math.ceil(pints)) 
        print ("There are" ,(math.floor(pints)), "pints required to coat the cylinder.") 

        cost = (pints * 8.75)
        (math.ceil (cost))
        print ("The total cost will be $" ,(round (cost, 2)))

def main():
        print("This program calculates the cost of coating a cylinder along with the area and the number of pints required.")
        while True:
                perform_calculation()
                response = input("Would you like to perform another calculation (y/n)? ")
                if (response == "y"):
                        print("")
                        continue
                else:
                        break

main ()
                

```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/TKarsch20/Midterm-Project/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


[Next](NationalGuard.md)
