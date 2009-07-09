Mandy - Simplified Hadoop distribution for Ruby code
====================================================

Mandy hides the differences and complexities between running map/reduce tasks locally or distributed or in test environments.

It provides a simple DSL to define new jobs for distribution. See examples/word_count.rb for a very simple demo.
Run the word count example locally with...

    bin/mandy local examples/word_count.rb examples/alice.txt examples/output.txt