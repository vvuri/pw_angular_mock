## ToDo
- Simple Angular App
- Mock for API
- Playwright E2E test


## Steps
### Create project
1. Create project in PyCharm - pw_angular_mock
2. Create repo om GitHub
3. Telnet:
    ```
    $ git init
    $ git add README.md
    $ git commit -m "first commit"
    $ git branch -M main
    $ git remote add origin https://github.com/vvuri/pw_angular_mock.git
    $ git push -u origin main
    ```    
4. Run venv
   - Open pyCharm --> Go to Settings --> Tools --> Terminal
   - C:\Windows\system32\cmd.exe /K  "venv\Scripts\activate.bat"
   - reopen terminal	
5. Install https://playwright.dev/python/docs/intro

   ``` $ pip install pytest-playwright ```
    > pytest_playwright-0.3.0
    > playwright-1.29.1
    
   ```$ playwright install```    
    > Downloading Chromium 109.0.5414.46 
6. $ pip install flake8
7. $ pip freeze > requirements.txt 	
8. project structure
    > /src - for project
      /tests - for tests
9. first test
    https://playwright.dev/python/docs/writing-tests

### Next

- API mock test
    - Mocking API Response | Playwright Tutorial Part - 81
        https://www.youtube.com/watch?v=c7zCQ8FKih4
    - https://playwright.dev/python/docs/mock

- Playwright + xPath

- VSCode
    https://www.youtube.com/watch?v=6fapvF1uYo0

- PageObject model
    https://www.youtube.com/watch?v=9w6tDpQC4lE

- Work in docker or VM

- Search 
    https://www.bing.com/search?q=Playwright

- Playwright API Testing[CRUD] with Python/PYTEST
    https://www.youtube.com/watch?v=_i-XNZSSa5Q

- Doc
    https://playwright.dev/
    https://learn.microsoft.com/ru-ru/microsoft-edge/playwright/
- 
- PW example
    https://github.com/JoanEsquivel/playwright-python-test-framework
