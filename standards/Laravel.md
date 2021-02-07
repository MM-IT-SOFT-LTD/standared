## Laravel Coding Standard



This is coding standard for laravel developers in order to create production friendly product.



#### Create production friendly product

- Never add or commit third party modules in VCS like **node_modules** or **vendor**
- Never add or commit IDE configuration settings like **.idea** , **.vscode** etc.
- Never add or commit **.env** file in VCS
-  Keep **public** directory as servers document root
- Always compile assets in **production** mode before commit
- Always keep necessary **seeds** to run application without any exception
- Never edit existing migration file, create new migration files to update schema