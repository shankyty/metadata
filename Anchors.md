---
anchored_content: &anchor_name This string will appear as the value of two keys.
other_anchor: *anchor_name

# Anchors can be used to duplicate/inherit properties
base: &base
  name: Everyone has same name

foo: &foo
  <<: *base
  age: 10

bar: &bar
  <<: *base
  age: 20
---
