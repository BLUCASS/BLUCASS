#!/usr/bin/python
# -*- coding: utf-8 -*-

class PythonDeveloper:

    def __init__(self):
        self.name = "Lucas Batista"
        self.role = "Python Developer"
        self.languages = ["pt_BR", "en_US"]

    def greeting(self):
        print("Hello. Be my guest to explore.")


me = PythonDeveloper()
me.greeting()
