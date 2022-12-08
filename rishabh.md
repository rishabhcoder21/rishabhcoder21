Create an API that lists the title, description based on the category passed as an input parameter.

https://title/description?category=title

Create an API that would save a new entry with all the relevant properties which retrieves values from the endpoint GET /entries.

https://title/description/auth/cors?category=title

what are the key things you would consider when creating/consuming an API to ensure that it is secure and reliable?

Prioritize security
Inventory and manage your APIs
Use a strong authentication and authorization solution.
Practice the principle of least privilege
Encrypt traffic using TLS
Remove information that’s not meant to be shared
Don’t expose more data than necessary
Validate input. Never pass input from an API through to the endpoint without validating it first.
Use rate limiting. Setting a threshold above which subsequent requests will be rejected (for example, 10,000 requests per day per account) can prevent denial-of-service attacks.
Use a web application firewall. Ensure that it is able to understand API payloads.

Theoritical Challenge

Suppose you have a CSV file with the data below.



A1: 5, A2: 7, A3: 9, B1: 3, B2: 8, B3: =4+5, C1: =5+A1, C2: =A2+B2, C3: =C2+B

I want a program that will take the CSV input above and produce CSV output with the results.  If it is a value, then return a value.  If it is a formula then calculate the formula and return the value of that formula.

How will you tackle the challenge above?
What type of errors you would you check for?
How might a user break your code?

stringInput = “a1: 5, a2: 7, a3: 9, b1: 3, b2: 8, b3: =4+5, c1: =5+a1, c2: =a2+b2, c3:c2+b”


function calculation (string: stringInput){

for(int i=0;i<stringInput;i++)
{
  if(char[i]=='+'||char[i]=='-'||char[i]=='/'||char[i]=='*')
  {
     calculate=input1 char[i] input[2]
  }
  else
  {
     return value
  }

return output
}



output = “a1: 5, a2:7, a3: 9, b1: 3, b2: 8, b3: =9, c1: =10, c2: =15  c3: 18”
