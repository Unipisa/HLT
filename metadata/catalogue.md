## SWHAPPE catalogue.md Template

Here we propose a template for catalogue<span>.md for SWHAPPE.

Each Item in the `raw_materials` folder of Depository should have a corresponding record on the `catalogue.md` with the structure below..

Please note that:
* Name and Surname of actors should be linked to their paragraph in [actors.md](./actors.md) file;
* Items should be linked to the file [inside the repository](./raw_matherials/);
* On the [second part of the Catalogue](./catalogue.md#SW_NAME-Catalougue-Tree) should be copied the result of the command `tree -a` ;
* Notes are optional;
* *Warehouse:* is optional - should be used only when a physical warehouse is used to store material taken from the *origin*.

Example of Actor link:
~~~
[Name Surname](./actors.md#name-surname)
~~~
Example of Item link:
~~~
[Item Name](./raw_materials/example_file.zip)
~~~


# SW_NAME Catalougue


* **[Item Name](./raw_materials/example_file.zip)**
  * *Origin:* 
  * *Warehouse:*
  * *Authors:* [Name Surname](./actors.md#name-surname)
  * *Collectors:* [Name Surname](./actors.md#name-surname)
  * *Description:* 
  * *Notes:*
  
.

# SW_NAME Catalougue Tree


result of `tree -a`  on the `raw_materials` directory.
