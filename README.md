# vulture-analysis

This repo collects vulture reports for various Python projects. 

After preparing a report, we would like to send it to the respective 
project and ask for feedback. The following is an example text for a 
new issue:

    We used vulture (https://github.com/jendrikseipp/vulture) to search
    for unused code in your project. You can find the report below. It 
    would be great if you could give us feedback about which items are 
    actually used or unused. This would allow us to improve vulture and
    ideally it also helps you to remove obsolete code or even find typos 
    and bugs.

New reports should use the following template:

# Vulture report for Foobar

Command:
    
    vulture src foobar.py --exclude src/external
    
Raw result:

    src/utils/helpers.py:123: Unused function 'make_foobar'
    src/shelve.py:123: Unused function 'get_foo'
    src/main.py:456: Unused variable 'bar'
    
Obvious false-positives:

    src/shelve.py:123: Unused function 'get_foo'
    
Unused code or false-positives:
    
    src/utils/helpers.py:123: Unused function 'make_foobar'
    src/main.py:456: Unused variable 'bar'
