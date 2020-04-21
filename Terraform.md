# TERRAFORM 

(Infrastructure as a code)

Terrform is a tool for building, changing and versioning infrastructure safely and efficiently.

## Things to know
 * Terraform is written in Go-Language
 * 



## Configuration Files 
 These files describe to terraform the components needed to run a single application or your entire datacentre

   - Terraform generated an execution plan describing what it will do to reach the desired state. then executes the described infrastructure



## Variables 
   This can be to store sensitive information you wouldn't want others to see
   Define a value you'll use multiple times in the configuration
   A placeholer for information that changes depending on the deployment

    *syntax*

      variable "var_example" {
         
      } 

