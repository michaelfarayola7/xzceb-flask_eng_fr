import unittest

from translator import english_to_french
from translator import french_to_english

class TestE2F(unittest.TestCase): 
    def test1(self): 
        self.assertEqual(english_to_french('Hello'), 'Bonjour') 
        # test when 2 is given as input the output is 4.
        self.assertNotEqual(english_to_french('Hello'),'Hello') 
        # test when -3.1 is given as input the output is -6.2.
        self.assertNotEqual(english_to_french("None"),'') 
        # test when 0 is given as input the output is 0.
        self.assertNotEqual(english_to_french(0),0)

class TestF2E(unittest.TestCase):
    """French to English tests"""
    def test1(self):
        # Test Bonjour returns Hello
        self.assertEqual(french_to_english('Bonjour'), 'Hello')
        # Test Bonjour does not return Bonjour
        self.assertNotEqual(french_to_english('Bonjour'), 'Bonjour')
        # Test None returns empty string
        self.assertNotEqual(french_to_english("None"), '')
        # Test empty string returns empty string
        self.assertNotEqual(french_to_english(0),0)
        
if __name__=='__main__':
    unittest.main()