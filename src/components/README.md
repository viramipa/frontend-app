# frontend-app/README.py

"""
Frontend App Documentation
==========================

A high-quality, maintainable, and scalable frontend application.
"""

__license__ = 'MIT'
__author__ = 'Your Name'

from pathlib import Path

def get_project_root():
    """Returns the path to the project root."""
    return Path(__file__).parent.parent

def get_project_name():
    """Returns the name of the project."""
    return get_project_root().name

def get_project_description():
    """Returns a brief description of the project."""
    return "A high-quality, maintainable, and scalable frontend application."

def get_project_license():
    """Returns the license under which the project is published."""
    return __license__

def get_author_info():
    """Returns information about the project author."""
    return f"Author: {__author__}"

if __name__ == "__main__":
    print(f"Project Root: {get_project_root()}")
    print(f"Project Name: {get_project_name()}")
    print(f"Project Description: {get_project_description()}")
    print(f"Project License: {get_project_license()}")
    print(f"Author Info: {get_author_info()}")