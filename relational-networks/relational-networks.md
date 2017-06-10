# vullture report for [relational-networks](https://github.com/kimhc6028/relational-networks)

We used [vulture](https://github.com/jendrikseipp/vulture) to search
for unused code in your project. You can find the report below. It
would be great if you could give us feedback about which items are
actually used or unused. This would allow us to improve vulture and
ideally it also helps you to remove obsolete code or even find typos
and bugs.

### Command
```
vulture relational-networks
```

### Raw results
```
relational-networks/main.py:43: Unused variable 'kwargs'
relational-networks/main.py:138: Unused variable 's_datasets'
relational-networks/model.py:34: Unused function 'forward'
relational-networks/sort_of_clevr_generator.py:11: Unused variable 'question_size'
relational-networks/sort_of_clevr_generator.py:13: Unused variable 'answer_size'
relational-networks/translator.py:2: Unused function 'translate'
```

There might be false positives, which can be prevented by adding them to a
whitelist file. More info [here](https://github.com/jendrikseipp/vulture#usage)
