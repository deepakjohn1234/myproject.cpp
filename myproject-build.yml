name: Compile myproject.cpp

on:
  push:
    branches: [ main ]
  pull_request:
    branches: [ main ]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout repository
      uses: actions/checkout@v3

    - name: Compile and run myproject.cpp
      run: |
        g++ -o myproject myproject.cpp
        ./myproject
