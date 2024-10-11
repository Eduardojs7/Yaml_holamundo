# Yaml_holamundo

history:
  - command: dotnet --version
  - command: ansible --version
  - command: dotnet new web -n HelloWorldApp
  - command: nano hello_world.yml
  - command: pwd
  - command: cd HelloWorldApp
  - command: ls
  - commands:
      - dotnet publish -c Release -o out
      - dotnet publish -c Release -o out
  - command: cd out
  - command: ls
  - commands:
      - dotnet HelloWorldApp.dll --urls "http://0.0.0.0:5000"
      - dotnet HelloWorldApp.dll --urls "http://0.0.0.0:5000"
      - dotnet HelloWorldApp.dll --urls "http://172.31.36.14:5000"
