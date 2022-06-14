## Laravel Coding Standard



This is coding standard for laravel developers in order to create production friendly product.



#### Create production friendly product

1. Never add or commit third party modules in VCS like **node_modules** or **vendor**
2. Never add or commit IDE configuration settings like **.idea** , **.vscode** etc.
3. Never add or commit **.env** file in VCS
4. Keep **public** directory as servers document root
5. Always compile assets in **production** mode before push to production
6. Always keep necessary **seeds** to run application without any exception
7. Never edit existing migration file, create new migration files to update schema
8. Always follow **psr-4** autoloading standard while creating new class
9. Never add or commit **user uploeded media**, but add the folder in VCS in order to create symlink by putting a file ( like .gitignore or .gitkeep )
10. Never server unminified 3rd party stylesheet or javascript file direcly from public folder. Always try to compile your assets (by laravel mix) in order to optimize assets properly.
