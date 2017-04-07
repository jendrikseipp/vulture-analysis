# Vulture report for [system-design-primer](https://github.com/donnemartin/system-design-primer)

We used [vulture](https://github.com/jendrikseipp/vulture) to search
for unused code in your project. You can find the report below. It 
would be great if you could give us feedback about which items are 
actually used or unused. This would allow us to improve vulture and
ideally it also helps you to remove obsolete code or even find typos 
and bugs.

Command:
```
vulture system-design-primer
```

Raw result:

```
system-design-primer/solutions/object_oriented_design/call_center/call_center.py:116: expected an indented block at "def notify_call_completed(self, call):  # ..."
system-design-primer/solutions/object_oriented_design/deck_of_cards/deck_of_cards.py:116: unexpected EOF while parsing at "def shuffle(self):  # ..."
system-design-primer/solutions/object_oriented_design/lru_cache/lru_cache.py:15: expected an indented block at "def append_to_front(self, node):  # ..."
system-design-primer/solutions/object_oriented_design/online_chat/online_chat.py:10: expected an indented block at "def remove_user(self, user_id):  # ..."
system-design-primer/solutions/object_oriented_design/parking_lot/parking_lot.py:121: expected an indented block at "def remove_vehicle(self):  # ..."
system-design-primer/solutions/system_design/query_cache/query_cache_snippets.py:55: invalid syntax at "def get(self, query)"
system-design-primer/solutions/system_design/sales_rank/sales_rank_mapreduce.py:12: invalid syntax at "def mapper(self, _ line):"
system-design-primer/solutions/system_design/social_graph/social_graph_snippets.py:63: unexpected EOF while parsing at "# Use self.lookup to translate a person_id to a Person"
system-design-primer/solutions/system_design/web_crawler/web_crawler_snippets.py:5: invalid syntax at "def __init__(self, db);"
system-design-primer/solutions/object_oriented_design/hash_table/hash_map.py:8: Unused class 'HashTable'
system-design-primer/solutions/object_oriented_design/hash_table/hash_map.py:17: Unused function 'set'
system-design-primer/solutions/object_oriented_design/hash_table/hash_map.py:25: Unused function 'get'
system-design-primer/solutions/object_oriented_design/hash_table/hash_map.py:32: Unused function 'remove'
system-design-primer/solutions/system_design/mint/mint_mapreduce.py:48: Unused function 'steps'
system-design-primer/solutions/system_design/mint/mint_snippets.py:5: Unused variable 'HOUSING'
system-design-primer/solutions/system_design/mint/mint_snippets.py:6: Unused variable 'FOOD'
system-design-primer/solutions/system_design/mint/mint_snippets.py:16: Unused class 'Categorizer'
system-design-primer/solutions/system_design/mint/mint_snippets.py:22: Unused function 'categorize'
system-design-primer/solutions/system_design/mint/mint_snippets.py:32: Unused class 'Transaction'
system-design-primer/solutions/system_design/mint/mint_snippets.py:40: Unused class 'Budget'
system-design-primer/solutions/system_design/mint/mint_snippets.py:45: Unused function 'override_category_budget'
```
