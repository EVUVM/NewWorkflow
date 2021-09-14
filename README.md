# NewWorkflow

name: first

on: [push, pull_request]

jobs:
  job1:
    name: First job
    runs-on: ubuntu -latest
    steps:
    - name: Step one
    - name: Step two
  job2:
    name: Second job
    runs-on: windows-latest
    steps:
    - name: Step one
    - name: Step two



1. Open Datei
2. CD .github/workflows 
3. vim first.yml
